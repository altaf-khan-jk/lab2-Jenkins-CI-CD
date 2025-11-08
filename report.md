# Jenkins CI/CD Lab Report

**Chosen Method:** Webhook (or Polling if you prefer)

**Integration Steps:**
1. Connected Jenkins to GitHub repository.
2. Configured Jenkinsfile for pipeline stages.
3. Set up trigger using Webhook/Poll SCM.

**Challenges:**
- Configuring GitHub webhook URL properly.
- Ensuring Jenkins has access to GitHub (PAT or credentials).

**Resolution:**
- Verified Jenkins connectivity.
- Tested by making changes to README.md and confirming pipeline triggered.