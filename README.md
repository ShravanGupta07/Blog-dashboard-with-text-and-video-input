# Regional Language Blog Translator

Welcome to the **Regional Language Blog Translator** app! This application allows users to translate blog content into multiple Indian regional languages, manage blogs, track blog analytics (views, likes, shares), and store translated blogs in a permanent directory.

## Features:
- **Multi-language Translation**: Translate blog content into various regional languages such as Hindi, Marathi, Gujarati, Tamil, Kannada, Telugu, Bengali, Malayalam, Punjabi, and Odia.
- **Blog Management**: Create, edit, delete, and view blogs in multiple languages.
- **Analytics Dashboard**: Track blog views, likes, and shares with visual graphs.
- **Translation Accuracy**: Calculate translation accuracy using Levenshtein distance between original and translated text.
- **File Storage**: Save published blogs in a dedicated directory as JSON files.
- **Interactive UI**: Built with Streamlit for easy interaction and real-time updates.

## Technology Stack:
- **Streamlit**: For building the user interface.
- **Google Translate API**: For text translation into various languages.
- **Levenshtein**: To calculate the translation accuracy based on the difference between original and translated text.
- **Matplotlib**: For visualizing blog performance (views, likes, shares).
- **Pandas**: For data handling and analytics.
- **JSON**: For storing blog data in a structured format.

## Installation Instructions:

### Clone the repository:
```bash
git clone https://github.com/yourusername/regional-language-blog-translator.git

## Installation Instructions:

### Create a virtual environment and activate it (optional but recommended).


python -m venv venv

## Usage:

### Homepage:
- Choose the language to which you want to translate your blog.
- Enter text or upload a file to translate.
- Once translated, you can publish the content as a blog and see the translation in real-time.

### Blog Section:
- View all the published blogs with their titles and content.
- Like, share, and track blog performance through the interface.

### Manage Blog:
- Select a blog to manage: edit its content, delete it, or view it.

### Analytics:
- View the performance of each blog based on metrics like views, likes, and shares.
- Visualize these metrics with interactive graphs.

## File Structure:
- **app.py**: Main Streamlit application.
- **requirements.txt**: List of dependencies.
- **published_blogs/**: Directory to store published blog data in JSON format.
- **README.md**: Project documentation.
- **LICENSE**: License file (if applicable).


### Acknowledgements

Special thanks to LevelSuperMind Hackathon for providing the platform and opportunity to showcase this project. 
Your support has been invaluable in bringing this idea to life. 
We appreciate your encouragement and the chance to collaborate with fellow innovators!
