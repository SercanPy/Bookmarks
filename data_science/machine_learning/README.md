# MACHINE LEARNING

- This [Github repository](https://github.com/louisfb01/start-llms?tab=readme-ov-file) provides further resources to get started with LLMs.
- Medium [article](https://andreshat.medium.com/llm-quantization-naming-explained-bedde33f7192) on Large Language Model naming convention used by the generative AI community.

**NAVIGATION**
- [RAG](/data_science/machine_learning/retrieval_augmented_generation/README.md)


<!-- ####################################################################### -->
## Theoretical AI
<!-- ####################################################################### -->

### Articles
- [Attention explained](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/) by Jay Alammar

- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)

- [Interfaces for Explaining Transformer Language Models](https://jalammar.github.io/explaining-transformers/) by Jay Alammar
    - [Github project](https://github.com/jalammar/ecco)

- [On the Opportunities and Risks of Foundation Models](https://arxiv.org/abs/2108.07258) - surveys a range of topics on foundational models (large langauge models are a large part of them).

- [A Primer in BERTology: What we know about how BERT works](https://arxiv.org/abs/2002.12327) - provides an excellent overview of what we understand about BERT


### Papers
- 2024 [AdvPrompter: Fast Adaptive Adversarial Prompting for LLMs](https://arxiv.org/abs/2404.16873) by Meta Research
    - an **unsupervised** approach to generating successful adversarial prompts to enable resilience against jailbreaking attacks.


### Books
- [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 3rd Edition](/PDFs/Hands%20On%20Machine%20Learning%20-%20Concepts%20Tools%20and%20Techniques%20to%20Build%20Intelligent%20Systems%20-%202nd%20edition.pdf) by Aurélien Géron
    - [Publisher's page](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)
    - 2nd edition pdf [download link](https://powerunit-ju.com/wp-content/uploads/2021/04/Aurelien-Geron-Hands-On-Machine-Learning-with-Scikit-Learn-Keras-and-Tensorflow_-Concepts-Tools-and-Techniques-to-Build-Intelligent-Systems-OReilly-Media-2019.pdf)

- [Hands-On Large Language Models](https://www.oreilly.com/library/view/hands-on-large-language/9781098150952/) by Jay Alammar & Maarten Grootendorst [NOT YET RELEASED]

- [Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch?utm_source=raschka&utm_medium=affiliate&utm_campaign=book_raschka_build_12_12_23&a_aid=raschka&a_bid=4c2437a0&chan=mm_github) by Sebastian Raschka [PRE-RELEASE]
    - [Github](https://github.com/rasbt/LLMs-from-scratch)
    - [YouTube video](https://www.youtube.com/watch?v=kPGTx4wcm_w) - "Developing an LLM: Building, Training, Finetuning" by Sebastian Raschka. A high-level, no-code overview that explains the development of an LLM, featuring numerous figures from the book 'Build a Large Language Model (From Scratch)', which itself focuses on the underlying code that implements these processes.


### Courses
- Coursera - [Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms)

- Princeton - [Understanding Large Language Models](https://www.cs.princeton.edu/courses/archive/fall22/cos597G/) - useful course material, and offers a sensible schedule/order in which to cover relevant topics.



<!-- ####################################################################### -->
## Applied AI
<!-- ####################################################################### -->

[**RAG folder**](/retrieval_augmented_generation/README.md)
### Courses
- Nvidia - [Deploying a Model for Inference at Production Scale](https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+S-FX-03+V1) - MLOps for neural network models using different frameworks (PyTorch, Tensorflow, ...)

- Nvidia - [Generative AI with Diffusion Models](https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+S-FX-14+V1)
    - **Enrolled**

### Videos
- OpenAI developer conference 2024 - [maximising LLM performance](https://youtu.be/ahnGLM-RC1Y?si=1hvPU9h8vhtC67yG) - explanation of when to use prompt engineering, RAG, and/or fine-tuning, and how to evaluate performance.


<!-- ####################################################################### -->
## Frameworks
<!-- ####################################################################### -->

Relevant frameworks are
- PyTorch (DL)
- Tensorflow (DL)
- Keras (DL)
- LlamaIndex (LLMs)
- Langchain (LLMs)

### Articles
- PyTorch - [Deep Learning with PyTorch: A 60 Minute Blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html?highlight=minute%20blitz) - an official PyTorch tutorial


### Videos
- PyTorch - [tutorial series](https://youtube.com/playlist?list=PLqnslRFeH2UrcDBWF5mfPGpqQDSta6VK4&si=v9TQt8-wNaTuCdHl) by Partick Loeber
- PyTorch - [beginner series](https://youtube.com/playlist?list=PL_lsbAsL_o2CTlGHgMxNrKhzP97BaG9ZN&si=udl48pZgEXcrvsMA) by Brad Heintz



<!-- ####################################################################### -->
## Running LLMs locally
<!-- ####################################################################### -->

- Ollama [docker image](https://hub.docker.com/r/ollama/ollama) - allows running of following [models](https://ollama.com/library) from the terminal.
- [Continue.dev](https://docs.continue.dev/setup/configuration#local-and-offline-configuration) - VS Code extension to run local LLM models for coding.
- [OpenWebUI](https://docs.openwebui.com/) - an offline UI for using local LLMs.