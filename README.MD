# MahderAI App: LLM Fine-tuning Data Formats

This repository showcases the required data formats for fine-tuning Large Language Models (LLMs) using the MahderAI App. For each supported task, you'll find a sample `.jsonl` file demonstrating the input format needed for training within the MahderAI App. A corresponding `.npy` file illustrates the processed data suitable for inference on your local machine after downloading your fine-tuned checkpoints.

**Important:**

*   **Training (MahderAI App):** Use the **`.jsonl` file format** as input for training your models *directly on the MahderAI platform.*
*   **Inference (Local Machine):** Use the **`.npy` file format** *after* downloading your fine-tuned model checkpoints from MahderAI. This format represents the data that the model expects for inference for your specific task.

## Supported Tasks and Data Formats:

Here's a breakdown of the data formats for each task:

*   **Binary Classification:**
    *   **JSONL Input (for MahderAI App training):** [binary_format.jsonl](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/binary_classification/binary_format.jsonl)
    *   **Numpy Processed Data (for local inference):** [binary_processed_format.npy](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/binary_classification/binary_processed_format.npy)

*   **Multi-Class Classification:**
    *   **JSONL Input (for MahderAI App training):** [multi_class_format.jsonl](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/Multi_class_classification/multi_class_format.jsonl)
        *   **Note:** The sample data uses the following label mapping:
            *   0: Technology
            *   1: Sports
            *   2: Politics
            *   3: Entertainment
            *   4: Business
    *   **Numpy Processed Data (for local inference):** [multiclass_processed_format.npy](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/Multi_class_classification/multiclass_processed_format.npy)

*   **Chatbot:**
    *   **JSONL Input (for MahderAI App training):** [chatbot_format.jsonl](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/chatbot/chatbot_format.jsonl)
    *   **Numpy Processed Data (for local inference):** [chatbot_processed_format.npy](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/chatbot/chatbot_processed_format.npy)

*   **Translation:**
    *   **JSONL Input (for MahderAI App training):** [translation_format.jsonl](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/translation/translation_format.jsonl)
    *   **Numpy Processed Data (for local inference):** [translate_processed_format.npy](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/translation/translate_processed_format.npy)

*   **Extractive Question Answering:**
    *   **JSONL Input (for MahderAI App training):** [extractive_format.jsonl](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/extractive_question_answering/extractive_format.jsonl)
    *   **Numpy Processed Data (for local inference):** [extractive_processed_format.npy](https://github.com/mahdertesf/LLM-Fine-tunning-Data-Format/blob/main/extractive_question_answering/extractive_processed_format.npy)