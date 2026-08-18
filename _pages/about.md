---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, I'm Samar!

I'm currently pursuing my M.S. in Computer Science at UC San Diego, with a focus in AI and NLP. Previously I graduated from the University of Central Florida with a bachelor's degree (B.S.) in Computer Science and a minor in Mathematics.

I'm currently seeking new grad positions, please feel free to reach out if you are interested!

Experience
======
## Software Engineering Intern
**Soar Tech** — *Orlando, FL*  
*June 2025 – September 2025*

- Reduced hallucinated entity extractions by integrating three fine-tuned ModernBERT models (0.91 F1) as a verification layer within a PDF agent, cross-checking its own NER outputs before finalizing results
- Enabled domain-specific NER fine-tuning with Python and Hugging Face by building a data pipeline with Docling and the OpenAI API that generated 60,000+ structured data points
- Containerized models with Docker and served them via vLLM behind a FastAPI and PostgreSQL backend

## Undergraduate Research Assistant
**Sage Lab, University of Central Florida** — *Orlando, FL*  
*March 2024 – August 2025*

- Enabled automated detection of accessibility issues in UI/UX designs by building an automated-labeling pipeline
- Powered the project's accessibility-prediction models by mining the GitHub and Stack Overflow APIs with Python to build a ground-truth dataset of 70,000+ JSON metadata files and images
- Improved accessibility-prediction accuracy by extracting text-size, text-contrast, and image-contrast features from UI images as model training inputs

Projects
======
## [Lady Bug](https://github.com/LadyBugML/ladybug)  
**Python, Flask, MongoDB, Github** — *Published at ICSME 2025 (Auckland, NZ)*  
*August 2024 – May 2025*

- Built a GitHub bot for UI-enhanced bug localization in mobile apps, combining bug-report and source-code embeddings with UI data — a novel approach later published at ICSME 2025
- Benchmarked 5+ frontier LLMs for the localization task, driving a 15% improvement over the prior methodology
- Implemented CI/CD pipeline (GitHub Actions) with automated custom benchmark suite of 20 real-world GitHub repositories with known bugs to validate the tool's localization accuracy against ground-truth reports
- Recognition: Judge's Choice Award (Student Research Symposium), showcase finalist, $250 scholarship

## [Agentic 3D Gaussian Splatting](https://github.com/juliexwu/agentic-splatting)  
**Python, LangGraph, gsplat**  
*March 2026 – June 2026*

- Built a multi-agent Actor-Critic pipeline in LangGraph where multiple VLM agents (Gemma) iteratively tune 3D Gaussian Splatting training hyperparameters, removing the need for manual configuration tuning
- Enabled the pipeline to initialize directly from raw video by implementing a GPU-accelerated pre-filtering stage: frame extraction (ffmpeg) and point-cloud generation (pycolmap)
- Achieved an average PSNR gain of 0.52 dB over the initial configuration across agentic refinement loops

## [Formula 1 Track Optimization](https://github.com/SamarKaranch/F1-Track-Optimizer)  
**Python, FastF1, CVXPY, Clarabel, Matplotlib**  
*February 2026 – March 2026*

- Formulated minimum lap-time optimization as a nonconvex control problem, resolving a bilinear friction/curvature coupling via Sequential Convex Programming into per-iteration SOCPs solved with Clarabel
- Validated on 5 real F1 circuits using FastF1 telemetry, beat Las Vegas Grand Prix lap time by 8.11s

## [Focus Flow](https://github.com/colintle/FocusFlow)  
**Next.js, React, TypeScript, Tailwind CSS, Firebase**  
*August 2023 – December 2023*

- Delivered a full-stack planner app with a calendar view by building reusable React/TypeScript components styled with Tailwind CSS and syncing task state in real time through Firebase listeners
- Streamlined CRUD operations across the app by designing and implementing REST APIs for Firebase
