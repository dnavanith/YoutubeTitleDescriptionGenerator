🎬 YouTube Title & Description Generator (GenAI, Streamlit + Hugging Face)
Generate catchy YouTube video titles and SEO-optimized descriptions in seconds using Generative AI!
Built with Streamlit and the Hugging Face Inference API (Mistral-7B-Instruct-v0.3).

🚀 Features
AI-powered title & description generation
Enter a video script or summary, select a tone, and get engaging, SEO-friendly metadata.

No local model downloads required
Uses Hugging Face’s cloud API for fast, reliable results.

User-friendly web interface
Built with Streamlit for easy interaction and instant output.

Download results
Save generated metadata as a .txt file for quick upload to YouTube.

Robust error handling
Handles API errors and edge cases gracefully.

⚡ Quick Start
1. Clone this repo
(Or download as ZIP and extract)

2. Install dependencies

Open your terminal or command prompt in the project folder.

Run:

text
pip install -r requirements.txt
Or, install manually:

text
pip install streamlit requests
3. Add your Hugging Face API token

Create a file at .streamlit/secrets.toml in your project root:

text
HF_TOKEN = "your_hugging_face_token_here"
Get your token from Hugging Face
(Enable “Inference API” and “Inference Providers” permissions.)

4. Run the app

In your terminal, run:

text
streamlit run app.py
📝 Usage
Paste your video script or summary.

Select the desired tone (Professional, Casual, Funny, Inspirational).

Enter SEO keywords (comma-separated).

Click Generate Metadata.

Copy or download your AI-generated title and description!

🧑‍💻 Tech Stack
Frontend/UI: Streamlit

AI Model: Mistral-7B-Instruct-v0.3 via Hugging Face Inference API

Language: Python 3.8+

🧪 Testing
Tested with a variety of video topics, tones, and keywords.

Handles both short and long scripts.

Robust to missing or ambiguous input.

Average response time: 3–8 seconds.

🌱 Future Work
Support for Instagram/TikTok captions

AI-generated thumbnail suggestions

SEO analytics integration

Real-time collaboration

Accessibility features (voice input, screen reader support)

📸 Screenshots
![App Home](https://github.com/user-attachments/assets/74693a28-fe5c-408d-ae2a-b5c512652e](https://github.com/user-attachments/assets/b330c484-90a6-4ae1-a9fc-d19e6a](https://github.com/user-attachments/assets/c3e589f6-934b-4d2d-9583-e2102a2622cc
