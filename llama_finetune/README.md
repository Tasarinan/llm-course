Instruction Fine Tuning: Making General Purpose Assistants:
- Transforms the model into a general purpose assistant by adding control over its behavior
- It aims to create an LLM that understands cues as instructions rather than text
- It would likely interpret the prompt as an instruction and expands the capabilities of models
- This enables LLMs to learn to perform new tasks introduced through additional instructions and does not require large amount of task-specific data


Different Fine Tunings:

1. Low Rank Adaptation (LoRA): It adopts low-rank approximations on the downstream layers of LLMs. It optimizes computational resources and expenses by fine-tuning LLMs to certain tasks and datasets
2. SFT: It is a standard method where a trained LLM undergoes supervised fine-tuning with limited sample data. The model learns from this data and generates responses that align with expected outputs. It can be used for Instruction fine-tuning.
3. Reinforcement Learning from Human Feedback 


Fine Tune Examples

[Fine Tune LLM with Axolotl](https://github.com/andysingal/llm-course/blob/main/llama_finetune/Fine_tune_LLMs_with_Axolotl.ipynb)

[Template-free axolotl](https://hamel.dev/notes/llm/finetuning/09_template_free.html)

[Finetune_7B_dpo.ipynb](https://github.com/andysingal/llm-course/blob/main/llama_finetune/Finetune_7B_dpo.ipynb)

[Finetune-tech-keywords](https://github.com/andysingal/llm-course/blob/main/llama_finetune/finetune_tech_keywords.ipynb)

[Fine_tune_SegFormer](https://github.com/andysingal/llm-course/blob/main/llama_finetune/Fine_tune_SegFormer_on_custom_dataset.ipynb)

[Supervise fine-tune casual language model](https://www.kaggle.com/code/aisuko/supervise-fine-tune-casual-language-model)

[Fine-Tune LLMs in 2024](https://www.determined.ai/blog/llm-finetuning)

[FineTune-RoBERTa-LORA](https://new.qq.com/rain/a/20240213A02E8M00)

[Phi_2_+_QLoRA+dialogsum](https://github.com/andysingal/llm-course/blob/main/llama_finetune/Phi_2_%2B_QLoRA%2Bdialogsum.ipynb)

[RoBERTa Sequence Classification Fine-Tuning with LORA]

[Fine-Tuning-Custom-Dataset](https://github.com/andysingal/llm-course/blob/main/llama_finetune/fine-tuning-custom-dataset.ipynb)

[AutoLOra-Mergimg](https://github.com/andysingal/llm-course/blob/main/llama_finetune/%F0%9F%A7%9C_AutoLoRAMerging_(Ties%2C_Dare%2C_MagnitudePrune).ipynb) 

[2-bit-quantization](https://github.com/andysingal/llm-course/blob/main/llama_finetune/2_bit_Quantization.ipynb)

[Fine-Tuning Gemma Models in Hugging Face](https://github.com/andysingal/llm-course/blob/main/llama_finetune/examples_notebook_sft_peft.ipynb)

[Fine-Tune Gemma with ChatML](https://github.com/andysingal/llm-course/blob/main/llama_finetune/gemma-lora-example.ipynb)

[Fine-tune BERT for sentiment analysis](https://skimai.com/fine-tuning-bert-for-sentiment-analysis/)

[Fine-tune Jamba](https://github.com/andysingal/llm-course/blob/main/llama_finetune/fine_tune_Jamba.ipynb)

[layered_inference_with_airllm_70B_LLM_Inference_on_a_Single_4GB_GPU](https://github.com/andysingal/llm-course/blob/main/llama_finetune/notebooks/layered_inference_with_airllm_70B_LLM_Inference_on_a_Single_4GB_GPU.ipynb) 

[Refusal-Demo](https://github.com/andysingal/llm-course/blob/main/llama_finetune/notebooks/refusal_demo.ipynb)

spectrum: [Fine-tune with Spectrum](https://github.com/cognitivecomputations/spectrum)

[Combined DPO + ReFT Finetuning Tutorial](https://github.com/andysingal/llm-course/blob/main/llama_finetune/notebooks/Combined_ORPO_REFT_FineTuning_LLAMA3.ipynb) 

[Build a memory-efficient MoE model from anything, in seconds](https://github.com/EricLBuehler/mistral.rs/blob/master/docs/ANYMOE.md)

[sentence_transformer_fine_tuning](https://huggingface.co/spaces/DoctorSlimm/sentence_transformer_fine_tuning/blob/main/app.py)


Dolphin models use this technique to target the most important layers to fine-tune, like in their recent Qwen2-72B version  

[Qwen2-VL-Fine-Tuning-LLaMA-Factory](https://github.com/AIAnytime/Qwen2-VL-Fine-Tuning/blob/main/Qwen_2_VL_2B.ipynb)

[Fine-Tuning ModernBERT](https://drchrislevy.github.io/posts/modern_bert/modern_bert.html)



Resources:
- [GGUF/GGML/Llama.cpp](https://github.com/andysingal/llm-course/blob/main/llama_finetune/file_types.md)
- [Determined-AI-LLM](https://www.determined.ai/blog/llm-finetuning)
- [ViT-fine-tuning](https://github.com/olonok69/LLM_Notebooks/blob/main/image/Image_classification_NSWF_full_training.ipynb)
- [Using Wandb](https://wandb.ai/site/solutions/llm-fine-tuning)
- [Finetune-flashatten](https://medium.com/@yernenip/optimizing-phi-2-a-deep-dive-into-fine-tuning-small-language-models-9d545ac90a99)
- [Exploring mergekit for Model Merge, AutoEval for Model Evaluation, and DPO for Model Fine-tuning](https://medium.com/towards-data-science/exploring-mergekit-for-model-merge-and-autoeval-for-model-evaluation-c681766fd1f3)
- [Wandb-finetuning](https://wandb.ai/fully-connected/blog/distilbert)
- [Finetune-Llama3-with-LLaMA-Factory](https://github.com/andysingal/llm-course/blob/main/llama_finetune/notebooks/Finetune_Llama3_with_LLaMA_Factory.ipynb)
- [Fine_tune_Llama_3_with_ORPO](https://github.com/andysingal/llm-course/blob/main/llama_finetune/notebooks/Fine_tune_Llama_3_with_ORPO.ipynb)
- [Mergoo: Efficiently Build Your Own MoE LLM](https://huggingface.co/blog/alirezamsh/mergoo)


<img width="900" alt="Screenshot 2024-02-05 at 4 11 08 PM" src="https://github.com/andysingal/llm-course/assets/20493493/81eef3c8-d3a5-4a3b-a0dd-174dd7c65de1">

<img width="553" alt="Screenshot 2024-04-15 at 11 15 27 AM" src="https://github.com/andysingal/llm-course/assets/20493493/48667f68-e5a5-4722-b090-f8f277f1ff1e">


## Memory optimization
### Vllm
- https://vllm.readthedocs.io/_/downloads/en/latest/pdf/ 
- https://sumanthrh.com/post/distributed-and-efficient-finetuning/ 
- https://www.philschmid.de/deepspeed-lora-flash-attention 
- https://mer.vin/2024/02/flash-attention-2/
- https://quickaitutorial.com/five-technique-vllm-torch-flash_attention-super-local-llm/


##Automate finetuning

[AutoQuantize](https://github.com/andysingal/llm-course/blob/main/llama_finetune/%F0%9F%A4%96_AutoQuantize_(GGUF%2C_AWQ%2C_EXL2%2C_GPTQ).ipynb)

[AutoBitnet](https://github.com/andysingal/llm-course/blob/main/llama_finetune/%F0%9F%8C%8A_AutoBitnet.ipynb)

[AutoQuant](https://github.com/andysingal/llm-course/blob/main/llama_finetune/notebooks/%E2%9A%A1_AutoQuant.ipynb)


Merge models
[LM-Cocktail: Resilient Tuning of Language Models via Model Merging](https://pypi.org/project/LM-Cocktail/) 

[Phi-3-mini-128k-instruct](https://huggingface.co/microsoft/Phi-3-mini-128k-instruct/blob/main/sample_finetune.py)

Notebooks:
[smol-vision](https://github.com/merveenoyan/smol-vision)

