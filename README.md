# 🧑‍💻 **Lucy - Your Personal Virtual Assistant**  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)  
![SpeechRecognition](https://img.shields.io/badge/Speech_Recognition-v3.8.1-blue.svg)  
![Pyttsx3](https://img.shields.io/badge/pyttsx3-v2.90-blue.svg)  
![Requests](https://img.shields.io/badge/Requests-v2.28.1-green.svg)  
![No License](https://img.shields.io/badge/license-No_License-red.svg)  

Lucy is a **voice-activated virtual assistant** designed to perform a variety of tasks like fetching the latest news, telling jokes, giving weather updates, and more. This project leverages **[Python](https://www.python.org/)** and several libraries to create an interactive, speech-based assistant.

---

## 🌟 **Features**

- 🗣️ **Voice-activated commands**: Lucy listens for your commands and responds with the appropriate actions.
- 🧑‍🏫 **Fun facts & Motivational quotes**: Get random fun facts and motivational quotes to brighten your day.
- 🎬 **Anime Recommendations**: Receive anime suggestions when you're unsure of what to watch next.
- 📰 **News Updates**: Stay updated with the latest news headlines.
- 🤣 **Jokes**: Need a laugh? Ask Lucy to tell you a joke.
- 🌤️ **Weather Reports**: Get real-time weather updates for any city.
- 🎶 **Music Playback**: Play your favorite songs by specifying the title.

---

## 📥 **Installation**

### 🔧 **Prerequisites**
- [Python 3.8+](https://www.python.org/downloads/)
- Internet connection (for fetching news, weather, and other data)

### 🛠️ **Libraries Required**

Install the required libraries using `pip`:

```bash
pip install SpeechRecognition pyttsx3 requests pyjokes
```

### ⚙️ **Setup**

1. Clone this repository:

   ```bash
   git clone https://github.com/SyedShahulAhmed/Lucy-Virtual-Assistant.git
   cd lucy-virtual-assistant
   ```

2. Replace the placeholder API keys with your own:
   - **News API**: Replace the `news_api` variable with your News API key from [newsapi.org](https://newsapi.org/).
   - **Weather API**: Replace the `api_key` in the weather section with your Weather API key from [weatherapi.com](https://www.weatherapi.com/).

---

## 🏃‍♂️ **Usage**

Run the Python script to start the assistant:

```bash
python lucy.py
```

### 🗣️ **Example Commands**
- **Open websites**: `"Open Google"`, `"Open Github"`, `"Open YouTube"`
- **Get the weather**: `"What's the weather in New York?"`
- **Get news**: `"Give me the latest news"`
- **For fun**: `"Tell me a fun fact"`, `"Motivate me"`, `"Recommend an anime"`, `"Tell me a joke"`

### 💬 **Sample Output**

```text
Listening...
Lucy Activated...
Processing command
--------------------------------
How about watching Steins;Gate?

Listening...
Lucy Activated...
Processing command
--------------------------------
The weather in New York is Clear with a temperature of 25°C.

Listening...
Lucy Activated...
Processing command
--------------------------------
Here’s a motivational quote: "The only way to do great work is to love what you do."

Listening...
Lucy Activated...
Processing command
--------------------------------
Playing music...
Now playing: Skyfall
```

---

## ✨ **Customization**

Feel free to **fork** this repository and make your own modifications!  
You can add new features, integrate different APIs, or enhance the assistant’s capabilities.

---

## 🤝 **Contributing**

This project is still in its early stages, and contributions are welcome!  
- Fork the project
- Make your changes
- Submit a pull request to share your improvements
