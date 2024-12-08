
# Krushak-Agri-Chat-Bot

**Krushak-Agri-Chat-Bot** is an intelligent agricultural chatbot designed to assist farmers with a variety of tasks and queries. Powered by **Google Gemini**, the chatbot offers a ChatGPT-like interface with robust multi-language communication, voice interaction, and WhatsApp integration. This ensures a seamless and accessible experience for farmers across different regions and languages. The chatbot is powered by Django on the backend and Bootstrap for a responsive user interface.

---

## Features

- **ChatGPT-like Interface**: A user-friendly and intuitive interface for effortless communication.
- **Google Gemini Integration**: Harnesses the power of Google Gemini for advanced, real-time agricultural assistance.
- **WhatsApp Integration**: Users can interact with the chatbot directly through WhatsApp for added convenience.
- **Multi-language Support**: Supports multiple languages, enabling farmers to converse in their native tongues.
- **Voice Interaction**: Allows users to communicate via voice commands and receive voice responses, improving accessibility for farmers who may have limited literacy skills.
- **Django Framework**: Utilizes Django for the backend, ensuring scalability and robust performance.
- **Responsive Design**: Frontend built using Bootstrap, providing an easy-to-use interface across devices, including smartphones and tablets.

---

## How It Works

1. **User Interaction**: Farmers interact with the chatbot either through the web interface or WhatsApp.
2. **Multi-Language Communication**: The chatbot detects the user's language and provides responses in their preferred language.
3. **Voice Input and Output**: Users can speak their queries, and the chatbot responds via voice, enabling hands-free communication.
4. **Agricultural Assistance**: The chatbot offers real-time information on crop management, weather forecasts, pest control, and other agriculture-related queries.
5. **WhatsApp Support**: Farmers can receive responses directly on WhatsApp, ensuring accessibility without needing a web browser.

---

## Use Cases

- **Crop Management**: Guidance on best practices for growing, watering, and harvesting crops.
- **Pest Control**: Information on pest identification and prevention measures.
- **Weather Forecasts**: Localized weather updates to help farmers plan their activities.
- **Market Prices**: Real-time updates on the prices of agricultural produce.
- **Government Schemes**: Details about government assistance and schemes available for farmers.

---

## Technology Stack

- **Backend**: Django (Python framework)
- **Frontend**: Bootstrap for responsive design
- **AI Integration**: Google Gemini for intelligent and contextual responses
- **Voice Support**: Speech-to-text and text-to-speech functionalities
- **WhatsApp Integration**: Direct messaging support via WhatsApp API

---

## Installation

To set up the chatbot locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/krushak-agri-chat-bot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd krushak-agri-chat-bot
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure API keys for **Google Gemini** and **Twilio (for WhatsApp integration)**.

5. Set up the Django server:

   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

---

## Future Improvements

1. **Integration with IoT Devices**: Connect with smart sensors for real-time field data.
2. **Enhanced AI Models**: Further optimization of Google Gemini for highly specific agricultural advice.
3. **Offline Support**: Developing an offline mode for areas with limited internet access.
4. **Mobile App**: Extend the chatbot’s functionality to a dedicated mobile application.
5. **Data Visualization**: Provide detailed insights and trends for improved farm management.  

---

This chatbot is an advanced tool aimed at revolutionizing agricultural assistance with the latest AI technologies, ensuring farmers have the right tools to maximize productivity and efficiency.
