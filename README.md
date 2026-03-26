# Mert Bursalıoğlu - Portfolio Website

A modern, glassmorphism-styled personal portfolio website. Built with Flask, featuring responsive design and bilingual support (TR/EN).

## 🚀 Features

- **Glassmorphism Design**: Modern glass effect with transparent cards and blur effects
- **Bilingual Support**: Turkish and English language options
- **Responsive Design**: Perfect display on mobile and desktop devices
- **Smooth Animations**: Smooth transitions and hover effects
- **Dark Theme**: Eye-friendly interface with dark theme

## 📋 Requirements

- Python 3.8+
- Flask 3.1.2+

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd my_website
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
# or
.venv\Scripts\activate  # Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

Optional: if you prefer using npm scripts for a single command workflow:
```bash
npm install
```

## 🎯 Usage

Start the development server:
```bash
python app.py
```

Or with npm:
```bash
npm run dev
```

Open your browser and navigate to `http://localhost:5000`.

## 📁 Project Structure

```
my_website/
├── app.py                 # Flask application file
├── requirements.txt       # Python dependencies
├── templates/
│   └── index.html        # Main HTML template
├── static/
│   ├── css/
│   │   └── style.css    # Stylesheet
│   ├── js/
│   │   └── main.js      # JavaScript file
│   ├── linkedin.png     # LinkedIn icon
│   ├── github.png        # GitHub icon
│   ├── Screenshot 2025-12-15 at 11.12.12.png  # Profile photo
│   └── Mert BURSALIOĞLU ADRESSİZ CV.docx dosyasının kopyası.docx.pdf  # CV file
└── README.md
```

## 🌐 Production Deployment

For production, you can use Gunicorn:

```bash
gunicorn -w 4 -b 0.0.0.0:5000 app:app
```

## 📝 Notes

- Language preference is saved in localStorage
- CV file and profile photo should be in the `static/` folder
- You can update LinkedIn and GitHub links with your own profiles


## 📄 License

This project is for personal use.
