# AI Story Generator from Images 

An AI-powered Streamlit web application that generates and narrates creative stories from uploaded images using Google Gemini AI and Text-to-Speech.

🔗 Live App: https://ch-story-generator.streamlit.app/

---

##  Features

-  Upload 1 to 10 images  
-  Choose story style (Comedy, Thriller, Fairy Tale, Sci-Fi, Mystery, Adventure, Morale)  
-  AI generates a complete story using Google Gemini  
-  Text-to-Speech narration using gTTS  
-  Multi-image understanding and storytelling  
-  Fast and simple Streamlit UI  

---

##  Tech Stack

- Python   
- Streamlit   
- Google Gemini AI (google-genai / google-generativeai)  
- Pillow (Image processing)  
- gTTS (Text to Speech)  
- python-dotenv (Environment variables)  

---

##  Project Structure

Story Generator/
│
├── app.py                  # Streamlit UI
├── story_generator.py      # AI story + narration logic
├── .env                    # API key storage
├── requirements.txt        # Dependencies
├── venv/                   # Virtual environment (not pushed to GitHub)

---

##  How It Works

1. User uploads 1–10 images  
2. User selects a story style  
3. Gemini AI analyzes images and generates a connected story  
4. Story is formatted based on style rules  
5. gTTS converts story into audio narration  
6. Streamlit displays story + audio player  

---

##  Installation (Local Setup)

### 1. Clone repository
```bash
git clone https://github.com/chabdullah7/story-generator.git
cd story-generator
