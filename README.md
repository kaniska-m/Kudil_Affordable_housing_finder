# KUDIL - Sustainable Affordable Housing Finder

KUDIL is a web application designed to help Indian families find affordable and sustainable housing solutions. The platform aligns with UN Sustainable Development Goals (SDGs) to promote sustainable cities and communities while reducing inequalities.

## Features

- 🏠 Smart property search with sustainability filters
- 🌱 Focus on eco-friendly and sustainable housing
- 💰 Integration with government housing schemes
- 🤝 NGO support and community features
- 📱 Responsive and modern UI design
- 🔒 Secure user authentication system

## Technology Stack

- Frontend: HTML5, CSS3, JavaScript
- Backend: Python (Flask)
- Database: SQLite
- Authentication: Flask-Login
- Styling: Custom CSS with animations
- Icons: Custom SVG icons

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/kudil.git
cd kudil
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

5. Initialize the database:
```bash
flask db init
flask db migrate
flask db upgrade
```

6. Run the application:
```bash
flask run
```

Visit `http://localhost:5000` in your browser.

## Project Structure

```
kudil/
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── .env.example       # Environment variables template
├── assets/
│   └── icons/         # SVG icons
├── static/
│   ├── css/          # Stylesheets
│   └── js/           # JavaScript files
├── templates/
│   ├── auth/         # Authentication templates
│   ├── buyer/        # Buyer interface
│   └── seller/       # Seller interface
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- UN Sustainable Development Goals
- Indian Government Housing Initiatives
- Open Source Community