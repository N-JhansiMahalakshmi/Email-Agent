# 📬 Email Agent
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


The agent will prompt you for an action or a topic. Example interaction:

| Input Prompt | Agent Action |
| :--- | :--- |
| **User:** Draft an email to John confirming the meeting tomorrow. | **Output:** Uses Gemini to draft the confirmation email. |
| **User:** Add a line about the agenda being attached. | **Output:** Uses memory to modify the *previous* draft and includes the new instruction before sending. |

-----
Project Link: [https://github.com/[N-JhansiMahalakshmi]/Email-Agent](https://www.google.com/search?q=https://github.com/%5BYour-N-JhansiMahalakshmi%5D/Email-Agent)
