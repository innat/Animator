# Animator

<div align="left">
    <img src="./assets/image.gif" width="30%" />
</div>

![Python](https://img.shields.io/badge/python-3.10.6-green)
![PyTorch](https://img.shields.io/badge/pytorch-2.0-orange)
![Transformers](https://img.shields.io/badge/transformers-4.28.1-yellow)
![Diffusers](https://img.shields.io/badge/diffusers-0.16.1-blue)


  
## 🤖 Model

TODO

## 🖌️ Visual Output

Some output of **Stage 1**.

<p float="left">
  <img src="./assets/1.png" width="25%" />
  <img src="./assets/2.png" width="25%" />
  <img src="./assets/3.png" width="25%" />
</p>

<p float="left">
  <img src="./assets/5.png" width="25%" />
  <img src="./assets/6.png" width="25%" />
  <img src="./assets/7.png" width="25%" />
</p>

Some output of **Stage 2**.

<p float="left">
  <img src="./assets/96.jpg" width="40%" />
  <img src="./assets/97.jpg" width="40%" />
</p>

<p float="left">
  <img src="./assets/98.jpg" width="40%" />
  <img src="./assets/99.jpg" width="40%" />
</p>

## 🚀 Transformation

Styling process of an input image with **Animator**. With `scale = 0.1` of controlnet

| Input  |  Control Scale (CS) 0.1 |
:-------------------------:|:-------------------------:
<img src="./assets/ref.png" > |  <img src="./assets/200.png"  width="99%">

Keeping the `lora scale = 1.0`, varying the `control scale` produces smooth transformation by injecting target style into the input image, shown below.

| **CS 0.4**  |  **CS 0.5** | **CS 0.6** 
:-------------------------:|:-------------------------:|:-------------------------:
<img src="./assets/199.png"> | <img src="./assets/198.png"> | <img src="./assets/197.png"> 

| **CS 0.7** | **CS 0.8** | **ALL** 
:-------------------------:|:-------------------------:|:-------------------------:
<img src="./assets/196.png"> | <img src="./assets/195.png"> | <img src="./assets/ref.gif">

## 🔥 Gradio UI

![](./assets/gradioui.gif)

