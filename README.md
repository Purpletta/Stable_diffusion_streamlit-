# Stable diffusion with streamlit
Homework on the subject "Computer workshop".

## About
In this project, we implemented the streamlit application for working with neural networks (stable diffusion for generating images from text entered by the user).
Note that image generation in this project takes place using a CPU.

## Usage
Firstly, clone this repository
```
git clone https://github.com/Purpletta/Stable_diffusion_streamlit
```
Secondly, install the necessary dependencies:
```
pip install -r requirements.txt
```
Next, you need to follow the link: https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main to get an access token (you need to select the "write" option). Now run the command: 
```
huggingface-cli login
```
and insert your token.

You are ready to run application:
```
streamlit run src/main.py
```

## Source
stable-diffusion: https://huggingface.co/runwayml/stable-diffusion-v1-5

streamlit: https://streamlit.io/
