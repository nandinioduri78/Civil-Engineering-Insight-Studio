# Civil-Engineering-Insight-Studio

A Streamlit application that uses Google's Gemini AI to analyze civil engineering structures from images.

## 🌐 Live Demo

🔗 Demo Video: [https://drive.google.com/file/d/1yXiaPI3NcRrDJxg5Y-NFgKvLUIxFRx40/view?usp=sharing](https://drive.google.com/file/d/1CvoY4tUqxvjuFWgRchyF8DZicNLf71v8/view)

## Features

- **Upload Image**: Upload an image of a civil engineering structure (bridge, building, dam, etc.).
- **AI Analysis**: Uses Google's Gemini-1.5-Flash (or compatible) model to provide a detailed breakdown including:
    - Type of structure
    - Materials used
    - Estimated dimensions
    - Construction method
    - Notable features
    - Engineering challenges
- **Interactive UI**: Clean and modern user interface built with Steamlit.

## Setup

### 1. Clone the repository
```bash
git clone https://github.com/Tagore2702/Civil-Engineering-Insight-Studio.git
cd Civil-Engineering-Insight-Studio
```

### 2. Create a Virtual Environment (Recommended)
It's best practice to use a virtual environment to manage dependencies.

**Windows:**
```bash
python -m venv venv
.\venv\Scripts\activate
```

**macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables
1. Create a `.env` file in the root directory.
2. Add your Google Gemini API key:
   ```env
   GOOGLE_API_KEY=your_api_key_here
   ```
   *(You can get an API key from [Google AI Studio](https://aistudio.google.com/))*

### 5. Run the Application
```bash
streamlit run app.py
```

## Technologies Used

- Python
- Streamlit
- Google Generative AI (Gemini)
- Pillow (PIL)
- Python-dotenv

## License

MIT

