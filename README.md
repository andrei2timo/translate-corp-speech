# Speech Translation Assistant

This Python script demonstrates how to use Azure Speech and Translation services in combination with OpenAI for speech recognition, translation, and generation.

## Prerequisites

Before running this script, you'll need the following:

- Azure subscription with access to Speech and Translation services.
- OpenAI API Key.
- Python environment with required packages (see `requirements.txt`).

## Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/speech-translation-assistant.git

2. **Set up environment variables**

   Create a .env file in the same directory as the script and add the following:
   ```bash
    speach_key=YOUR_AZURE_SPEECH_KEY
    region=YOUR_AZURE_REGION
    translation_key=YOUR_AZURE_TRANSLATION_KEY
    translation_endpoint=YOUR_AZURE_TRANSLATION_ENDPOINT
    OPENAI_API_BASE=https://api.openai.com
    OPENAI_API_VERSION=v1
    OPENAI_API_KEY=YOUR_OPENAI_API_KEY

3. **Install required packages**

   ```bash
   pip install -r requirements.txt

## Usage

1. Run the script
   python speech_translation_assistant.py
   The script will prompt you to start speaking. It will recognize your speech, translate it, convert it to a corporate tone using OpenAI, and then speak the translated text.

## Contributing

If you'd like to contribute, please fork the repository and create a new branch. Submit a pull request with your changes.

## License
  This project is licensed under the MIT License.
  ```css
  
Please make sure to replace placeholders like `YOUR_AZURE_SPEECH_KEY` with actual values and ensure that you have a `requirements.txt` file listing all the necessary packages. If you have a specific license you prefer, replace the link in the License section accordingly.
