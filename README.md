Kalai: AI-Powered Artisan Marketplace Assistant
Project Overview
Kalai is a prototype web application designed to empower local artisans by providing them with an AI-driven marketing and sales toolkit. The platform aims to bridge the gap between traditional craftsmanship and the digital marketplace by automating key tasks that often challenge artisans, such as creating compelling content and professional product images.

This prototype showcases a full-stack, serverless architecture built on Google Cloud Platform, simulating how a live application would function.

Key Features
AI-Powered Content Generation: Uses Gemini to transform simple product descriptions into rich, authentic narratives, SEO-friendly titles, and engaging social media copy.

Visual Enhancement: Utilizes Imagen to generate professional, high-quality product images from a simple photo upload. This helps artisans present their work beautifully without the need for expensive photography.

Multilingual Support: The prototype simulates using the Cloud Speech-to-Text API to transcribe and translate spoken descriptions in multiple official Indian languages, including Gujarati, Marathi, and Tamil.

Real-time Data Storage: Connects to Firestore to provide a real-time database for storing and managing an artisan's product catalog.

Proactive Insights (Simulated): Demonstrates how a central ADK AI Agent would use data to provide proactive insights and notifications to artisans about potential customer interest and social media promotion.

Technology Stack
The solution is built on a modern, scalable, and serverless architecture powered by Google Cloud:

Front-end: HTML, CSS (Tailwind CSS), JavaScript

Generative AI: Google's Gemini and Imagen models via Vertex AI

Core Services:

Cloud Run: For deploying the scalable, containerized application.

Firestore: The real-time NoSQL database for operational data.

Cloud Storage: For handling image file uploads.

APIs (Simulated)::

Cloud Speech-to-Text: For multilingual voice-to-text functionality.

Google Location APIs: For geotagging and location-based insights.

ADK AI Agent: The core intelligence layer for proactive actions.

How to Run the Prototype
This prototype is a single, self-contained index.html file. You can run it locally or deploy it to a static site hosting service.

Save the file: Save the code as index.html.

Open in a browser: Open the file directly in any modern web browser to interact with the prototype.

Explore the features:

Enter product details and click "Generate Content" to see the AI in action.

Click the microphone icon to simulate a multilingual voice input.

Upload an image file to see the image-handling functionality.

Note: For live functionality, a real-world implementation would require connecting to the actual Google Cloud APIs and configuring API keys, authentication, and a back-end service on Cloud Run.
