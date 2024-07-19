
# Introduction

Turn text into lifelike spoken audio using Azure Speech Services's TTS

## Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/AJLab-GH/azure_text_to_speech.git
   cd azure_text_to_speech

## docker-template

```bash
pre-commit install
```

---

## Azure Cognitive Services Speech SDK Setup Guide

Newer versions of the Azure Cognitive Services Speech SDK may have
conflicts with SSL and Python libraries. To create an environment
without these conflicts, it is recommended to use a virtual environment,
such as Conda. Follow the setup instructions below to create and configure
your Conda environment.

## Prerequisites

Ensure you have Conda installed. You can download and install it from:
[Anaconda](https://www.anaconda.com/products/distribution) or,
[Miniconda](https://docs.conda.io/en/latest/miniconda.html).

## Setup Instructions

### 1. Recreating the Environment from YAML

To recreate the environment from the `environment.yaml` file:

```bash
conda env create -f environment.yaml
```

Activate the new environment:

```bash
conda activate azure_speech_env
```

## Note - Conda Deactivate

incase you need to deactivate conda use the following commands

```text
conda deactivate
```

## Environment Variables

Set the environment variables for your Azure Cognitive Services subscription
key and region. You can do this in your terminal or within your script.

### Setting Environment Variables in Terminal

```bash
export SPEECH_KEY='your_subscription_key'
export SPEECH_REGION='your_region'
```

## Conclusion

By following these instructions, you can set up a clean and conflict-free
environment for using the Azure Cognitive Services Speech SDK. If you encounter
any issues, ensure all dependencies are correctly installed and that your
environment variables are set properly.

---

This README provides a comprehensive guide for setting up the Azure Speech SDK
in a Conda environment, covering all necessary steps and potential issues.
