
# Academic Research Assistant

The Academic Research Assistant is a comprehensive tool designed to help researchers, students, and academics streamline the process of summarizing research papers, generating presentations, creating podcasts, and producing videos. This project leverages advanced AI models, including Google's Gemini, to extract, simplify, and present research content in an accessible and engaging manner.




## Features

- __Text Extraction and Summarization:__

    - Extract text from PDFs (including scanned documents using OCR).

    - Summarize research papers using Google's Gemini model.

    - Simplify technical jargon for non-expert audiences.

- __Podcast Generation:__

    - Generate podcast scripts with analogies to explain complex concepts.

    - Convert scripts into audio using Google Text-to-Speech (gTTS).

    - Combine audio with video to create engaging multimedia content.

- __Presentation Generation:__
    - Automatically create PowerPoint presentations from research summaries.

    - Customize presentations with different themes (Formal, Casual, Fun).

    - Export presentations as .pptx files.

- __Video Generation:__

    - Overlay generated audio on video clips to create educational videos.

    - Support for multiple video formats and audio mixing.


## Installation

To use this project, you need to install the required dependencies. You can do this by running the following commands:

```bash
  pip install PyPDF2 pdf2image pytesseract pillow pydub tts gTTs google-generativeai python-pptx moviepy
```
- Additionally, ensure you have the following installed:

    - __Tesseract OCR:__ For text extraction from scanned PDFs.
    - __FFmpeg:__ For video processing.

## Workflow

- __Extract Text:__ Extract text from a research paper PDF.

- __Summarize:__ Generate a summary of the paper using Gemini.

- __Simplify:__ Simplify the summary for non-experts.

- __Podcast:__ Create a podcast script and generate audio.

- __Presentation:__ Generate a PowerPoint presentation from the summary.

- __Video:__ Overlay the podcast audio on a video to create an educational video.
## Customizations

__Themes:__ You can customize the presentation themes by modifying the THEMES dictionary in the code.

__Analogy Generation:__ You can modify the analogy generation prompts to suit your needs.

