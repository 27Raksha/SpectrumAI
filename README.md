# SpectrumGenAI
SpectrumGenAI is a versatile and multi-input content summarization tool designed to handle various media formats, including text, images, audio, and video. Leveraging advanced APIs and machine learning models, SpectrumGenAI provides concise and contextual summaries. For text-to-text summarization, it utilizes the Binge API along with Google Gemini Pro to generate coherent summaries, while also offering hyperlinks sourced from relevant articles for deeper context. The tool supports two modes for image inputs and incorporates a comprehensive preprocessing pipeline to ensure accurate image summaries. For video content, SpectrumGenAI employs the YouTube Transcribe API and Beautiful Soup to extract and transcribe text, which is then processed using Gemini Pro with prompt engineering techniques. Additionally, a dedicated pipeline integrates computer vision models, specifically Gemini Pro and Gemini Pro Vision, to generate detailed video summaries based on user input prompts. Enhancing accessibility, SpectrumGenAI also provides audio summaries.

To implement these features, the text-to-text summarization is powered by the Binge API and Google Gemini Pro, with hyperlinks generated from relevant articles. For article and video inputs, transcription extraction is achieved using the YouTube Transcribe API and Beautiful Soup, followed by further summarization through Gemini Pro. The video summarization pipeline combines computer vision with Gemini Pro and Gemini Pro Vision to deliver comprehensive summaries. Users can submit text inputs through the Binge API to receive summarized versions with contextual hyperlinks, process images through the preprocessing pipeline for accurate summaries, and utilize the YouTube Transcribe API and Beautiful Soup to extract and transcribe video content for further summarization by Gemini Pro. Audio summaries are also available to enhance accessibility for users.

To get started, clone the repository and install the necessary dependencies. Configure your API keys for Binge, Google Gemini Pro, and YouTube Transcribe API in the configuration file, and run the application.
