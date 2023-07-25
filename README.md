# LLM Workflow Engine (LWE) OpenAI Provider plugin

OpenAI Provider plugin for [LLM Workflow Engine](https://github.com/llm-workflow-engine/llm-workflow-engine)

Access to non-chat [OpenAI](https://platform.openai.com/docs/models) models (GPT-3, etc.)

## Installation

### From packages

Install the latest version of this software directly from github with pip:

```bash
pip install git+https://github.com/llm-workflow-engine/lwe-plugin-provider-openai
```

### From source (recommended for development)

Install the latest version of this software directly from git:

```bash
git clone https://github.com/llm-workflow-engine/lwe-plugin-provider-openai.git
```

Install the development package:

```bash
cd lwe-plugin-provider-openai
pip install -e .
```

## Configuration

Add the following to `config.yaml` in your profile:

```yaml
plugins:
  enabled:
    - provider_openai
    # Any other plugins you want enabled...
```

## Usage

From a running LWE shell:

```
/provider openai
/model model_name text-davinci-003
```
