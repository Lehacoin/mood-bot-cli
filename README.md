# mood-bot-cli
A simple command-line mood bot that gives short, kind responses based on how you're feeling
# mood_bot.py

def mood_bot():
    mood = input("How are you feeling today? (happy/sad/tired/angry): ").strip().lower()

    responses = {
        "happy": "That's awesome! Keep spreading those good vibes! 🌞",
        "sad": "Sending virtual hugs your way 💙 Remember: it's okay to not be okay.",
        "tired": "Don't forget to rest. You deserve a break 😴",
        "angry": "Deep breaths. You got this. 💢➡️💆",
    }

    print(responses.get(mood, "Hmm, I’m not sure how to respond to that, but I’m here for you! 🤗"))

if __name__ == "__main__":
    mood_bot()
