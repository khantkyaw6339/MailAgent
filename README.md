# MailAgent

MailAgent is an AI-powered assistant designed to streamline your email tasks and enhance productivity. This project demonstrates the integration of tools, LangGraph, and Gmail, showcasing the power of modern AI agents.

## Features
- **Agent-Based Experience**: 
  - Proactive AI capable of performing specific tasks with minimal user input.
- **Tool Integration**: 
  - Seamless connection to Gmail API for managing emails (drafting, sending, and more).
- **LangGraph**: 
  - Leverages LangChain's LangGraph for orchestrating tasks and workflows efficiently.
- **Gmail Functionality**: 
  - Automated email drafting and sending.
  - Handles user-specific email tasks dynamically.

## Getting Started
### Prerequisites
- Python 3.12.7 or higher
- A Gmail account with API enabled ([Enable Gmail API](https://developers.google.com/gmail/api/quickstart/python))
- OAuth credentials file (`credentials.json`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/khantkyaw6339/MailAgent.git
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
## Usage
1. Open the main notebook file:
   ```bash
   Agent.ipynb
2. Run the notebook:
3. Example query:
- **send an email to example@gmail.com thanking them for coffee and inviting for dinner.**
## Project Architecture
- **Agent: Powered by LangChain for task management.**
- **Tools:**
  - GmailToolkit: Manages Gmail integration for email-related tasks.
- **LangGraph**: 
  - Provides structured task execution and advanced orchestration.
## License
This project is licensed under the MIT License.
