# **AutoQGen: NLP-Powered Automated Question Paper Generator**

[![license](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://github.com/asahi417/lmqg/blob/master/LICENSE)
[![PyPI version](https://badge.fury.io/py/lmqg.svg)](https://badge.fury.io/py/lmqg)
[![PyPI pyversions](https://img.shields.io/pypi/pyversions/lmqg.svg)](https://pypi.python.org/pypi/lmqg/)
[![PyPI status](https://img.shields.io/pypi/status/lmqg.svg)](https://pypi.python.org/pypi/lmqg/)

## **Project Overview**
AutoQGen is an **NLP-powered automated question paper generation system** designed to streamline the traditionally time-consuming process of crafting question papers. Leveraging advanced **Natural Language Processing (NLP)** algorithms, the system generates contextually relevant, diverse, and high-quality questions for academic assessments.  

AutoQGen empowers educators with a **user-friendly interface** for seamless data input, customizable patterns, and automated question generation, all while ensuring **security, fairness, and efficiency**.  

---
<p align="center">
  <img src="https://github.com/Hari10513/QuestionPaperAutomation/blob/main/assets/qag.png" width="400">
  <br><em> Three distinct QAG approaches. </em>
</p>

---

## **System Architecture**

<p align="center">
  <img src="https://github.com/Hari10513/QuestionPaperAutomation/blob/main/screenshots/system_architecture.png" width="500">
</p>

- **Login Module**: COE (Chief of Examination) and lecturer access.
- **Notes Updating Module**: Manages input content and updates the question bank.
- **NLP Processing Module**: Analyzes and understands the input data.
- **Question Paper Generation Module**: Generates randomized question papers.

***AutoQGen: NLP-Powered Automated Question Paper Generator ([https://questionpaperautomation.orgfree.com/](https://questionpaperautomation.orgfree.com/))*** is a web application hosting our QAG models.

## **Model Development**
The `lmqg` also provides a command line interface to fine-tune and evaluate QG, AE, and QAG models.

## **Model Training**
<p align="center">
  <img src="https://github.com/Hari10513/QuestionPaperAutomation/blob/main/assets/grid_search.png" width="650">
</p>

---
## **Features**

- **Customizable Question Patterns:** Allows educators to customize the format and difficulty.
- **Randomization and Fairness:** Randomized question selection avoids predictability.
- **Multiple Input Formats:** Accepts input as text, PDFs, and documents.
- **Secure Storage:** Uses **MySQL** to securely store questions and patterns. 

---

## **ScreenShots**

<p align="center">
  <img src="https://github.com/Hari10513/QuestionPaperAutomation/blob/main/screenshots/Login_Page.png" width="400">
  <br><em> Login Page. </em>
</p>


<p align="center">
  <img src="https://github.com/Hari10513/QuestionPaperAutomation/blob/main/screenshots/Question_Pattern.png" width="400">
  <br><em> Question Paper Pattern Selection. </em>
</p>


<p align="center">
  <img src="https://github.com/Hari10513/QuestionPaperAutomation/blob/main/screenshots/OutPut_generation.png" width="400">
  <br><em> Generated Output </em>
</p>


<p align="center">
  <img src="https://github.com/Hari10513/QuestionPaperAutomation/blob/main/screenshots/Output.png" width="400">
  <br><em>Output File</em>
</p>

---
## **Technologies Used**

| Component               | Technology                 |
|-------------------------|----------------------------|
| **Programming Language**| Python, PHP               |
| **NLP Libraries**       | HuggingFace Transformers, NLTK |
| **Frontend**            | HTML, CSS, JavaScript     |
| **Backend**             | Flask, PHP                |
| **Database**            | MySQL                     |
| **Framework**           | WAMP Server               |

---

### **Prerequisites**
- Python 3.8+  
- MySQL Database  
- Required Python Libraries
- WAMP Server

---

## Citation
Please cite following paper if you use any resource and see the code to reproduce the model if needed.

- [***AutoQgen***](https://www.autoqg.net/): The QG models ([code to reproduce experiments](https://github.com/asahi417/lm-question-generation)).
```
@inproceedings{ushio-etal-2022-generative,
    title = "{G}enerative {L}anguage {M}odels for {P}aragraph-{L}evel {Q}uestion {G}eneration",
    author = "Ushio, Asahi  and
        Alva-Manchego, Fernando  and
        Camacho-Collados, Jose",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, U.A.E.",
    publisher = "Association for Computational Linguistics",
}
```
- [***A Practical Toolkit for Multilingual Question and Answer Generation, ACL 2023, System Demonstration***](https://arxiv.org/abs/2305.17416): The library and demo ([code to reproduce experiments](https://github.com/asahi417/lm-question-generation/tree/master/misc/2023_acl_qag)).

```
@inproceedings{ushio-etal-2023-a-practical-toolkit,
    title = "A Practical Toolkit for Multilingual Question and Answer Generation",
    author = "Ushio, Asahi  and
        Alva-Manchego, Fernando  and
        Camacho-Collados, Jose",
    booktitle = "Proceedings of the 61th Annual Meeting of the Association for Computational Linguistics: System Demonstrations",
    month = Jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
}
```
