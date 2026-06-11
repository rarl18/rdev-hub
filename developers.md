# 👨‍💻 Developers

Information for anyone wanting to set up, run, or contribute to these projects.

## 🛠️ Requirements

- **Python 3.10+**
- **Git**
- (Optional) **Linux** environment recommended for the gaming lab tools

## 📦 Getting Started

Clone a project repository:

```bash
git clone https://github.com/rarl18/binance-ai-bot.git
cd binance-ai-bot
```

Create a virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## ⚙️ Configuration

Most projects use a `.env` file for API keys and secrets. Example:

```bash
BINANCE_API_KEY=your_api_key_here
BINANCE_API_SECRET=your_api_secret_here
```

> 🔒 Never commit your `.env` file or API keys to a public repository.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to your fork and open a Pull Request

## 🧱 Project Structure (example)

```
binance-ai-bot/
├── src/
│   ├── strategies/
│   ├── indicators/
│   └── bot.py
├── requirements.txt
├── .env.example
└── README.md
```

## 🐛 Reporting Issues

Open an issue with:

- A clear description of the bug or feature request
- Steps to reproduce (for bugs)
- Your environment (OS, Python version, etc.)
