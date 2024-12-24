# Content Summarization Tool
## Overview
This Content Summarization Tool simplifies the process of extracting valuable insights from text-based documents. By employing advanced techniques like TF-IDF (Term Frequency-Inverse Document Frequency) and sentence ranking, the tool effectively identifies important keywords and creates concise summaries of Word documents. It also features robust preprocessing to ensure accurate results.

## Dataset Description
This project uses a sample dataset collected from Wikipedia, containing information about the Taj Mahal. 

### Dataset Details

Source: Wikipedia (https://en.wikipedia.org/wiki/Taj_Mahal)
Content: 337 words across 24 sentences

## Features
Document Parsing: Reads .docx files to process text content.

Text Preprocessing:
Converts text to lowercase.
Removes punctuation, numbers, and stopwords.

Keyword Extraction: Uses TF-IDF to extract the top keywords and their relevance scores.

Text Summarization: Produces a summary by ranking sentences based on TF-IDF scores.

Configurable Output: Allows customization of the number of sentences in the summary.

## Results
### Input Document Statistics
Original Word Count: 337 words

post-processing Words: 160 words

### Extracted Keywords (Top 10)
Gives the The highest-scoring keywords along with their TF-IDF scores.

Compression Ratio: ~53% compression.
