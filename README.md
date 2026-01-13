# ✈️ Airline AI Assistant

An AI-powered customer support assistant for an airline, built to bring together key concepts of modern LLM engineering: **multi-modality**, **tool calling**, and **agentic workflows**.

This project is part of an applied learning journey and demonstrates how a real-world airline assistant could interact with users using text, images, and audio, while also querying a database for structured information.

---

## 🚀 Features

* **Multi-modal AI assistant**

  * Text-based conversational support
  * Image generation using **DALL·E 3** (via GPT-4o)
  * Audio generation for spoken responses

* **Tool calling & data access**

  * Database lookups for airline-related information
  * Ticket price storage and retrieval via **SQLite**

* **Agentic foundations**

  * Early step toward an agentic workflow where the assistant decides when to call tools

* **Basic authentication**

  * Simple login system implemented with **Gradio**
  * Credentials can be edited directly in the code

---

## 🎨 Image Generation (Artist Tool)

The project includes an image-generation function ("artist") powered by **DALL·E 3**.

⚠️ **Price alert**: each generated image costs approximately **$0.04**, so image generation should be used sparingly.

---

## 🔐 Authentication

The Gradio interface includes basic authentication.

**Default credentials (for demo purposes only):**

* **Username:** `vince`
* **Password:** `bananas`

> ⚠️ These credentials are not secure and should be changed before any real deployment.

---

## 🗄️ Database

* **SQLite** is used as a lightweight database
* Stores airline ticket prices
* Queried by the assistant via tool calling

---

## 🎯 Project Goals

This project aims to demonstrate:

1. A multi-modal AI assistant with **image and audio generation**
2. **Tool calling** integrated with a real database
3. A practical step toward **agentic AI workflows**

---

## 🎥 Demo

▶️ **[Watch the demo video](https://drive.google.com/file/d/1BRsTY40Zcxef8q4byTOmL2JlMnml9WBi/view?usp=sharing)**

---

## 🛠 Installation

1. Clonez ce dépôt sur votre machine locale :
2. 
 git clone the repository then cd into it

3. Install **uv** from Astral :
   ```bash
   pip install uv
   ```

4.Install project depencies and syncronize environment :
   ```bash
   uv sync
   ```

5. Run the project :
   ```bash
   uv run Airline_AI_Assistant_with_tool_calling.py
   ```

---

## 🧪 Status

This project is a learning and experimentation environment and is **not production-ready**.

---
