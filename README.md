# CRAFT-CRNN System for General OCR task

## Introduction
A few days ago, I made an [OCR project](https://github.com/YIYANGCAI/CRAFT-CRNN-OCR-Pipeline) using [CRAFT](https://arxiv.org/abs/1604.03239) for detection and [CRNN](https://links.jianshu.com/go?to=https%3A%2F%2Farxiv.org%2Fpdf%2F1507.05717v1.pdf). However, that project's inputs require a point where near the nearest target text aera. This project makes a modification that omit the point input and is able to detect all text in the picture.

## How to use the project
the requirements of the project can be found in [original OCR project](https://github.com/YIYANGCAI/CRAFT-CRNN-OCR-Pipeline)
Put the weights of CRAFT and CRNN in the ./weights/ and test images in ./test_data/ Then run
```
python test.py
```
The results is saved in ./result/