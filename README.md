# AI Assistant for VR Arena

## Project Description

This project is an AI assistant for a website that consults clients on various aspects related to a VR arena. The assistant helps visitors learn about available game options, event conditions, and other related queries, while also collecting their contact details for follow-up.

**Main Features:**
- Real-time consultation for website users.
- Collection of contact details: Name, phone number, email, service, and preferred method of communication.
- Searching for existing contacts in the CRM system.
- Creating new contacts and leads in the CRM.
- Transferring conversation history from Voiceflow to the CRM.

## Technologies Used

- **Python** – the primary language for implementing business logic and API integrations.
- **JavaScript** – for developing the client-side interface and interactive website features.
- **Voiceflow** – a platform for designing and configuring dialogue scenarios.
- **OpenAI API (Playground)** – provides the AI capabilities for the assistant.
- **API Integration** – enables interaction with the CRM system (Kommo.com) and other external services.

## Architecture

1. **User Interface:**  
   The website features a chat interface through which users interact with the AI assistant.

2. **Backend:**
   - Developed using Python to handle conversation logic, integrate with the OpenAI API, and manage data.
   - Utilizes a custom prompt in OpenAI Playground to generate responses based on a predefined database and scenarios.

3. **CRM Integration (Kommo.com):**
   - Searches for existing contacts in the CRM database.
   - Creates new contacts and leads when necessary.
   - Transfers the conversation history and additional details (date, time, service, and preferred method of contact) to the CRM.

4. **Voiceflow:**
   - The dialogue flow is designed in Voiceflow, allowing for flexible management of conversation scenarios and sequential steps.

## Implementation Stages

### 1. Client Interview
- Conduct meetings to clarify requirements.
- Gather information on usage scenarios, functional requirements, and constraints.
- Obtain the necessary database for integration.

### 2. Creating the Technical Specification (TS)
- Develop a detailed TS outlining the assistant's functionality, interfaces, and algorithms.
- Review and refine the document in collaboration with the client.

### 3. Development and Configuration
- Create and optimize the prompt in OpenAI Playground.
- Implement the consultation functionality on the website.
- Integrate with the CRM system for searching and creating contacts and leads.
- Ensure the storage of conversation history and additional details (name, phone number, email, service, preferred method of communication).
- Conduct thorough testing and debugging of all features.

### 4. Deployment and Handover to the Client
- Test the assistant using various scenarios.
- Launch the system for client team testing.
- Fix any identified issues and optimize processes.
- Provide ongoing technical support and updates as per additional agreements.

## Timeline, Cost, and Conditions

- **Timeline:** 21 calendar days (preliminary estimate).
- **Cost:** 300 euros (preliminary estimate).
- **Conditions:** The final cost will be determined after agreeing on a detailed TS. The work can be contracted on a self-employed basis.

## How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ai-assistant-vr-arena.git
