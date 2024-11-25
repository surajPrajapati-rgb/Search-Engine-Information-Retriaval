# Web Scraping and Document Similarity Using Cosine Similarity

## Project Overview

This project demonstrates how to:

1. **Scrape Content from a Website**: Extract textual data from a specified website using web scraping techniques.
2. **Calculate Document Similarity**: Compare the similarity between documents using the **Cosine Similarity** metric. This is achieved by vectorizing the documents and calculating the cosine of the angle between their vector representations.

### Key Features:

* **Web Scraping**: Uses the `requests` library to fetch HTML content and `BeautifulSoup` to parse and extract meaningful text from the website.
* **Text Preprocessing**: The text is cleaned by removing stopwords and tokenizing the content before analysis.
* **Cosine Similarity**: Implements the **Cosine Similarity** metric to compute how similar two documents are based on their content.

### Use Cases:

* Scraping articles, blog posts, or other content from websites.
* Comparing textual data to determine how similar different documents are to each other.
