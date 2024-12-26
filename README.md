# Life Event Extraction Project

## Overview

The **Life Event Extraction** project is designed to analyze and categorize life events from textual data, such as social media posts or personal narratives. By leveraging natural language processing (NLP) techniques, this project can identify significant life events and provide insights into the emotional context surrounding them.

## Features

- **Event Classification**: Automatically classify text into predefined life event categories such as Weddings, Graduations, Anniversaries, and more.
  
- **Keyword Matching**: Utilize a comprehensive list of keywords associated with each life event to enhance the accuracy of classification.

- **TF-IDF Analysis**: Implement Term Frequency-Inverse Document Frequency (TF-IDF) to evaluate the importance of words in the context of life events.

- **Data Preprocessing**: Clean and preprocess input data to ensure high-quality analysis, including tokenization and stemming.

## Getting Started

### Prerequisites

To run this project, you will need:

- Python 3.x
- NLTK library for natural language processing
- Jupyter Notebook for executing the code

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/life-event-extraction.git
   cd life-event-extraction
   ```

2. Install the required libraries:
   ```bash
   pip install nltk
   ```

3. Download necessary NLTK resources:
   ```python
   import nltk
   nltk.download('punkt')
   ```

### Usage

1. Open the Jupyter Notebook file `Life-Event-Extraction-Code.ipynb`.
2. Load your dataset or input text directly into the provided cells.
3. Run the cells sequentially to preprocess the data, classify events, and view results.

## Data Sources

The project utilizes a dataset containing various life events and their associated keywords. The dataset is stored in a text file and is processed within the Jupyter Notebook.

## Example Input

You can input text such as:
```
"I got engaged last week!"
```

## Example Output

The program will classify this input as:
```
Life event: Wedding & Engagement
```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
