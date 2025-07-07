AI for your app without paid APIs:
Here are some options to consider for integrating AI features into your app without relying on paid APIs:
1. Open-Source Chatbot Platforms:
Botpress: A conversational AI software with a visual interface for building and managing chatbots. It supports both text and voice interactions and offers a built-in NLU engine.
Rasa: A popular open-source framework for building chatbots using a "story" approach for training.
DeepPavlov: A conversational AI framework built on PyTorch, allowing for the development of dialogue systems and complex chatbots.
ChatterBot: A straightforward Python library for creating rule-based chatbots.
BotMan: A PHP framework that simplifies the development of bots for multiple messaging platforms.
Bottender: A JavaScript framework for building conversational user interfaces. 
2. Utilizing Free Tiers & Open-Source Models:
Google AI Studio & Gemini API: Google AI Studio provides free usage in all available regions, and the Gemini API has a free tier for testing, enabling integration of Gemini models.
Hugging Face APIs: Hugging Face offers free APIs providing access to a wide range of open-source models, including pre-trained models for tasks like text classification and generation.
OpenAI GPT-3.5 (Free Tier): OpenAI provides a free tier for GPT-3.5 Turbo, suitable for prototypes and smaller projects.
Google Cloud AI (Free Tier): Google Cloud provides free usage of AI products, including Translation, Speech-to-Text, Natural Language, and Video Intelligence, up to set monthly limits.
IBM Watson API (Free Tier): IBM Watson offers a free tier with limited API calls, useful for prototyping.
Meta LLAMA Models: These open-source models are suitable for research and non-commercial applications.
PaLM 2: While not entirely open-source, PaLM 2 offers free access.
OpenRouter: This platform lists some free AI models. 
3. Self-Hosted AI Models:
MindStudio: Allows connection and use of self-hosted AI models, including OpenAI-compatible models. 
4. Considering Pre-made Tools (some offer free tiers):
Lindy.ai: A platform for creating AI assistants without coding, offering a free plan. It automates workflows.
iAsk Ai: A free AI-powered search engine that provides unlimited responses.
Chatbox AI: A free AI client application and smart assistant that can understand documents, images, and code.
Zapier Chatbots: Allows the building of free AI chatbots without coding, with integrations to many apps.
Smartsupp: Offers a free plan for real-time analytics, though with limited conversations.
Zoho SalesIQ: Provides a free plan for hybrid chatbots, with limitations on chat sessions.
IntelliTicks: A free option for conversational landing pages.
HubSpot: Offers a free chatbot creation tool with a visual editor and ready-to-use templates. 
Important Considerations:
Usage Limits: Free tiers and plans often have usage limits, which may be suitable for development and initial deployment but require consideration for scaling.
Technical Expertise: Open-source solutions and self-hosted models may require more technical expertise for setup and maintenance compared to managed platforms.
Data Privacy: Data privacy policies of any AI service integrated should be considered, especially when handling sensitive information. 
By exploring these options, a suitable AI solution for your app can be found that aligns with your needs without requiring paid APIs for basic usage. Remember to evaluate the features, limitations, and technical requirements of each option before making a decision. 
AI responses may include mistakes. Learn more






17 sites
14 Best Open Source Chatbot Platforms to Use in 2025
What is an open-source chatbot? Open-source chatbots are messaging applications that mimic human conversation. Open-source means the original code for the softw...

favicon
Botpress
Are there any free Ai APIs that I can connect to?
Feb 8, 2025 — Yes, there are some free AI APIs available: * **Google Gemini AI API** Available for free at aistudio.google.com * **OpenRouter** Lists some free models * **Dee...
favicon
Reddit
10+ AI tools you can start using for free in 2025 - Google Cloud
Work with the latest AI models and turn your ideas into apps with free AI tools. Google AI Studio is the fast path for developers, students, and researchers who...

favicon
Google Cloud
Show all
I'm hoping that it will be able to pay for itself and that perhaps I can come up with some funding. but getting the app to work implementation time and I'm going to need some usage plus. some testing scenarios.. The app is built into a chat. and has to have the ability to be able to create multiple personas. Also have the ability to step someone in the chat room through getting an API for open AI for Gemini for all of them. which will eventually make the app even better incorporating them in But for now I need an in-house. which one in the list that you suggested open source. Would you try? which do you think would be the best for that? situation scenario and application. The application is using cluttered and. expire store firepiece for data storage.
Considering the requirements for a chat app built with Flutter and Firebase, several factors should be considered:
Multiple Personas: The ability for in-house AI to interact with users differently is essential.
In-house Functionality: A system that can be controlled and adapted is preferred over reliance on external APIs.
Future Integration: Plans to eventually integrate OpenAI and Gemini are in place.
Firebase Storage: Data storage is already set up in Firebase. 
Based on these needs, Rasa is a strong option among open-source platforms: 
Persona Handling: Rasa's story-based approach allows for different conversation flows and responses, which is suitable for multiple personas.
Open-Source & In-House: Rasa is fully open-source, providing complete control over the system.
Integration Flexibility: Rasa's architecture is designed to be extendable, which makes it easier to integrate with external APIs such as OpenAI and Gemini.
Firebase Integration: Since Firebase is used for data storage, integration between the Flutter app and the Rasa backend will need to be developed. Although Rasa doesn't have a built-in Firebase connector, custom actions can be built to handle Firebase operations, like storing chat history or user profiles. 
Other Options:
Botpress: While it has a visual interface and built-in NLU, Rasa's "story" approach might be more flexible for managing multiple personas with distinct conversation paths.
Tock: Tock is a good option if you want a complete, self-contained open-source platform, but Rasa is more focused on building conversational AI itself.
Firebase Extensions (PaLM): Firebase offers extensions to implement chatbots, including one that uses the PaLM API, which stores data in Firestore. However, this option relies on a proprietary API, so it might not align with the goal of staying fully open-source initially. 
Implementation Recommendations:
Start with Rasa to build the in-house AI with the initial set of personas.
Develop Firebase integration by building custom actions in Rasa to interact with the Firebase database for storing chat data and managing user information.
As the app evolves, leverage Rasa's flexibility to integrate with OpenAI and Gemini, potentially using Rasa's existing connectors or building custom ones. 
By choosing Rasa, you gain a robust open-source platform that allows you to manage multiple personas and have a strong foundation for future integration with external AI APIs, while working with your existing Firebase infrastructure. Consult the Rasa documentation and community resources for detailed implementation guides and support. 

###
---
When implementing Rasa with your Flutter and Firebase setup, consider these points:
Rasa's learning curve: Full use of Rasa's capabilities requires technical knowledge, particularly in Python.
Custom actions for Firebase integration: Custom actions in Rasa are needed to interact with Firebase for storing chat data and managing user information. This enables your in-house AI to read from and write to your Firebase database.
Training data: Rasa is a machine learning framework that relies on training data for learning and improvement. The more diverse and high-quality data provided, the better your chatbot will understand and respond to user queries.
Gradual integration with external APIs: Integrating with OpenAI and Gemini can be valuable. Rasa's architecture is designed for a smooth integration process.
Community support: A large and active developer community is available for troubleshooting and implementation help. 