🛡️ ScamShield AI

Paste a suspicious message (or upload a screenshot) and ScamShield AI, powered by Google's Gemma model,
explains the warning signs in plain language and suggests safe next steps.


Features


Paste text or upload a screenshot of a message

Verdict (scam / suspicious / likely safe) with a confidence score

List of warning signs, each with a plain-language reason

Safe verification steps


Run it locally


Install Python 3.10+ and the requirements:
pip install -r requirements.txt

Get a free API key from Google AI Studio.

Set the key (Command Prompt: set GEMINI_API_KEY=your-key, PowerShell: $env:GEMINI_API_KEY="your-key"), or paste it into the app's sidebar.

Start the app:
streamlit run scamshield_app.py


Deploy

Deploy for free on Streamlit Community Cloud and add your key under
Settings → Secrets as:


GEMINI_API_KEY = "your-key"

Never commit your API key to this repository.


Disclaimer

ScamShield AI is an aid and can make mistakes. When in doubt, contact the organisation through its
official website or phone number.


License

MIT - see LICENSE.

