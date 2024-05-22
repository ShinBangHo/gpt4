<div align="center">
This repository contains different examples and usecases showcased in the book <a href="https://appswithgpt.com">Developing Apps with GPT-4 and ChatGPT - 2nd Edition</a>.

<img src="./images/book_cover.png" alt="Book cover" width="300"/>
</div>

Check the branches and releases for different versions of the OpenAI API.

# Usage

### All examples
Install the requirements for all the examples with:

    pip install -r requirements.txt

Each example contains either a jupyter notebook, or a python file that can be run with:

    python [example_folder]/run.py

Some examples require some additional setup.

### Chap3_03_QuestionAnseringOnPDF
Start Redis with

    docker-compose up -d

### Chap3_04_VoiceAssistant
The gradio interface is available at the address displayed in the output.

### Chap5_04_LlamaIndexCustomization
Customize if needed the docker-compose.yml file and start weaviate with

    docker-compose up -d
Alternatively, run:

    docker run -p 8080:8080 -p 50051:50051 cr.weaviate.io/semitechnologies/weaviate:1.24.9