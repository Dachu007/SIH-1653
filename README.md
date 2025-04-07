# Smart India Hackathon Workshop
# Date:07.04.2025
## Register Number:212224040074
## Name:S.Dharshini
## Problem Title

SIH1648-Online Chatbot based ticketing system

## Problem Description
Background:Visitors to museums often face several significant challenges due to manual ticket booking systems. One prominent issue is the inefficiency and time consumption associated with the process. Long queues are common, especially during peak hours, weekends, or special exhibitions, leading to frustration and impatience among visitors. Besides the wait times, the manual system is prone to errors, such as incorrect ticket issuance, double bookings, or lost records, which can cause further delays and inconvenience. Overall, these challenges associated with manual ticket booking systems significantly detract from the visitor experience, reducing satisfaction and potentially impacting the museum's reputation and visitor numbers. Description: The implementation of a chatbot for ticket booking in a museum addresses several critical needs, enhancing the overall visitor experience and streamlining museum operations. Here are the key reasons for adopting a chatbot ticket booking system: 1. Improved Customer Service 2. Efficient Handling of High Volumes 3. Cost-Effective Solution 4. Data Collection and Analysis 5. Accessibility 6. Reduced Human Error 7. Multilingual Support 8. Enhanced Marketing and Promotion Expected Solution: An efficient and responsive multilingual chatbot based ticketing system that can handle all kinds of bookings from gate entry to shows. Payment gateway should also be integrated to make it fully free from human intervention. It will also provide analytics to aid in more efficient decision making process.

## Problem Creater's Organization
Ministry of Culture

## Idea

We propose SanskritiBot, an AI-powered, multilingual chatbot that simplifies ticket booking and provides instant assistance for cultural sites across India. The chatbot will enable users to book tickets through natural conversations in English, Hindi, and regional languages via platforms like WhatsApp, Telegram, and a web/mobile app. It will also offer real-time information about site timings, events, visitor guidelines, and payment options, making the experience seamless and accessible. With an integrated admin dashboard, secure payments, and user-friendly design, SanskritiBot aims to modernize the way tourists interact with India’s cultural heritage.




## Proposed Solution / Architecture Diagram

The proposed system consists of a multilingual AI chatbot integrated into platforms like WhatsApp, Telegram, a web portal, and a mobile app, allowing users to interact in natural language for booking tickets and accessing site-related information. The chatbot is powered by a conversational AI engine (such as Dialogflow or Rasa), which connects to various backend modules. These include a ticket booking module for managing slots and generating QR-coded digital tickets, a site information module for providing real-time details about cultural sites, and an NLP layer for understanding regional languages. All interactions are processed through a backend server (built with Django or Node.js), which handles user authentication, request processing, and data storage using a secure database. The system also integrates with a payment gateway (like UPI, Razorpay, or Paytm) for seamless transactions. An admin dashboard allows the Ministry to manage bookings, view visitor analytics, and update content, ensuring scalability and ease of deployment across various cultural sites.

![Screenshot 2025-04-07 205217](https://github.com/user-attachments/assets/91552898-a4ae-4a1b-bc98-f6c7a7fa394c)

![Screenshot 2025-04-07 205217](https://github.com/user-attachments/assets/790ad413-73f7-49b6-b1bb-6d92002e286e)




## Use Cases

A visitor looking to explore a cultural monument initiates a conversation with the chatbot through a web interface, mobile app, or messaging platform like WhatsApp. The user simply types a message such as “I want to book a ticket for India Gate.” The chatbot, using natural language processing, understands the request and responds with available options including dates, time slots, and ticket categories (e.g., adult, child, foreigner). The user selects their preferences, and the chatbot prompts for payment through integrated gateways like UPI, Paytm, or credit/debit cards. Once the payment is successfully processed, the chatbot instantly generates a digital ticket with a QR code and shares it with the user in the chat. The entire process is seamless, interactive, and can be completed without needing to download a separate app or visit a physical counter, making it ideal for tourists and culturally curious individuals alike.

![Screenshot 2025-04-07 205351](https://github.com/user-attachments/assets/7a21c341-9582-4201-9e8e-201d88d5bc70)




## Technology Stack

Database:

PostgreSQL or MySQL – For structured data like users, bookings, tickets
MongoDB – For flexible, unstructured data such as chat logs or FAQs
HTTPS for secure communication
JWT for session handling
Input validation and data encryption for privacy and security
React.js or Vue.js (for dynamic dashboard UI)
Charts & Analytics: Chart.js or Recharts for visualizing visitor data, ticket sales, etc.
Cloud Services: AWS / Firebase / Render / Heroku
Chatbot Hosting: Google Cloud (for Dialogflow) or self-hosted on VPS (for Rasa)
CI/CD: GitHub Actions or GitLab CI for smooth deployment pipeline

## Dependencies

