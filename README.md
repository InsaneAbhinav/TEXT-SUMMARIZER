# 📄 Text & Document Summarizer

A powerful web application built using **Streamlit** that performs **text summarization**, **sentiment analysis**, **keyword extraction**, and **text comparison**. It supports multiple document formats such as PDF, DOCX, PPTX, and images for OCR-based extraction and summarization.

## 🚀 Features

- **Summarize Text**: Quickly summarize large chunks of text, with options to set the summary length and highlight differences between the original and summarized content.
- **Summarize Documents**: Upload and summarize text from PDFs, DOCX files, PowerPoint presentations, and images using OCR.
- **Sentiment Analysis**: Analyze the sentiment of summarized text, with results scaled from 1 to 10.
- **Keyword Extraction**: Automatically extract key terms from the text to capture important themes.
- **Text Comparison**: Highlight the differences between the original text and the summarized version for easy comparison.

## 🛠️ Technologies Used

- **Streamlit**: A Python framework for building interactive web apps.
- **SpaCy**: A robust NLP library used for keyword extraction.
- **txtai**: For generating text summaries.
- **Tesseract OCR**: To extract text from image files (JPG/PNG).
- **Transformers (HuggingFace)**: Sentiment analysis using pre-trained BERT models.
- **PyPDF2, python-docx, python-pptx**: To extract text from PDFs, DOCX, and PPTX formats.

## 🎨 Custom Styling

The project incorporates a custom-designed user interface using CSS, enhancing the aesthetic experience:
- Soft, light background colors for better readability.
- Bold and bright elements for buttons and headers to draw user attention.
- Smooth transitions and hover effects for an interactive feel.

Here's a sample of the custom styling from `style.css`:

```css
h1 {
    color: #1df30d;
    text-align: center;
    font-size: 3rem;
    font-weight: bold;
}

button {
    background-color: #ff4500;
    color: black;
    padding: 12px 24px;
    border-radius: 8px;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #ff6347;
}
```

## 📂 Folder Structure

- **app.py**: The main application file where all functionalities (text extraction, summarization, sentiment analysis, etc.) are implemented.
- **style.css**: Custom CSS file for styling the web interface.
- **logo_processed.png**: Logo image displayed in the sidebar.
- **README.md**: This file providing details about the project and its usage.

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/text-document-summarizer.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   streamlit run app.py
   ```

4. Open your browser and navigate to `http://localhost:8501` to start using the summarizer.

## 📊 Usage

1. **Summarize Text**:
   - Input text directly into the text area for summarization.
   - Adjust summary length using the slider.
   - Optionally enable keyword extraction and sentiment analysis.

2. **Summarize Document**:
   - Upload a document (PDF, DOCX, PPTX, image) for text extraction and summarization.
   - View the extracted text, keywords, and summarized content.

3. **Download Summary**:
   - After summarization, download the summary in `.txt` format with a single click.

## 🧪 Example

### Input Text:
```
Artificial Intelligence is transforming industries by providing intelligent solutions to complex problems...
```

### Summary:
```
AI is transforming industries by offering solutions to complex problems...
```

### Sentiment Analysis:
- Sentiment: Positive
- Score: 8.6/10

## 🖼️ Screenshots
![image](https://github.com/user-attachments/assets/27f6b226-8e05-4673-a89f-fce53e603a67)
![image](https://github.com/user-attachments/assets/addb8402-09d9-4888-8736-9c1e9008598d)
---
