```markdown
# 🤖 ChatBot Project

Welcome to the **ChatBot Project**! This chatbot is built using **Microsoft DialoGPT**, a pre-trained language model designed for conversational tasks, integrated with **Flask** as the backend framework. The front-end interface is developed with **HTML**, **CSS**, **JavaScript**, and **jQuery** to create a visually appealing and interactive chat experience.

## 🚀 Installation & Setup

Follow the steps below to install and set up the project:

### 1. 🐍 Install Python

Make sure you have Python installed. If not, download and install Python from the official site:

[Install Python](https://www.python.org/downloads/)

### 2. 📦 Install pip

To install pip, run the following command in your terminal:

```bash
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```

Then install pip by running:

```bash
python3 get-pip.py
```

Ensure pip is successfully installed by checking its version:

```bash
pip --version
```

### 3. ✅ Verify Python & pip Installation

Run the following commands to verify that Python and pip are installed correctly:

```bash
python3 --version
```

```bash
pip --version
```

### 4. ⚙️ Installing Flask and Other Dependencies

After cloning or downloading the project, navigate to the project directory and install the necessary dependencies by running the following command:

```bash
pip install -r requirements.txt
```

This will install **Flask** and any other libraries required for the project.

## ▶️ Running the ChatBot Application

To run the application, follow these steps:

1. Navigate to the project directory:

    ```bash
    cd your/project/directory
    ```

2. Run the Flask application:

    ```bash
    python3 app.py
    ```

Once the server is running, you can access the chatbot by opening your web browser and navigating to the appropriate localhost address (typically `http://127.0.0.1:5000/`).

## 🛠️ What You Will Create

This project will guide you through the process of building a chatbot that can engage in conversations with users using **natural language processing**. The chatbot utilizes **Microsoft DialoGPT**, a powerful pre-trained conversational model, to generate human-like responses.

Throughout this project, you will:

- 🖥️ Set up a Flask server to handle requests.
- 💻 Create an interactive chat interface using **HTML**, **CSS**, **JavaScript**, and **jQuery**.
- 🤖 Integrate **DialoGPT** to provide conversational functionality.
- 📈 Optionally fine-tune the DialoGPT model for more specific conversational needs.

## 🌐 ChatBot Link

The chatbot uses the **Microsoft/DialoGPT-medium** model available on Hugging Face. You can explore the model here:

[DialoGPT-medium](https://huggingface.co/microsoft/DialoGPT-medium)

## 💬 User-HTML

The HTML structure for the user's message is as follows:

```javascript
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';
```

## 🤖 Bot-HTML

The HTML structure for the chatbot's response is as follows:

```javascript
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
```
