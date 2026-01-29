# Bot Info Viewer

A clean, professional **Python CLI tool** that displays Discord bot information with a beautiful terminal UI using **pystyle gradients** and **slow typing effects**.

This tool validates a Discord bot token and fetches bot details **without connecting to the Discord gateway**, making it fast, reliable, and immune to Discord gateway outages or Windows asyncio issues.

---

## Features

* Gradient ASCII banner using **pystyle**
* Smooth slow-typing terminal output
* Bot token validation
* Displays bot username & ID
* Lists all servers the bot is in (name + guild ID)
* Uses Discord **HTTP API only** (no gateway, no hanging)
* Clean project structure & readable code
* Fully compatible with Windows

---

## Project Structure

```text
bot-info-viewer/
│
├── main.py
├── requirements.txt
│
├── core/
│   ├── __init__.py
│   └── discord_client.py
│
├── ui/
│   ├── __init__.py
│   ├── banner.py
│   └── console.py
```

---

## Requirements

* Python **3.9+**
* A Discord **bot token**

### Python dependencies

```txt
pystyle
aiohttp
```

Install them with:

```bash
pip install -r requirements.txt
```

---

## Usage

1. Clone or download this repository
2. Install dependencies
3. Run the script:

```bash
python main.py
```

4. Press **ENTER** when prompted
5. Paste your **Discord bot token**
6. View your bot information 🎉

---

## Output Example

```text
Bot Username : examplebot#1234
Bot ID       : 123456789012345678
Server Count : 3

Servers:
• Server One | ID: 111111111111111111
• Server Two | ID: 222222222222222222
• Server Three | ID: 333333333333333333
```


## 🛠 Possible Enhancements

* Masked token input
* Export results to JSON/TXT
* Animated loading spinner
* Member counts per server
* Executable (.exe) build
* Theme / color switching

---

## 📜 License

This project is provided for **educational and personal use**.
You are responsible for complying with Discord's Terms of Service.

---

Made with ❤️ using Python
