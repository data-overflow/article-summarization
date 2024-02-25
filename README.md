# Global Article Summarization and Link Analysis using Intel oneAPI

## Problem Statement
In today's fast-paced world, there is an overwhelming number of articles and updates that impact our
lives. However, finding the most important articles and understanding them can be quite challenging.
Even when you find the articles, extracting meaningful insights can be difficult.
The challenge is to develop an interactive platform that leverages advanced language processing
techniques to filter articles based on user inputs (E.g., Articles on Virat Kohli in IPL 2023, Interim Budget
Details for 2024, etc.) and provide concise, relevant summaries.

## Proposed Solution
![Methodology](imgs/methodology.png)

## Architecture Diagram
![Artchitecture Diagram](imgs/Architecture.svg)

## Intel OneAPI Integration
The project was initially prototyped locally, exploiting my AMD Ryzen 5 CPU and Nvidia GeForce GTX 1650 GPU for computation. However, since scikit-learn doesn't offer support for GPUs I wasn't efficiently utilizing my hardware for performance. 

The project was then ported to Intel oneAPI Cloud Platform, and I was able to gain ridiculous performance gains. The platform also makes onboarding easy with ready-made python kernels that comes with all the necessary modules preinstalled. 


## Video Demo
[![Video Demo](https://img.youtube.com/vi/suqpWYhphFE/0.jpg)](https://www.youtube.com/watch?v=suqpWYhphFE)
- https://www.youtube.com/watch?v=suqpWYhphFE
