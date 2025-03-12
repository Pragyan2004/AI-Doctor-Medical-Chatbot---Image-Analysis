![Screenshot 2025-03-12 213135](https://github.com/user-attachments/assets/e0dc308a-1c7b-46f4-91f8-3f0e6c3fef51)# AI-Doctor-Medical-Chatbot-Image-Analysis

An AI-powered medical chatbot that allows users to upload medical images and receive AI-generated insights based on their queries. The application integrates FastAPI for backend processing, Tailwind CSS for a modern UI, and Groq's Llama-3.2 Vision API for AI-based image analysis.

# Features
Upload an image for medical analysis.
Ask a medical-related question about the uploaded image.
Select from multiple AI models for analysis.
Receive AI-generated responses in a user-friendly format.

# Tech Stack
  Frontend:
HTML, Tailwind CSS – Responsive UI design.
JavaScript – Client-side logic and API handling.
Marked.js – Converts AI responses to markdown format for better readability.
  Backend:
FastAPI – A high-performance Python web framework.
Pillow – For image processing and verification.
Requests – To interact with Groq's API.
Base64 Encoding – To send images in a format compatible with the AI models.
Logging – For error tracking and debugging.
  AI Models Integrated:
Llama-3.2-11b-Vision (Smaller, faster model)
Llama-3.2-90b-Vision (Larger, more powerful model)
Hosting & Environment:
Uvicorn – ASGI server for running FastAPI.
dotenv – Securely loads API keys from .env file.

# Run the Application:
    python app.py

# Usage Guide
1️⃣ Upload a medical image.

2️⃣ Type your medical question related to the image.

3️⃣ Select an AI model (Llama-3.2-11b-Vision or Llama-3.2-90b-Vision).

4️⃣ Click "Submit" to get AI-generated insights.

# ScreenShot:-

![Screenshot 2025-03-12 213135](https://github.com/user-attachments/assets/4e444233-3048-4a5a-bf1c-3250ee59dc68)


![Screenshot 2025-03-12 213314](https://github.com/user-attachments/assets/13956f2c-fabf-4b85-9444-a4a85cf346e1)


