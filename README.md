# DecentralGPTGenerationAl

# How to Use

## Prerequisites

install nvidia-container-toolkit, see: https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html

## Start Service

```bash
bash ./start-service.sh <config-name>
```

## Request Serivce

### openai-text api

```bash
bash ./request-service-openai-text.sh <model>
```

### ollama-text api

```bash
bash ./request-service-ollama-text.sh <model>
```

### openai-image api

```bash
bash ./request-service-openai-image.sh <model>
```

## Stop Service

```bash
bash ./stop-service.sh <config-name>
```

## Table: config-name -> model & api-protocol

| config-name             | model                   | api-protocol |
| ----------------------- | ----------------------- | ------------ |
| llama3-8b               | Llama3-8B               | openai-text  |
| llama3-70b_1            | Llama3-70B              | openai-text  |
| llama3-70b_4            | Llama3-70B              | openai-text  |
| qwen1.5-110b_1          | Qwen1.5-110B            | openai-text  |
| qwen1.5-110b_4          | Qwen1.5-110B            | openai-text  |
| yi1.5-34b               | Yi1.5-34B               | openai-text  |
| qwen2-72b_1             | Qwen2-72B               | openai-text  |
| qwen2-72b_4             | Qwen2-72B               | openai-text  |
| falcon2-11b             | Falcon2-11B             | openai-text  |
| openbiollm-llama3-70b_1 | OpenBioLLM-Llama3-70B   | openai-text  |
| openbiollm-llama3-70b_4 | OpenBioLLM-Llama3-70B   | openai-text  |
| minicpm-v2.5            | MiniCPM-Llama3-V2.5     | ollama-text  |
| codestral-22b-v0.1      | Codestral-22B-v0.1      | openai-text  |
| gemma2-27b_4            | Gemma-2-27B             | openai-text  |
| llama3.1-405b_8         | Llama-3.1-405B          | openai-text  |
| mistral-123b_4          | Mistral-123B            | openai-text  |
| flux.1-dev              | FLUX.1-dev              | openai-image |
| nemotron-70b_1          | Llama-3.1-Nemotron-70B  | openai-text  |
| nvlm-70b_2              | NVLM-D-72B              | openai-text  |
| qwen2.5-72b_1           | Qwen2.5-72B             | openai-text  |
| deepseek-coder-v2_2     | DeepSeek-Coder-V2       | openai-text  |
| qwen2.5-coder-32b_1     | Qwen2.5-Coder-32B       | openai-text  |
| qwen2.5-coder-32b_2     | Qwen2.5-Coder-32B       | openai-text  |
| pixtral-124b_4          | Pixtral-124B            | openai-text  |
| llama3.3-70b_1          | Llama3.3-70B            | openai-text  |
| qvq-72b-preview_1       | QVQ-72B-Preview         | openai-text  |
| deepseek-v3_8           | DeepSeek-V3             | openai-text  |
| deepseek-v3_8_h200      | DeepSeek-V3             | openai-text  |
| sana                    | sana                    | openai-image |
| deepseek-r1_8_h200      | DeepSeek-R1             | openai-text  |
| qwen2.5-vl-72b_2        | Qwen2.5-VL-72B-Instruct | openai-text  |
