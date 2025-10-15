---
layout: page
title: End-to-End RAG System
description: Question Answering with Retrieval-Augmented Generation
img: assets/img/rag_project.jpg
importance: 2
category: Research Projects
---

<section id="overview">
  <h2><b>Overview</b></h2>
  <p>
    Built a comprehensive Retrieval-Augmented Generation (RAG) system for question answering over a curated knowledge base of Carnegie Mellon University and Pittsburgh-related events. The system addresses the limitations of large language models by providing them with relevant external context at inference time, reducing hallucinations and improving factual accuracy.
  </p>
  
  <h3><b>Key Contributions</b></h3>
  <ul>
    <li>
      <b>Knowledge Base Construction:</b> Curated a comprehensive corpus of over 144,000 text chunks by systematically crawling and parsing 29 seed URLs, including web pages and PDF documents. Implemented parallel crawling with intelligent chunking (1000 characters with 200-character overlap) to ensure contextual continuity.
    </li>
    <li>
      <b>Multi-Strategy Retrieval:</b> Designed and evaluated three retrieval approaches—sparse (BM25), dense (FAISS with SentenceTransformers), and hybrid fusion using weighted score combination. Achieved optimal performance with hybrid retrieval using α=0.25 interpolation weight.
    </li>
    <li>
      <b>Reader Architectures:</b> Implemented two reading strategies: concatenation-based reader for direct context fusion and a BART-based decoder for intelligent summarization of retrieved passages, balancing information density with context length.
    </li>
    <li>
      <b>Model Fine-tuning:</b> Applied RAFT-inspired fine-tuning on LLaMA-3.2-1B using 464 manually validated QA pairs with distractor documents, improving the model's ability to distinguish relevant from irrelevant context.
    </li>
    <li>
      <b>Comprehensive Evaluation:</b> Achieved best performance with LLaMA-3B + Sparse retrieval (EM: 0.1589, F1: 0.3202), demonstrating that sparse retrieval excels in factual precision while larger models improve semantic fidelity. Conducted rigorous statistical significance testing and category-based analysis across factual, temporal, causal, and descriptive questions.
    </li>
  </ul>

  <h3><b>System Architecture</b></h3>
  <p>
    The RAG pipeline integrates three core components: (1) a <b>retriever</b> that selects relevant documents using BM25, dense embeddings, or hybrid fusion; (2) a <b>reader</b> that either concatenates or summarizes retrieved content; and (3) a <b>generator</b> (LLaMA variants) that produces precise answers conditioned on the retrieved context. The modular design enables systematic evaluation of different retrieval and generation strategies.
  </p>

  <h3><b>Tools & Technologies</b></h3>
  <ul>
    <li><b>Retrieval:</b> BM25 (sparse), FAISS with SentenceTransformers (dense), Reciprocal Rank Fusion (hybrid)</li>
    <li><b>Embeddings:</b> all-MiniLM-L6-v2 for semantic similarity</li>
    <li><b>Models:</b> LLaMA-3.2-1B, LLaMA-3.2-3B, LLaMA-8B, BART-base</li>
    <li><b>Web Scraping:</b> BeautifulSoup, PyPDF2, ThreadPoolExecutor for parallel crawling</li>
    <li><b>Evaluation:</b> Exact Match, F1, ROUGE-L, BLEU, BERTScore</li>
  </ul>

  <h3><b>Key Findings</b></h3>
  <ul>
    <li>Sparse retrieval (BM25) achieved highest factual precision (EM: 0.1589) for entity-centric questions</li>
    <li>Dense retrieval provided richer contextual understanding but introduced semantic drift</li>
    <li>Hybrid fusion with α=0.25 offered best balance between precision and recall</li>
    <li>Larger generators (LLaMA-3B) improved fluency and semantic alignment</li>
    <li>Fine-tuning on domain-specific QA pairs improved answer grounding</li>
    <li>The system exhibited minimal hallucination due to strong grounding in curated knowledge base</li>
  </ul>

  <h3><b>Impact</b></h3>
  <p>
    Delivered a fully functional, modular RAG system demonstrating strong performance on domain-specific question answering. The project showcases expertise in information retrieval, large language models, system design, and rigorous experimental evaluation. The findings provide valuable insights into retrieval strategy selection based on question types and computational constraints.
  </p>

  <p><b>Course:</b> 11-711 Advanced Natural Language Processing, Carnegie Mellon University</p>
  <p><b>Team:</b> Prachi Goyal, Medha Hira, Raj Maheshwari</p>
</section>

<a href="https://github.com/RajWorking/RAG">GitHub Repository</a>
<br>
<a href="https://drive.google.com/file/d/1ivmTwKAxu6PVoKPRcyzRjeQASio7Sky8/view?usp=sharing">Project Report</a>