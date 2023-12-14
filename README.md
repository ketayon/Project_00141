# quantumopenai_QNLP_internship_project

![lambeq](https://github.com/hosen20/quantumopenai_QNLP_internship_project/assets/84079430/35d85e30-12da-4112-9524-b0153e9be9ef)


### Introduction:
This project was done as part of quantumopenai 40 days internship.
In this project about natural language processing classical, hybrid and quantum pipelines were built and a comparison between the three approaches was made.
### The Team:
1. Dhruv Sachdeva
2. Hussein Shiri
3. Kiran Kaur
4. Maksym Husarov
5. Rishi Koushik Reddy Thippireddy

### How the project is organized:
This project contains 4 folders and 1 pdf:
1. sentences folder: contains a pdf for web scraping, collected sentences and the filtered sentences.
2. classical_pipeline folder: contains classical pipeline jupyter notebook with the sentences used.
3. hybrid_pipeline folder: contains hybrid pipeline jupyter notebook with the sentences used.
4. quantum_pipeline folder: contains quantum pipeline jupyter notebook with the sentences used.
5. research_paper: a small research paper for this project as a pdf.

### Technologies used:
- Python
- Spark
- Spark-nlp
- Jupyter notebook
- Google colab
- Lambeq

### Comparison:

|           | classical | hybrid | quantum |
| --------- | ----------| ------ | ------- |
| time      | shortest  | medium | longest |
| memory    | least     | medium | biggest |
| accuracy  | best      | worst  | medium  |

In this table the time to complete, memory consumption and accuracy were compared.

It is reasonable that the classical pipeline is the best choice now. Quantum nlp is still a new field while classical nlp has been worked on a lot and many advances in the classical approach have been added to the classical programs. Also Spark-nlp is known to be the fastest, most advanced and most accurate nlp tool.

For a comparison between the hybrid and quantum case, although the quantum case got better accuracy with fewer training sentences, it's memory consumption was more than that of the hybrid pipeline. But a thing to note is that the quantum simulator used for both hybrid and quantum pipeline was without noise which could make the results a lot worse if noise was added, so the classical pipeline still wins even more.

![Screenshot from 2023-11-03 00-52-24](https://github.com/hosen20/quantumopenai_QNLP_internship_project/assets/84079430/74be433d-4bc7-4752-998a-f3bfa3b0fd68)


! [QuantumAI.pdf](https://github.com/ketayon/Project_00141/files/13673403/QuantumAI.pdf)



