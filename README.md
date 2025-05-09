# CMPE-258 Assignment-5 Customize-llm-using-unsloth

This repository showcases a series of experiments with open-source Large Language Models, focusing on optimization techniques using Unsloth and practical deployment scenarios.

## Repository Overview

The project documentation is available as a comprehensive video tutorial: [YouTube - Comprehensive LLM Fine-tuning, Pre-training, and Deployment with Unsloth](https://youtu.be/3ENSHptjJCU)

## Component Details

### a) Model Fine-tuning (a_model_finetuning/)

This section demonstrates fine-tuning techniques applied to four leading open-source LLMs:

* Llama 3.1 (8B) - Optimized for programming tasks
* Mistral NeMo (12B) - Enhanced conversational abilities
* Gemma 2 (9B) - Domain adaptation experiments
* Phi-3.5 (mini) - Knowledge-specific tuning

Each implementation includes dataset processing, training configuration, and performance assessment.

### b) Language Acquisition (b_language_pretraining/)

This component demonstrates how to teach an existing LLM a completely new language through continued pre-training with Unsloth. The notebook covers:

* Data collection for the target language
* Tokenization considerations
* Training strategy and hyperparameters
* Evaluation of language proficiency

### c) Multi-purpose Templates (c_specialized_templates/)

This section explores specialized chat templates for:

* Text classification tasks
* Natural conversation flows
* Extended context handling in TinyLlama
* Multi-dataset integration

The notebooks provide practical approaches to template customization and task-specific optimization.

### d) Preference Learning (d_preference_optimization/)

This component implements two modern reward modeling techniques:

* ORPO (Off-policy Ranked Policy Optimization)
* DPO (Direct Preference Optimization)

The implementation demonstrates how to align models with human preferences and improve output quality.

### e) Advanced Fine-tuning (e_checkpoint_continuation/)

This section shows how to resume and extend fine-tuning from existing checkpoints, including:

* Checkpoint loading and validation
* Training continuation strategies
* Performance tracking across training phases

### f) Healthcare Application (f_healthcare_assistant/)

This practical application focuses on developing a mental health support chatbot using:

* Microsoft Phi-3 architecture
* Unsloth optimization techniques
* Domain-specific datasets
* Safety and ethical considerations

### g) Production Deployment (g_deployment_pipeline/)

The final component demonstrates the complete workflow from fine-tuning to real-world deployment:

* Model optimization for inference
* Export to Ollama format
* Local deployment setup
* Performance benchmarking

## Getting Started

Each component includes a self-contained Colab notebook. To begin:

1. Navigate to your component of interest
2. Launch the respective Colab notebook
3. Configure GPU runtime (T4/P100/V100 recommended)
4. Follow the step-by-step implementation

## Technical Requirements

* Google Colab account with GPU access
* Google Drive space for model storage
* Understanding of transformer models and fine-tuning concepts

## Video Guide

The accompanying video tutorial walks through:

1. Environment setup for each component
2. Dataset preparation and processing
3. Model configuration and training
4. Results analysis and benchmarking
5. Practical applications and deployment considerations

The video comprehensively covers all seven components in a single walkthrough.

## Additional Resources

* [Unsloth Documentation](https://docs.unsloth.ai/)
* [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
* [Ollama Deployment Guide](https://ollama.com/docs)
