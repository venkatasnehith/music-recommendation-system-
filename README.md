# music-recommendation-system-
 🎵 A simple music recommendation system using YouTube API and genre-based search


A simple and interactive music recommendation system for  songs built using **Google Colab** and the **YouTube Data API**. It allows users to search for songs by predefined genres or custom text input.

---

## 🔥 Features

- 🎼 Genre-based song recommendations
- 🔍 Custom keyword-based song search
- 📺 Instant YouTube video links for results
- 🧠 Google YouTube Data API integration

---

## 🧑‍💻 How to Use

1. **Open the notebook in Google Colab**
2. Select a **genre** or enter a **custom search term**
3. Click the **Search** button
4. You will get clickable **YouTube links** to the top relevant videos

---

## 📦 Setup Instructions

### 🔑 1. Add YouTube API Key
Go to [Google Cloud Console](https://console.developers.google.com/)  
Create a project and enable the **YouTube Data API v3**. Then generate an API key.
API--->AIzaSyDGe1UUf-vI9Cvcvv0VGd-L7Ml74cly45Y

Paste it into the notebook:
```python
api_key = "YOUR_YOUTUBE_API_KEY"
````

### 📌 2. Install Required Libraries

Run the following cell in Colab to install required packages:

```python
!pip install --upgrade google-api-python-client
```

---

## 🧪 Tech Stack

* Python (Google Colab)
* YouTube Data API v3
* IPython Widgets & HTML Display

---

## ⚠️ Known Issues

* ❗ Results depend on YouTube's search response and may vary
* 🌐 Requires active internet connection

---
