# MaoMao Disambiguator Dictionary

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=pytorch&logoColor=white)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=000)](#)

Context-aware dictionary that automatically ranks definitions by semantic relevance
This project will be used to enhance ![MaoMao-Dict](https://github.com/MaoMao-Corp/MaoMao-Dict) performance and making it fully local, privacy-respecting, free of charge, and released as free software in the “free as in freedom” sense.

## Motivation
I'm tired of having to stop every time I encounter a word I don't know, or don't recognize in a particular context. Existing solutions such as popup dictionaries save you from opening new tabs but they still force you to read through every definition entry - sometimes there are a lot - and make a bold guess about which one better fits the context.

Given that English is not my first language, I sometimes struggle to infer the correct definition, which can be really time consuming.

This word disambiguator was created for personal use in mind, to make our daily lives better.

## General Overview
For a given word, predicts the part-of-speech and the lemma within its context window and then gives you the most likely definition/s.
