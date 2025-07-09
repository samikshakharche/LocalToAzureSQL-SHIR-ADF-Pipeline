# SHIR Installation Guide

This guide explains how I installed and connected the Self-hosted Integration Runtime (SHIR) to Azure Data Factory.

## Steps:

1. Go to Azure Portal → Azure Data Factory → Manage → Integration Runtimes
2. Click **+ New** → Select **Self-hosted** → Name it `YourameSHIR`
3. Click **Create** → You’ll get an authentication key and download link
4. Download and install the SHIR agent on your PC (approx. 50–60 MB)
5. During installation, paste the authentication key to link the SHIR with your ADF
6. After installation, go back to ADF and confirm SHIR shows **Running**

## Note:
- SHIR should be installed on a system that has access to the local SQL Server
- Avoid multiple SHIR installations on the same machine unless needed

