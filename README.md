# Machine Learning API using FastAPI
Develop a Machine Learning API (Application Programming Interface) using FastAPI.

[![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
[![MIT licensed](https://img.shields.io/badge/license-mit-blue?style=for-the-badge&logo=appveyor)](./LICENSE)
![Python](https://img.shields.io/badge/python-3.9-blue.svg)

## Introduction

This is the last project of the program, congratulations for all the work done until now.

In this project, we aim to help you to discover how to create an API that might be requested to interact with a ML model. This is an interesting solution when you want to keep your model architecture secret or to make your model available to users already having an app. By creating an API, and deployint it, your model can so that receive request using the internet protocol as presented by the illustration below.

![API illustration](https://lh3.googleusercontent.com/-qVJ4ZsbjsmH6CnYbojsAR4ImyHV8yxsFVinunH-pX7VCapGvufcXiPak6YVKIrj9ZdiCHwK5UFtQW8yuU5t83pz6fbqN1F2p74OWuT5dObCPnTBuCYr_P1mUg8arbP0WuEt7j_A)
**Source** : *The benefits of Machine Learning APIs - UbiOps*


## Description

<!-- 
[FastAPI](https://fastapi.tiangolo.com/) # 
-->

You will have a minimal interface demo with [Gradio](https://gradio.app/) & [Streamlit](https://streamlit.io/), this will just serve you to make sure that everything works correctly. Then, you will have to make your own interfaces, those allowing you to interact with a Machine Learning model, that is to say:
- Pass values through the interface;
- Recover these values in backend;
- Apply the necessary processing;
- Submit the previously processed values to the ML model to make the predictions;
- Process the predictions obtained and display them on the interface.

## Instructions

Your task is to understand the frameworks and build an API integrating a ML model using FastAPI.
Clone this repository to use it as a template, do not forget to change the readme at the end of the project.
Your work should follow these next steps.

1.  Build a ML model to predict the Titanic Survivals, during 2 first weeks. 

2.  Build an API using Fast API, during the remaining weeks, to embed the Titanic classification model built.


Upon completion of your project, you are required to write a blog post
on your thought process on medium, LinkedIn, personal blog, or any other
suitable blogging site.

## Rubrics

Machine Learning :

-   **Excellent:** Have an that works correctly with a nice and personalized interface.

-   **Good:** Have an app that launches, makes prediction and shows result.

-   **Fair:** Have an app that launches but having bugs regarding prediction or interface.

API :

-   **Excellent:** Have an that works correctly with a nice and personalized interface.

-   **Good:** Have an app that launches, makes prediction and shows result.

-   **Fair:** Have an app that launches but having bugs regarding prediction or interface.

## Installation

You have two ways in order to setup and run this project.

### Manual Setup

For manual installation, you need to have [`Python3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's `root :: repository_name> ...`  follow the steps below:

- Windows:
        
        python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

**NB:** For MacOs users, please install `Xcode` if you have an issue.

- Run the demo apps (being at the repository root):
        
  Gradio:
    
    - Demo

          python gradio_project/basic_demo/app.py

    - Salary prediction

          python gradio_project/salary/app.py


  - Go to your browser at the following address :
        
      http://127.0.0.1:7860/


<!-- ## Screenshots

<table>
    <tr>
        <th>FastAPI</th>
        <th>FastAPI</th>
    </tr>
    <tr>
        <td><img src="./screenshots/.png"/></td>
        <td><img src="./screenshots/.png"/></td>
    </tr>
</table> -->


## Resources
Here are some ressources you would read to have a good understanding of FastAPI :
- [Tutorial - User Guide](https://fastapi.tiangolo.com/tutorial/)
- [Video - Building a Machine Learning API in 15 Minutes ](https://youtu.be/C82lT9cWQiA)
- [Video - Deploy ML models with FastAPI, Docker, and Heroku ](https://www.youtube.com/watch?v=h5wLuVDr0oc)





## Contributing

Feel free to make a PR or report an issue 😃.

Oh, one more thing, please do not forget to put a description when you make your PR 🙂.

## Author

- [Emmanuel KOUPOH](https://www.linkedin.com/in/esa%C3%AFe-alain-emmanuel-dina-koupoh-7b974a17a/)
[![My Twitter Link](https://img.shields.io/twitter/follow/emmanuelkoupoh?style=social)](https://twitter.com/emmanuelkoupoh)