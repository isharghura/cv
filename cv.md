# Experience

## Frizzle (YC S25)
**ML Engineer Intern**  
New York City, USA | May 2026 - Aug 2026

**Tech:** Python, Google Cloud Platform, Vertex AI, LangSmith, Pydantic, OpenAI, Anthropic, Azure AI Foundry

- Unified LLM Infrastructure: Developed a Python-based LLM inference engine to dynamically route asynchronous requests across Google Vertex AI, Azure Foundry, AWS Bedrock, and OpenAI.
- Custom Dataset Curation: Compiled and formatted specialized datasets of real student math assignments for model training, testing, and performance benchmarking.
- Data Quality Assurance: Conducted rigorous data quality reviews using a hybrid approach of manual inspection, Python scripting, and programmatic LLM verification.
- Automated Evaluation Pipelines: Built an LLM-as-a-judge evaluation framework utilizing Gemini 2.5 Pro to systematically benchmark frontier models including Claude, GPT, and Llama.
- Experiment Tracking: Integrated LangSmith into the evaluation pipeline to log experiment sessions, trace token usage, and monitor multi-provider costs.
- Model Fine-Tuning: Fine-tuned Gemini 2.5 Flash Lite on Google Cloud Vertex AI using custom instructional data to improve domain-specific math grading accuracy.
- Structured Output Engineering: Built dynamic schema parsers to translate complex Pydantic models into strict, provider-compatible JSON schemas.
- Cloud Authentication & Deployment: Managed API integrations and secure authentication flows using Google Application Default Credentials and cloud service accounts.

## G-Research
**Software Engineer Intern**  
Remote | May 2026 - Aug 2026

**Tech:** Apache Spark, Scala, Maven, Python, Bash, Docker, Kubernetes, Kind, Colima, GitHub Actions, Armada

- Built a Python-based E2E test orchestration tool for a distributed job scheduler (Armada), automating cluster provisioning, Docker image validation, and Maven/Scala test execution in CI and local dev environments
- Solved a multi-platform Docker image compatibility issue by resolving manifest-list images to host-specific digests via the Docker/registry API, preventing kind load failures in containerd-backed environments
- Replaced fragile shell scripts with a robust Python CLI integrated into GitHub Actions, adding real-time log streaming, structured error handling, and deterministic validation gates to eliminate silent pipeline failures
- Redesigned a Spark-on-Kubernetes build system, replacing imperative shell scripts with declarative Maven profiles and an Ant-based validator to support single-command builds across Scala 2.12/2.13 and Spark 3.3/3.5/4.1

---

## JSI Telecom
**ML Engineer Intern**  
Ottawa, Canada | Jan 2026 - Apr 2026

**Tech:** PyTorch, Hugging Face, NVIDIA Triton, vLLM, Kubernetes, MLflow

• Architected an enterprise-grade ML benchmarking platform evaluating 50+ AI models (LLMs, Whisper,
Florence-2) across 100+ language pairs to inform model selection based on accuracy, latency, cost and content policy
compliance for sensitive domain tasks (weapons identification, controlled substance classification)
• Engineered a unified asynchronous backend abstraction layer over vLLM, NVIDIA Triton, and Agno, deploying
containerized pipelines via Kubernetes Helm charts with INT8/FP16 quantization for GPU optimization
• Implemented comprehensive evaluation pipelines integrating 12+ quality metrics (BLEU, ROUGE, BERTScore,
CER, WER) and an LLM-as-Judge system, centralizing experiment tracking in Azure ML and MLflow
• Built automated dataset pipelines supporting Hugging Face Hub streaming and synthetic data generation via
back-translation, scaling to 100K+ samples and reducing manual curation by 80%
• Implemented batch inference across model evaluation pipelines, improving benchmarking throughput by 2-3x and
reducing total evaluation time for 50+ models

---

## JSI Telecom
**AI Infra Engineer Intern (Stars Award)**  
Ottawa, Canada | Sep 2025 - Dec 2025

**Tech:** Kubernetes, AWS, Helm, Docker, C#

• Designed and operated CloudNativePG on Kubernetes (AWS) to deliver highly available PostgreSQL for AI
workloads, including replication, failover testing, and rolling upgrades
• Implemented backup, restore, and point-in-time recovery using Barman Cloud Plugin and Helm, enabling
zero-downtime recovery and secure archiving to object storage for ML pipelines
• Established observability and security using Prometheus, Grafana, and RBAC, with automated secret rotation and
hardened container images to protect AI data platforms
• Improved developer experience by extending internal UIs, automating C# validation tests, and authoring monitoring
documentation, accelerating onboarding and reducing configuration errors

---

## Apache Airflow
**Software Engineer Intern**  
Remote | Sep 2025 - Dec 2025

**Tech:** Python, MCP, LLMs, Docker, AWS

• Investigated the proposed AIP-91 MCP server, analyzing discussions from AWS engineers and the Airflow PMC on
enabling natural-language LLM interaction with Apache Airflow, as part of the MLH Fellowship
• Developed and validated Airflow metrics using OpenTelemetry to track DAG parse times across versions

---

## Meta
**Production Engineer Intern**  
Remote | Jun 2025 - Sep 2025

**Tech:** Python, Docker, Linux, Bash, MySQL, Flask, NGINX

• Selected as one of 44 from 4,000+ applicants for a Meta x MLH fellowship focused on system reliability
• Automated CI/CD pipelines via Bash, reducing manual deployment time by 90% and increasing frequency by 30%
• Optimized NGINX to handle 10k+ req/min, ensuring 99.9% uptime through custom rate limiting
• Deployed Prometheus and Grafana dashboards, cutting incident response times by 50% via real-time monitoring

---

## HackVerify
**Founder**  
Ottawa, Canada | Mar 2025 - Mar 2026

**Tech:** Python, Supabase, Beautiful Soup, SQL, JavaScript, Flask

- Building a tool that automates cheat checks for software competitions, speeding verification processes by 90%+
- Web scraped large amounts of data using Beautiful Soup and analyzed patterns to detect cheating
- Implemented LinkedIn OAuth to simplify login, signup, and verification flows
- Stored scraped and verification data in Supabase for secure authenticated access

---

## SunnySide
**Software Engineer**  
Remote | Apr 2024 - Sep 2025

**Tech:** Python, Supabase, TypeScript, React Native

- Implemented Supabase Auth for Google Sign-In, improving accessibility and authentication workflows
- Developed responsive login, registration, and mood-tracking pages across mobile platforms
- Performed testing and simulations through Android Emulator to ensure cross-device compatibility
- Transformed Figma designs into mobile-responsive React Native components

---

## Global Affairs Canada
**Data Engineer Intern**  
Gatineau, Canada | Jun 2024 - Dec 2024

**Tech:** T-SQL, SSMS, SSIS, Visual Studio, Git, Agile

- Designed ETL pipelines for a large-scale data migration project
- Performed T-SQL queries to extract and transform data for migration workflows
- Created functions and stored procedures to identify inconsistencies in source data
- Collaborated with teams to streamline migration workflows and reduce migration errors

---

## CU InSpace - Carleton Rocketry
**Embedded Software Engineer**  
Ottawa, Canada | Feb 2024 - May 2024

**Tech:** C, QNX, LoRa, Shell Scripting, Git

- Wrote C code interfacing with hardware and transmitting real-time telemetry over LoRa using QNX
- Implemented GNSS metadata blocks storing GPS and GLONASS satellite usage data
- Encoded sensor data into radio packets for transmission to the ground station via websocket distribution

---

# Projects

## Autonomous Inspection Robot
Apr 2026

**Tech:** Raspberry Pi, OpenCV, Ollama, Python, Ubuntu

- Engineered an autonomous robot using Raspberry Pi 4B with crack and leak detection
- Built a local vision-LLM pipeline using OpenCV and Ollama (LLaVA-Phi3)
- Enabled offline image analysis and automated reporting
- Configured Ubuntu 22.04 with ROS 2 and SLAM support
- Integrated voice-command systems
- Optimized edge AI performance for multimodal embedded workloads

---

## Light-following Roomba — 2nd Place @ uOttaHack 7
Jan 2025

**Tech:** C, C++, Arduino, QNX, Python

- Developed Arduino firmware in C for light sensor communication
- Sent sensor data to Raspberry Pi via I2C
- Implemented QNX-based real-time movement control software
- Built autonomous navigation logic for responsive movement

---

## FoodBank AI — Hack the Hill
Sep 2024

**Tech:** Python, ResNet, PyTorch, Flask, React, PostgreSQL

- Fine-tuned a pretrained ResNet model for food image classification using 3800+ food images
- Leveraged PyTorch for model fine-tuning, achieving a 20%+ classification accuracy improvement
- Optimized preprocessing with batch processing, reducing inference time by 30%+
- Designed and implemented a PostgreSQL database to manage user points and food submissions

---

## AI Chatbot
Jun 2023

**Tech:** Python, TensorFlow, Keras, Waitress, Flask, JavaScript, HTML/CSS

- Developed an intelligent chatbot using TensorFlow and Keras to mimic human conversation
- Trained the chatbot model on curated conversational patterns, tags, and responses
- Revamped the frontend UI using HTML/CSS to improve user experience
- Deployed the application using Waitress and Flask
