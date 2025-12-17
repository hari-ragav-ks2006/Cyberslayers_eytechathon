BuyBot AI: Agentic AI E-Commerce & Sales Bot
Introduction: Team Cyberslayers
Hello, we are Team Cyberslayers, a group of passionate developers and innovators participating in the hackathon to redefine the boundaries of e-commerce through Agentic AI. Our team combines expertise across Full Stack Development, AI/ML, and Data Analysis to build BuyBot AI, a cohesive and intelligent shopping system. Our members are:

Jeffryn Adaikalaraj - AI/ML Engineer

Hari Ragav K.S - Full Stack Developer

Ajay Tilak V - Back End Engineer

Kesav P - Data Analyst

Project Overview
BuyBot AI is a next-generation Agentic AI Sales & Support System designed to automate and personalize the entire e-commerce journey. Unlike traditional chatbots that rely on static scripts, BuyBot AI utilizes a network of specialized "Worker Agents" managed by a central "Sales Agent." This architecture allows the system to handle complex, multi-step user requests—from product discovery to payment and delivery—autonomously and intelligently. The solution is deployed across multiple channels, including a responsive web frontend, Telegram, and WhatsApp, ensuring customers can interact with the business wherever they are.

The Agentic Architecture
At the heart of BuyBot AI lies a sophisticated multi-agent framework. The primary interface is the Sales Agent, which acts as the manager. It handles the multi-channel conversation flow, manages session continuity, and intelligently switches context based on user intent. When a specific task is required, the Sales Agent routes the request to one of the specialized Worker Agents:

Recommendation Agent: This agent analyzes customer profiles, browsing history, and seasonal trends to suggest personalized products, bundles, and promotions, increasing conversion rates.

Inventory Agent: It checks real-time stock levels across warehouses and stores, offering flexible fulfillment options like "ship to home" or "click & collect."

Payment Agent: A secure module that processes payments via saved cards, UPI, or gift cards, automatically handling payment failures and retries for a smooth checkout experience.

Fulfillment Agent: This agent takes over after payment, scheduling delivery slots or reserving in-store pickups and notifying logistics providers.

Loyalty and Offers Agent: To boost retention, this agent applies loyalty points and personalized coupons, calculating final pricing and displaying savings to the user.

Post-Purchase Support Agent: Finally, this agent manages the lifecycle after the sale, handling returns, exchanges, and shipment tracking while soliciting feedback to improve the system.

Frontend & User Interface
The frontend of BuyBot AI was built using v0, utilizing generative UI to create a modern, responsive, and intuitive shopping experience. By leveraging v0's AI capabilities, we rapidly prototyped and deployed a clean interface that seamlessly connects with our backend agents. The design prioritizes accessibility and speed, ensuring that users can view product recommendations, track orders, and manage their profiles without friction. The frontend code is modular, making it easy to scale and integrate new features as our agentic network grows.

Multi-Channel Integration (Telegram & WhatsApp)
To maximize accessibility, we extended BuyBot AI beyond the web. Using Botpress, we deployed our Sales Agent to popular messaging platforms: Telegram and WhatsApp. This allows users to chat with our store just as they would with a friend. The bot maintains context across these channels, so a user can start a purchase on WhatsApp and check its status later on Telegram. The integration handles rich media, sending product images and payment links directly within the chat interface, providing a truly "headless" e-commerce experience.

Tools & Technologies Used
BuyBot AI leverages a cutting-edge stack to bring this agentic vision to life:

v0: For rapid, AI-powered frontend generation.

Gemini: The LLM powering the reasoning and natural language understanding of our agents.

Botpress: For orchestrating the conversational flows and integrating with Telegram/WhatsApp.

Kaggle: Used for sourcing datasets to train and refine our recommendation algorithms
