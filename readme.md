# 📚 Assignment & Quiz Generator

A Python-based educational tool that automatically generates assignment questions and multiple-choice quizzes from any given text or topic. Built with Streamlit for an intuitive web interface.

![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)
![Streamlit](https://img.shields.io/badge/streamlit-v1.28+-red.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🌟 Features

- **Smart Text Analysis**: Automatically extracts key terms and concepts from input text
- **Dual Input Modes**: 
  - Document text analysis for comprehensive content
  - Topic-only mode for quick question generation
- **Educational Content Generation**:
  - 2 essay assignment prompts with specific instructions
  - 3 multiple-choice quiz questions with explanations
- **Interactive Web Interface**: Clean, user-friendly Streamlit dashboard
- **Export Functionality**: Download generated content as text files
- **Content Statistics**: View analysis metrics and generation details

## 🚀 Quick Start

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. **Clone or download the repository**:
   ```bash
   git clone <repository-url>
   cd assignment-quiz-generator
   ```

2. **Install required dependencies**:
   ```bash
   pip install streamlit
   ```

3. **Run the application**:
   ```bash
   streamlit run quiz_generator.py
   ```

4. **Access the app**: Open your browser and go to `http://localhost:8501`

## 📖 Usage Guide

### Method 1: Document Text Analysis
1. Select "Document Text" in the sidebar
2. Paste your content in the text area (articles, lecture notes, etc.)
3. Optionally specify a topic name for better context
4. Click "🎯 Generate Content"

### Method 2: Topic-Only Generation
1. Select "Topic Only" in the sidebar
2. Enter your topic (e.g., "Machine Learning", "World War II")
3. Click "🎯 Generate Content"

### Viewing Results
- **Assignment Questions**: Essay prompts with writing guidelines
- **Quiz Questions**: Multiple-choice with optional answer reveal
- **Export Options**: Download as text file or view statistics

## 🛠️ How It Works

### Text Analysis Engine
```python
# Key term extraction
def extract_key_terms(self, text: str) -> List[str]:
    # Filters common words, ranks by frequency
    # Returns most relevant terms for question generation
```

### Content Generation Logic
- **Assignments**: Uses key terms and topics to create analytical essay prompts
- **Quiz Questions**: Generates multiple-choice based on extracted concepts
- **Smart Fallbacks**: Provides generic questions when text analysis is limited

### Question Types Generated
1. **Analytical Essays**: Compare, contrast, evaluate key concepts
2. **Concept Recognition**: Identify key terms from the text
3. **Application Questions**: Practical implications and connections
4. **Comprehension Checks**: Main ideas and relationships

## 📁 Project Structure

```
assignment-quiz-generator/
│
├── quiz_generator.py          # Main application file
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies (optional)
```

## 🎯 Example Output

### Sample Assignment Questions:
1. "Write
