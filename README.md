# PolyglotSum: Multilingual Audio Summarizer

## Project Overview
PolyglotSum is a project designed to transcribe multilingual audio files using OpenAI Whisper and summarize them using Google's large language model (LLM).

## Detailed Breakdown

### 1. Audio Processing and Language Detection
- **Load and Preprocess Audio:** Load an audio file and prepare it for analysis with OpenAI Whisper.
- **Create Mel Spectrogram:** Construct a mel spectrogram from the audio to visualize the frequency spectrum.
- **Language Detection:** Use Whisper to analyze the mel spectrogram and determine the language spoken in the audio.

### 2. Transcription with OpenAI Whisper
- **Transcribe Audio to Text:** Utilize OpenAI Whisper to transcribe audio into text, ensuring accurate and multilingual voice recognition.

### 3. Integration with Google LLM
- **Set up Google API:** Interface with Google Generative AI using an API key for authentication.
- **Initialize LLM:** Configure a large language model from Google (e.g., "gemini-pro") to process the transcribed text.

### 4. Text Splitting and Summarization
- **Split Text into Chunks:** Divide the transcribed text into manageable chunks for efficient processing.
- **Summarize Text:** Utilize Google LLM to summarize each segment of text, then concatenate the summaries to form a comprehensive final summary.

## Conclusion
PolyglotSum demonstrates robust capabilities in multilingual speech recognition and text summarization. By leveraging powerful models and APIs like OpenAI Whisper and Google LLM, it ensures accurate transcription, language identification, and concise summarization of transcribed information.
