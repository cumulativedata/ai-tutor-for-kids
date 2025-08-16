# Kids Learning Chat Assistant

An interactive, AI-powered learning assistant designed specifically for children. This web-based application provides engaging educational support across multiple subjects including Math, English, Science, and History.

## What is this app?

This is a smart tutoring app that helps kids learn by having conversations with an AI tutor. Think of it like having a patient, knowledgeable teacher available 24/7 who can help with homework, explain difficult concepts, and make learning fun!

## Why This Approach is Better

Unlike other AI tutoring services, our app offers several key advantages:

- **High Privacy**: Your conversations stay completely on your computer - nothing is stored on external servers
- **Pay-As-You-Go**: You pay OpenRouter directly for the AI usage - no hidden fees or surprise charges. We are not affiliated with OpenRouter and simply use their service to connect to AI models.
- **No Bait and Switch**: We cannot demand money later by creating a pay wall - you only pay OpenRouter for the AI responses you choose to use
- **Open Source**: The code is freely available for anyone to inspect, modify, and improve

## Key Features

- **Subject-Specific Help**: Get tutoring in Math, English, Science, and History
- **Kid-Friendly Design**: Colorful, engaging interface with age-appropriate responses
- **Privacy Focused**: All your conversations stay on your computer - nothing is sent to the internet (except to the AI)
- **Works on Any Device**: Use it on computers, tablets, and smartphones

## How to Get Started

### 1. Download the App

1. Save the `kids_learning_chat.html` file to your computer:
   - Right-click on the file and select "Save Link As..." or "Download"
   - Save it to a folder you can easily find (like Desktop or Documents)
   - Double-click the file to open it in your browser

### 2. Set Up the AI (One-time setup)

To make the AI work, you'll need a free account from OpenRouter (a service that provides access to smart AI):

1. Visit [OpenRouter.ai](https://openrouter.ai) and create a free account
2. Add some money to your account (starting with just $5 is fine and should last a while)
3. Generate an "API Key" (this is like a special password that lets the app talk to the AI)
4. Copy this key to your clipboard

### 3. Connect the App to the AI

1. Open the `kids_learning_chat.html` file in your browser
2. Click the "⚙️ Settings" button (gear icon) at the top
3. Paste your API key into the "API Key" field
4. Click "Save" - your key is now saved on your computer
5. The app is ready to use!

## Understanding AI Model Selection

The app allows you to choose different AI models based on your needs. These models excel at long-context tasks and are particularly suitable for summarization roles. You can browse all available models at [OpenRouter Models](https://openrouter.ai/models).

### Recommended Models for Summarization:
- **GPT-5 (high)**
- **GPT-5 (medium)**
- **o3**
- **Grok 4**
- **Qwen3 235B 2507(Reasoning)**
- **Gemini 2.5 Pro**
- **Claude 4 Sonnet**
- **Gemini 2.5 Flash(Reasoning)**
- **GPT-4.1**
- **DeepSeek R10528**

### Cost vs. Quality
- **Faster, Cheaper Models**: Good for simple questions and quick answers (like basic math problems)
- **More Advanced Models**: Better for complex explanations and detailed help (like essay writing or advanced science concepts)

### Speed Considerations
- **Fast Models**: Respond in seconds, perfect for quick homework help
- **Advanced Models**: May take 10-30 seconds but provide more detailed explanations

### When to Use Long-Context Models
- **Summarization**: When you need to understand long passages or articles - these models handle long context very well
- **Complex Topics**: For subjects that require understanding lots of background information
- **Research Help**: When working on projects that involve multiple sources

You can change the AI model anytime in the settings to find what works best for your learning needs.

## How to Use

1. **Choose a Subject**: Click on one of the colorful buttons:
   - 🔢 Math
   - 📚 English
   - 🔬 Science
   - 🏛️ History
   - 💭 General Help (for any other questions)

2. **Tell the AI About Yourself**: The AI will ask for your age and grade level to give you personalized help

3. **Start Learning**: Ask questions like:
   - "Can you explain fractions?"
   - "Help me with my essay about George Washington"
   - "What's photosynthesis?"
   - "I need help with my math homework"

4. **See Your Progress**: The app shows how many questions you've asked and keeps a history of your conversations

## Privacy and Safety

- **Your Data Stays Local**: All conversations are saved only on your computer
- **No Internet Required**: Except for AI responses, everything works offline
- **No Personal Information Collected**: The app doesn't collect or send your personal data anywhere
- **Parental Control**: Parents can monitor usage and control the API spending

## Supported Browsers

Works best on:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## Troubleshooting

**If the AI isn't responding:**
- Make sure you entered your API key correctly
- Check that your OpenRouter account has money in it
- Refresh the page and try again

**If the app seems slow:**
- Some AI models take longer to respond. Summarization gets triggered occassionally and takes upto 30 seconds to complete.
- Try switching to a different AI model in the settings

## For Developers and Advanced Users

This is a single HTML file application that can be easily modified. Feel free to customize it for your needs.

## License

This project is open source and available under the MIT License.

## Support

For support, please open an issue on the GitHub repository or contact the maintainer.
