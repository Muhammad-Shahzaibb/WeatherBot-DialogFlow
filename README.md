# WeatherBot Dialogflow Backend

This is a FastAPI-based webhook backend for a Dialogflow ES chatbot that provides current and 8-day weather forecasts using the OpenWeather API.

## Features

- 🌦 Get current weather by city
- 📅 Get 8-day forecast by city and date
- 🔗 Integrated with Dialogflow ES webhook
- ☁️ Powered by OpenWeather API

## How to Run Locally

1. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the server:

    ```bash
    uvicorn main:app --reload
    ```

3. Use `ngrok` to expose the API:

    ```bash
    ngrok http 8000
    ```

## Webhook URL

Use the `https://your-ngrok-url.ngrok-free.app/webhook` as your **Dialogflow Fulfillment URL**.
