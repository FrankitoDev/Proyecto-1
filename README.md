🌤️ Bot de Clima en WhatsApp con Twilio  

Este proyecto obtiene la temperatura, sensación térmica y humedad de Buenos Aires usando la API de OpenWeatherMap y envía los datos por WhatsApp utilizando Twilio.  

🚀 ¿Cómo usar este proyecto en Google Colab?  

Sigue estos pasos para ejecutar el código correctamente en Google Colab:  

1️⃣ Clonar el repositorio en Google Colab  

Abre Google Colab y ejecuta lo siguiente en una celda:  


git clone https://github.com/FrankitoDev/Proyecto-1.git
cd Proyecto-1


2️⃣ Crear el archivo .env con tus credenciales  

En Google Colab, abre una nueva celda y ejecuta:  

with open(".env", "w") as f:
    f.write("TWILIO_ACCOUNT_SID=TU_ACCOUNT_SID\n")
    f.write("TWILIO_AUTH_TOKEN=TU_AUTH_TOKEN\n")
    f.write("TWILIO_WHATSAPP=whatsapp:+14155238886\n")  
    f.write("TU_NUMERO=whatsapp:+549XXXXXXXXX\n")  
    f.write("WEATHER_API_KEY=TU_API_KEY_DE_OPENWEATHER\n")


🔹 IMPORTANTE: Reemplaza "TU_ACCOUNT_SID", "TU_AUTH_TOKEN", "TU_NUMERO" y "TU_API_KEY_DE_OPENWEATHER" con tus credenciales reales.  

3️⃣ Ejecutar el código  

Ejecuta las celdas del notebook en orden. Cuando el script termine de correr, recibirás un mensaje en WhatsApp con la información del clima.  

---

📌 Requisitos  

- Cuenta en Twilio con el servicio de WhatsApp habilitado.  
- API Key de OpenWeatherMap.  
- Google Colab para ejecutar el código sin necesidad de instalar nada en tu PC.
