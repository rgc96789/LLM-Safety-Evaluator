# LLM Safety Evaluator

A lightweight AI governance tool that evaluates large language model outputs for safety and reliability.

This project demonstrates human-in-the-loop AI evaluation workflows used in modern AI systems.

## Features

• LLM output generation  
• Safety and hallucination evaluation  
• Prompt-based scoring system  
• AI governance demonstration

## Technologies

Python  
LLM APIs  
Prompt engineering  
AI evaluation pipelines

## Project Structure

ai-test-generation-tool/
│
├── generate_tests.py
├── sample_code.py
├── requirements.txt
└── README.md

## How to Run

Install dependencies:

pip install -r requirements.txt

Run the script:

python generate_tests.py

## Example Output

Generated tests:

def test_discount():
    assert calculate_discount(100, 0.1) == 90
