# Microsoft Foundry Demos - AI Summit NYC 2026

Welcome to the Microsoft Foundry hands-on labs and demos for AI Summit NYC 2026!

## Overview

This repository contains everything you need to get started with Microsoft Foundry, including:

- **Development Environment**: A fully configured devcontainer with Python 3.12, Jupyter, and Azure tools
- **Hands-on Labs**: Step-by-step notebooks to create and deploy Foundry projects
- **Documentation**: Comprehensive guides for setup, deployment, and customization

## Getting Started

### Quick Start

1. **Open in Development Environment**
   - Use GitHub Codespaces or VS Code Dev Containers
   - All dependencies are pre-configured

2. **Configure Azure Credentials**
   - Copy `.env.sample` to `.env`
   - Fill in your Azure credentials

3. **Run the Quickstart Lab**
   - Navigate to `labs/01-quickstart.ipynb`
   - Follow the step-by-step instructions to create your first Foundry project

## What's Included

### Development Tools

- **Python 3.12** environment
- **Jupyter** for interactive notebooks
- **Azure CLI** for Azure resource management
- **Azure Developer CLI (azd)** for simplified deployments
- **Bicep CLI** for infrastructure as code
- **VS Code AI Toolkit** for AI development

### Labs

- `labs/01-quickstart.ipynb` - Create your first Foundry project with agents

### Documentation

Explore the documentation sections:

- [Azure Account Setup](azure_account_setup.md) - Set up your Azure environment
- [Local Development](local_development.md) - Run and develop locally
- [Deployment](deployment.md) - Deploy to Azure
- [Observability](observability.md) - Monitor and trace your agents
- [Troubleshooting](troubleshooting.md) - Common issues and solutions

## Architecture

This solution demonstrates how to build AI agents using Azure AI Foundry with:

- **Agent Service**: Managed AI agents with conversational capabilities
- **File Search**: Knowledge retrieval from uploaded documents
- **Azure OpenAI**: Powered by GPT models
- **Monitoring**: Built-in tracing and telemetry

## Next Steps

1. Complete the [Azure Account Setup](azure_account_setup.md)
2. Run through the quickstart lab
3. Explore the sample questions and use cases
4. Customize the agent for your needs

## Resources

- [Azure AI Foundry Documentation](https://learn.microsoft.com/azure/ai-foundry/)
- [Agent Service Transparency Note](https://learn.microsoft.com/azure/ai-foundry/responsible-ai/agents/transparency-note)
- [GitHub Repository](https://github.com/nitya/get-started-with-ai-agents)

## Support

For issues and questions:
- Check the [Troubleshooting Guide](troubleshooting.md)
- Review [Sample Questions](sample_questions.md)
- Open an issue on GitHub
