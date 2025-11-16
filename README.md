# 📬 Swift Mailer
Receives a prompt, drafts emails using Gemini Chat (retaining context via Simple Memory), and sends the formatted output via Gmail. Seamlessly blends advanced LLM capabilities with real-world communication tools.
That's a fantastic project\! Here is a comprehensive and well-structured README file template for your AI Email Dispatcher, incorporating all the details you provided.

-----

An intelligent, memory-aware agent that uses the **Google Gemini Chat Model** to draft and dispatch emails based on simple text prompts, leveraging Gmail for reliable delivery.

## ✨ Features

  * **Intelligent Drafting:** Uses the Gemini Chat Model to generate sophisticated email content from concise user prompts.
  * **Conversational Memory:** Implements `Simple Memory` to retain context across multiple interactions, ensuring high-quality, continuous email threads.
  * **Real-World Integration:** Seamlessly integrates with the Gmail API for reliable and secure email sending.
  * **Structured Output:** Guided by a specific system message to enforce proper email formatting (subject, body, salutations, etc.).

## ⚙️ Architecture Diagram

-----

## 🚀 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need the following accounts and keys:

1.  **Python 3.8+**
2.  **Gemini API Key:** Obtain one from Google AI Studio.
3.  **Gmail API Credentials:** Set up a project in Google Cloud Console and enable the Gmail API. You will need a `credentials.json` file.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/[Your-Username]/SwiftMailer.git
    cd SwiftMailer
    ```

2.  **Create a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required packages:**

    ```bash
    pip install -r requirements.txt 
    # (Assuming you have packages like google-genai, google-auth, pandas, etc.)
    ```

### Configuration

1.  **Set Environment Variables:**
    Create a file named `.env` in the project root and add your API key:

    ```env
    GEMINI_API_KEY="YOUR_GEMINI_API_KEY_HERE"
    ```

2.  **Place Gmail Credentials:**
    Ensure your Gmail API `credentials.json` file is placed in the project root directory.

-----

## 💻 Usage

To start the agent and begin drafting emails, run the main script:

```bash
python main.py
```

The agent will prompt you for an action or a topic. Example interaction:

| Input Prompt | Agent Action |
| :--- | :--- |
| **User:** Draft an email to John confirming the meeting tomorrow. | **Output:** Uses Gemini to draft the confirmation email. |
| **User:** Add a line about the agenda being attached. | **Output:** Uses memory to modify the *previous* draft and includes the new instruction before sending. |

-----

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

-----
Project Link: [https://github.com/[N-JhansiMahalakshmi]/SwiftMailer](https://www.google.com/search?q=https://github.com/%5BYour-N-JhansiMahalakshmi%5D/SwiftMailer)
