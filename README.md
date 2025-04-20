# Weather Forecast App with LlamaIndex

This is a simple AI-powered Weather Forecast App built using LlamaIndex, Groq LLM, and the OpenWeatherMap API. The app uses LlamaIndex's ReActAgent and custom tools to interactively fetch weather information based on user queries.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Tools and Technologies](#tools-and-technologies)

## Introduction

The Weather Forecast App allows users to query current weather conditions for any city using a conversational agent. It integrates:

- 🧠 LlamaIndex's ReActAgent for tool-aware reasoning

- 🔍 OpenWeatherMap API to fetch real-time weather data

- 🤖 Groq as the backend LLM for generating responses

## Features

- Natural language weather queries (e.g., "What's the weather in Tokyo?")

- Uses custom tool integration with OpenWeather API

- Built with a focus on modular and minimal setup

## Installation

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/Weather-Forecast-App-with-LlamaIndex.git
```

2. Navigate to the project directory:

```
   cd Weather-Forecast-App-with-LlamaIndex
```

3. Set up environment variables by creating a .env file (Use .env.sample as a reference for setting up your .env file.)

## Usage

- Run the Jupyter Notebook:

```
   jupyter notebook langgraph.ipynb
```

## Tools and Technologies

- LlamaIndex

- Groq

- OpenWeatherMap API

- Python, Requests, dotenv
