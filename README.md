# Search Scraper

A powerful Python-based search and data visualization tool that combines Wikipedia content and Google Images search results into a comprehensive analysis package.

## Features

- **Wikipedia Content Scraping**
  - Extracts article titles, summaries, and full content
  - Captures infobox data for key information
  - Performs text analysis on article content

- **Google Images Integration**
  - Searches and downloads relevant images
  - Displays images in an organized grid layout
  - Supports up to 8 images per search

- **Data Visualization**
  - Word frequency analysis charts
  - Text composition visualization
  - Data sources overview
  - Text statistics breakdown

- **Text Analysis**
  - Word frequency counting
  - Stop word filtering
  - Sentence count analysis
  - Unique word identification

## Requirements

- Python 3.x
- Chrome browser installed
- ChromeDriver (compatible with your Chrome version)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/search-scraper.git
cd search-scraper
```

2. Install the required packages:
```bash
pip install selenium>=4.0.0 requests>=2.26.0 matplotlib>=3.4.0 seaborn>=0.11.0 pandas>=1.3.0 Pillow>=8.3.0 numpy>=1.21.0 ipython>=7.0.0 jupyter>=1.0.0
```

3. Download ChromeDriver:
   - Visit [ChromeDriver downloads](https://sites.google.com/chromium.org/driver/)
   - Download the version matching your Chrome browser
   - Add the ChromeDriver to your system PATH

## Usage

The tool can be used in two ways:

1. **Jupyter Notebook Interface**
```python
from search_scraper import NotebookSearchScraper

# Initialize the scraper
scraper = NotebookSearchScraper(headless=True)

# Perform a search
results = scraper.comprehensive_search("your search query")
```

2. **Quick Search Function**
```python
from search_scraper import search_and_display

# Perform a search with visualization
search_and_display("your search query")
```

## Example Output

The tool provides:
- Wikipedia article summary and key information
- Relevant images from Google
- Text analysis statistics
- Multiple data visualizations including:
  - Word frequency charts
  - Text composition pie charts
  - Data sources overview
  - Text statistics bar charts

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This tool is for educational purposes only. Please respect the terms of service of Wikipedia and Google when using this scraper. Ensure you comply with their robots.txt and usage policies. 