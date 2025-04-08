# Are-SLMs-Performant?

This repository houses python notebooks used to fine tune, evaluate and compare performance of Small Language Models (SLMs) used to answer the following question -

<p align="center">Can Small Language Models (SMLs) display a comparable performance to LLMs in extracting information from HTML?</p>

Also, I have published a Substack article discussing the approach I take to tackle this question, my finding, thoughts and more!

### 📦 Installation

```
git clone https://github.com/pradyGn/are-SLMs-performant.git
cd are-SLMs-performant
pip install requirements.txt
```

### 🧪 Notebooks

`2025-05-26_finetuning-SML.ipynb`: Contains code to fine tune a language model of your choice.

`2025-05-20_evaluate-SML.ipynb`: Contains code to perform inference on the fine tuned language model.

`2025-04-07_results-comparison.ipynb`: Contains helper functions and usage examples to compare the performance of the fine tuned language model.

### 📁 Folder Structure
```
are-SLMs-performant/
├── notebooks/
│   ├── 2025-05-26_finetuning-SML.ipynb
│   ├── 2025-05-20_evaluate-SML.ipynb
│   └── 2025-04-07_results-comparison.ipynb
├── results/
│   ├── Llama-3.2-1B_test_dataset_output.parquet
│   ├── Llama-3.2-1B_unseen_test_dataset_output.parquet
│   ├── ReaderLM-v2_test_dataset_output.parquet
│   └── ReaderLM-v2_unseen_test_dataset_output.parquet
├── README.md
├── .gitignore
└── requirements.txt
```

### 🔗 References

- [Substack Article](https://gprady.substack.com/p/fine-tuning-small-language-models)
- [Huggingface Dataset Repository](https://huggingface.co/datasets/Jiraya/html_to_json_information_extraction_dataset)

### 🙋‍♂️ Contact

- [LinkedIn](https://www.linkedin.com/in/pradyumangangan/)
- pradyuman.gangan02@gmail.com
