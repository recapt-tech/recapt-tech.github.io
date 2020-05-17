---
layout: page
title: Product Description
include_in_header: false
description:  All you need to know about the technical requirements and technologies used.
fontawesome_icon_name: microchip
---

# Product Description

One of the core requirements is the ease of use of the solution both in terms of learning how to use the system and in the number of steps required.  The set of requirements can be summarized in the following list:

1.	**Automation**: Instead of the user having to manually enter each line item of the receipt into the app for tracking, the solution needs to automatically extract information and store it.
2.	**Simplicity**: The user is not requirement to purchase new hardware or gadgets in order to be able to use the solution.
3.	**Efficiency**: The app should have a small memory and processing footprint and the user is able to install the app and use it on a typical smartphone i.e. the user is not required to have a high-end smartphone.

### Technology Description

Optical Character Recognition (OCR) is the process of using computer vision to automatically detect and extract text from an image (e.g. printed receipt). Many traditional OCR systems rely on hand crafted rules to detect text which achieves sub optimal accuracy.

This app uses an OCR engine that is driven by Deep Learning. Deep learning is the next evolution of machine learning that learns through an artificial neural network and allows the machine to analyze data and learn complex structures. Incorporating deep learning into OCR has allowed the accuracy to improve drastically and the algorithm is able to extract text, quantities and prices of different lines. 

After detecting text using the OCR engine, the data is fed into the parser to extract relevant details and discard irrelevant ones. Later, this parsed data is shown to the user for review and confirmation. Finally, the data is stored in the cloud so that the user can access it any time and on any device.


![technical-steps](/assets/content/steps.png)
