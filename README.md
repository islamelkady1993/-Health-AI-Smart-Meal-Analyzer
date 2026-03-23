# -Health-AI-Smart-Meal-Analyzer
🥗 Health AI: Smart Meal Analyzer An automated AI-powered solution that analyzes food images to provide instant nutritional insights, built using n8n, OpenAI (GPT-4o/Vision), and Webhooks.

<img width="954" height="599" alt="Screenshot 2026-03-23 165442" src="https://github.com/user-attachments/assets/9c718c4f-3a71-480d-a5a2-1cb8d33246d2" />

<img width="1233" height="580" alt="Screenshot 2026-03-23 165431" src="https://github.com/user-attachments/assets/035c8a97-c677-4d62-aaaf-3e2c7df175b6" />
<img width="880" height="623" alt="Screenshot 2026-03-23 165202" src="https://github.com/user-attachments/assets/d494faf0-5656-4afe-b56a-5955be80d6e4" />



🚀 Overview
Health AI is a workflow-driven application designed to simplify calorie tracking and nutrition management. Users can upload a photo of their meal, and the system automatically identifies the dish, breaks down its ingredients, and calculates its nutritional value (Calories, Protein, Carbs, and Fats).

Key Features:
Visual Recognition: Uses AI to identify traditional and modern dishes from images.

Nutritional Breakdown: Provides precise estimates for Calories, Macros (Protein, Carbs, Fats).

Detailed Ingredients: Extracts a list of ingredients used in the meal (e.g., Basmati rice, grilled chicken, spices).

Automated Workflow: Powered by n8n for seamless integration between the frontend and the AI agent.

🛠️ Tech Stack
Workflow Automation: n8n

AI Engine: OpenAI Chat Model (Vision Capabilities)

Data Parsing: Structured Output Parser (JSON)

Backend Communication: Webhooks & REST APIs

⚙️ How it Works (Workflow Logic)
Webhook Trigger: Receives the image data from the user interface.

AI Agent: Processes the image using the OpenAI model.

Structured Output: The AI parses the data into a clean format (Calories, Protein, etc.).

Response: Sends back the final nutritional breakdown to the frontend for display.
