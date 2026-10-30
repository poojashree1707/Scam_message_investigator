## Scam Message Investigator

### Project Overview

Scam Message Investigator is an AI-powered application that analyzes suspicious messages and identifies potential scam indicators using a locally running Large Language Model (LLM).

Built using Python, Streamlit, and Ollama, the application examines messages for suspicious links, urgent threats, requests for sensitive information, fake offers, impersonation, and other common scam patterns.

It generates a structured investigation report with a risk level, warning signs, explanations, and recommended safety actions.

The application uses a local AI model to process messages without sending them to an external AI API.

### Key Features

* AI-Powered Message Analysis: Examines suspicious messages using a local LLM.

* Risk Level Assessment: Categorizes messages into Low Concern, Medium Concern, or High Concern.

* Message Classification: Identifies the likely category of the message.

* Warning Sign Detection: Highlights suspicious phrases and explains why they may be risky.

* Safety Recommendations: Provides practical actions to protect users.

* Investigation Limitations: Explains what cannot be verified from the message alone.

* Structured JSON Output: Generates organized and consistent investigation reports.

* Local AI Processing: Uses Ollama to run the language model locally.

### How It Works

* The user enters a suspicious message into the application.

* The application sends the message and system instructions to the local Ollama API.

* The Gemma 3:1B model analyzes the message for potential scam indicators.

* The model generates a structured JSON response.

* The application displays the investigation report, including:

Risk Level

Message Type

Summary

Warning Signs

Recommended Safety Actions

Investigation Limitations

### Risk Classification

* Risk Level

Description

* Low Concern

No clear suspicious indicators identified

* Medium Concern

Some potentially suspicious patterns detected

* High Concern

Multiple or significant scam indicators detected


## DEMO 

<img width="1850" height="657" alt="Screenshot 2026-10-30 144410" src="https://github.com/user-attachments/assets/7e664f94-6483-4051-9ec6-bbd652a32f76" />

<img width="1843" height="676" alt="Screenshot 2026-10-30 144431" src="https://github.com/user-attachments/assets/c6d847c7-f25d-4bc4-8218-f0657deceacb" />

### Conclusion

#### The Scam Message Investigator demonstrates how Artificial Intelligence, Large Language Models, and Prompt Engineering can be used to improve digital safety. By analyzing suspicious messages and identifying potential scam indicators, the application helps users make more informed decisions and stay aware of online threats. Using Ollama and the Gemma 3:1B model enables local AI-based analysis while reducing dependence on external AI APIs. This project provides a practical approach to promoting scam awareness and safer digital communication.

