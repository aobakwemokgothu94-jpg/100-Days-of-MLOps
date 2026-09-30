# 100 Days of MLOps - Progress & Curriculum

Welcome to the **100 Days of MLOps** tracking repository! This curriculum covers end-to-end Machine Learning Operations, including environment management, data versioning, experiment tracking, feature stores, containerization, model serving, monitoring, CI/CD, orchestration, and Kubernetes deployments

A hands-on MLOps repository demonstrating production-ready machine learning lifecycle practices. Features automated data pipelines, experiment tracking, CI/CD workflows for model deployment, automated testing, containerized microservices, and continuous performance monitoring
---

## 📊 Overview & Status

* **Course Level:** Level 1
* **Overall Progress:** 21% Completed (21 / 100 tasks completed)

---

## 🗺️ Roadmap & Daily Tasks

### Completed Tasks (Days 1–21)

| Day | Task | Status |
| :--- | :--- | :---: |
| **Day 1** | Create a Python Virtual Environment for ML | ✅ Completed |
| **Day 2** | Fix a Broken JupyterLab Server Configuration | ✅ Completed |
| **Day 3** | Fix a Broken uv Lockfile Specification | ✅ Completed |
| **Day 4** | Add a .gitignore and Untrack Committed Artifacts | ✅ Completed |
| **Day 5** | Fix a Broken ML Workflow Makefile | ✅ Completed |
| **Day 6** | Fix a Broken Ruff and Black Configuration | ✅ Completed |
| **Day 7** | Test and Package the Fraud-Detection Module | ✅ Completed |
| **Day 8** | Fix a Broken pre-commit Configuration | ✅ Completed |
| **Day 9** | Fix a Broken Cookiecutter Template for ML Projects | ✅ Completed |
| **Day 10** | Initialize DVC in an Existing Git Repository | ✅ Completed |
| **Day 11** | Track a Dataset with DVC | ✅ Completed |
| **Day 12** | Fix a Broken DVC Remote and Push to SeaweedFS | ✅ Completed |
| **Day 13** | Pull DVC-Tracked Data from Remote | ✅ Completed |
| **Day 14** | Create a DVC Pipeline for Data Processing | ✅ Completed |
| **Day 15** | Parameterize a DVC Pipeline | ✅ Completed |
| **Day 16** | Track ML Metrics with DVC | ✅ Completed |
| **Day 17** | Run and Compare DVC Experiments | ✅ Completed |
| **Day 18** | Version Datasets and Models Across Git Branches | ✅ Completed |
| **Day 19** | Complete a Production DVC Pipeline with SeaweedFS Remote | ✅ Completed |
| **Day 20** | Start the MLflow Tracking Server | ✅ Completed |
| **Day 21** | Log an ML Experiment to MLflow | ✅ Completed |

---

### Upcoming Tasks (Days 22–100)

#### MLflow & Experimentation (Days 22–30)
- [ ] **Day 22:** Create and Organize MLflow Experiments
- [ ] **Day 23:** Search, Compare, and Triage MLflow Runs
- [ ] **Day 24:** Enable MLflow Autologging
- [ ] **Day 25:** Register, Version, and Manage Model Lifecycle
- [ ] **Day 26:** Log a Model with a Signature and Validate Inputs
- [ ] **Day 27:** Load Model from Registry with Custom Preprocessing
- [ ] **Day 28:** Fix a Broken MLflow Project and Re-Run It
- [ ] **Day 29:** Fix MLflow's Remote Artifact-Store Wiring (PostgreSQL + SeaweedFS)
- [ ] **Day 30:** End-to-End MLflow: Register, Serve, and Monitor the Champion

#### Model Training & Optimization Pipelines (Days 31–40)
- [ ] **Day 31:** Fix a Broken Config-Driven Training Setup
- [ ] **Day 32:** Make a Training Script Reproducible (Seed Discipline)
- [ ] **Day 33:** Fix a Broken Evaluation Script and Metrics Report
- [ ] **Day 34:** Fix a Broken Cross-Validation Loop (Stratified + Aggregates)
- [ ] **Day 35:** Fix a Broken Optuna Tuner with MLflow Logging
- [ ] **Day 36:** Fix a Multi-Model Bake-Off in the MLflow Compare View
- [ ] **Day 37:** Fix a Four-Stage Training Pipeline's Inter-Stage Wiring
- [ ] **Day 38:** Fix a Parallel-Training Bake-Off (n_jobs Backend)
- [ ] **Day 39:** Make a PyTorch Trainer Device-Aware with Checkpointing
- [ ] **Day 40:** Fix and Complete a Five-Stage Training Capstone

#### Feature Stores, Secrets & Data Quality (Days 41–49)
- [ ] **Day 41:** Scaffold a Feast Feature Repository and Build a Training Set
- [ ] **Day 42:** Define a Feast Feature View (Entity + Field Schema)
- [ ] **Day 43:** Materialize Features and Read Them from the Online Store
- [ ] **Day 44:** Store MLflow's Admin Password in HashiCorp Vault
- [ ] **Day 45:** Authenticate MLflow to Vault via AppRole and Fix Its KV Policy
- [ ] **Day 46:** Author Data-Quality Expectations with Great Expectations
- [ ] **Day 47:** Debug a Failing Great Expectations Checkpoint
- [ ] **Day 48:** Enforce a Data-Quality Checkpoint as a Blocking CI Gate
- [ ] **Day 49:** Secrets + Data-Quality Integration Capstone

#### Containerization & Docker (Days 50–56)
- [ ] **Day 50:** Create Docker Image for ML Training Environment
- [ ] **Day 51:** Create Multi-Stage Docker Build for ML Serving
- [ ] **Day 52:** Fix a Broken Jupyter + MLflow + SeaweedFS Compose Stack
- [ ] **Day 53:** Fix a Broken PyTorch Dockerfile (CPU-Wheel URL)
- [ ] **Day 54:** Push ML Model Images to Container Registry
- [ ] **Day 55:** Fix a Broken Dockerfile HEALTHCHECK and EXPOSE
- [ ] **Day 56:** Fix a Docker CI Pipeline with Git-SHA Tagging

#### Model Serving & Deployment Strategies (Days 57–66)
- [ ] **Day 57:** Serve an ML Model with Flask
- [ ] **Day 58:** Serve an ML Model with FastAPI
- [ ] **Day 59:** Run Batch Predictions on a Dataset
- [ ] **Day 60:** Package a Model as a BentoML Service
- [ ] **Day 61:** Deploy a Model-Serving Container via Portainer
- [ ] **Day 62:** Implement A/B Testing for Model Deployment
- [ ] **Day 63:** Async Predictions with a Redis-Backed Worker
- [ ] **Day 64:** Serve Multiple Models Behind Unified API Gateway
- [ ] **Day 65:** Simulate a Canary Rollout for Model Updates
- [ ] **Day 66:** Production Model Serving with Docker Compose

#### Monitoring, Observability & Retraining Gates (Days 67–75)
- [ ] **Day 67:** Add Prometheus as a Grafana Data Source
- [ ] **Day 68:** Build a Grafana Time-Series Panel for Prediction Accuracy
- [ ] **Day 69:** Build a Grafana Table Panel for Per-Feature Data Drift
- [ ] **Day 70:** Enforce Accuracy Gates with an Evidently Test Suite and a Grafana Alert
- [ ] **Day 71:** Build a 4-Panel Model-Overview Grafana Dashboard
- [ ] **Day 72:** Configure a Grafana Contact Point and Notification Policy
- [ ] **Day 73:** Promote a Retrained Model via a Champion/Challenger Gate
- [ ] **Day 74:** Add a Custom Business Metric and a Grafana Version Variable
- [ ] **Day 75:** Fix and Complete an End-to-End Monitoring Stack: Prometheus, Grafana, Evidently

#### CI/CD & Automation Pipelines (Days 76–84)
- [ ] **Day 76:** Create CI Pipeline for ML Code Linting and Testing
- [ ] **Day 77:** Fix a Failing Data-Quality Job in Gitea Actions
- [ ] **Day 78:** Parallelise Tests via a Gitea Actions Matrix Strategy
- [ ] **Day 79:** Publish CI Training Artefacts via upload-artifact
- [ ] **Day 80:** Wire Repository Secrets into a Gitea Actions Workflow
- [ ] **Day 81:** Tag a Release and Publish to the Gitea Package Registry
- [ ] **Day 82:** Compose Gitea Workflows via workflow_call
- [ ] **Day 83:** Revert a Broken ML Release via the Gitea Revert Button
- [ ] **Day 84:** Enforce Branch Protection on the main Branch

#### Pipeline Orchestration & Cloud Native (Days 85–96)
- [ ] **Day 85:** Submit Your First Argo Workflow
- [ ] **Day 86:** Fix a Broken Argo DAG Dependency Chain
- [ ] **Day 87:** Pass Data Between Argo Steps with Output Parameters and Branching
- [ ] **Day 88:** Fix a Missing @task Decorator in a Prefect Flow
- [ ] **Day 89:** Parallel Model Training with Argo withParam Fan-Out
- [ ] **Day 90:** Automated Retraining with Argo CronWorkflow
- [ ] **Day 91:** Production ML Pipeline: Argo Workflows + MLflow on Kubernetes
- [ ] **Day 92:** Fix a Service targetPort Mismatch on a Kubernetes Deployment
- [ ] **Day 93:** Fix a Broken HorizontalPodAutoscaler scaleTargetRef
- [ ] **Day 94:** Fix a Broken KServe InferenceService storageUri
- [ ] **Day 95:** Complete a Kubeflow Pipeline and Run It via the KFP UI
- [ ] **Day 96:** Deploy a GitOps Application via the ArgoCD NEW APP Form

#### End-to-End Capstone Series (Days 97–100)
- [ ] **Day 97:** Capstone (1/4): End-to-End MLOps System — Train, Register, Serve
- [ ] **Day 98:** Capstone (2/4): Monitoring and Automated Retraining
- [ ] **Day 99:** Capstone (3/4): GitOps Continuous Deployment with ArgoCD
- [ ] **Day 100:** Capstone (4/4): Close the Loop with Prometheus + Grafana Observability
