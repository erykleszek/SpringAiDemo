# 🤖 Spring AI Demo

This project demonstrates the integration of **Spring Boot** with **Spring AI** (supporting OpenAI models), and a simple frontend built with **React**.

## 🧩 Architecture

- **Backend (Java, Spring Boot)** – Provides a REST API for generating text responses, images, and recipes.
- **Frontend (React)** – Simple user interface to interact with the API.

## 🚀 Features

### API Endpoints

| Endpoint                | Description |
|-------------------------|-------------|
| `GET /ask-ai?prompt=...` | Get a GPT-4o-based text response |
| `GET /generate-image?prompt=...` | Generate images using DALL·E |
| `GET /recipe-creator?ingredients=...&cuisine=...&dietaryRestrictions=...` | Generate a recipe based on input |

### Key Backend Classes

- `ChatService` – Handles GPT-4o text responses
- `ImageService` – Generates images using DALL·E
- `RecipeService` – Uses prompt engineering to create cooking recipes
- `GenAIController` – Maps HTTP endpoints to services

## 🧠 Requirements

- Java 17+
- Maven
- Node.js 18+
- OpenAI API key
## 📌 Notes

Make sure to provide your OpenAI API key in the application configuration (`application.properties`) 
