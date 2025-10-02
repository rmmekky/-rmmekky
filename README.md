SafePost

SafePost is a Streamlit-based web app that analyzes user-generated text and images to check whether the content is safe to post or inappropriate.
It uses AI models for text classification and image captioning, and stores results in a simple CSV-based database.

🚀 Features

📝 Text classification → Detects safe vs. inappropriate content.

🖼️ Image captioning → Generates detailed captions for uploaded images.

💾 CSV database → Stores all inputs, classifications, and timestamps.

📊 Data visualization → Provides insights into safe vs. unsafe posts.

🌐 Streamlit UI → Simple and interactive web interface.

.

📂 Project Structure
├── app.py              # Main Streamlit app  
├── text_classifier.py  # Text classification module  
├── imagecaption.py     # Image captioning module  
├── database.py         # CSV database management  
├── data.csv            # Saved inputs and results  
└── README.md           # Project documentation 

