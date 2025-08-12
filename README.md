
📊 WhatsApp Chats Analyzer


A Python-based tool to analyze and visualize WhatsApp chat data from exported .txt files.
It helps you understand your conversations better by showing statistics, activity trends, and emoji usage.

🚀 Features
📥 Import & Clean Data – Reads WhatsApp chat exports without media.

🧹 Preprocessing – Extracts date, time, sender, and message content.

📊 Statistics & Insights:

Total messages & total words

Most active users

Most used words

Emoji analysis

📅 Time Analysis:

Messages per day

Messages per month

Activity by hour

🎨 Visualizations:

Bar charts, line graphs, and heatmaps

Word clouds of frequently used terms

📁 Project Structure
graphql
Copy
Edit
Whatsapp-Chats-Analyzer/
├── whatsapp_analysis.py        # Main script for analyzing chat data
├── requirements.txt            # Python dependencies
├── sample_chat.txt              # Example WhatsApp exported chat
├── visuals/                     # Saved charts and plots
└── README.md                    # Documentation


⚙ How It Works
Load Chat File – Reads .txt file exported from WhatsApp.

Parse Messages – Extracts date, time, sender, message

Clean Data – Removes system messages & media placeholders.

Generate Insights –

Count messages & words per user

Most common words & emojis

Time-based activity trends

Visualize – Creates graphs & charts for easy interpretation.

📤 Input
.txt file exported from WhatsApp.

📈 Output
Text Summary – message counts, most active users, frequent words.

Charts & Graphs – daily, monthly, and hourly trends.

Emoji Usage – most used emojis and counts.
