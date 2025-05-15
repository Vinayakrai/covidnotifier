# covidnotifier

**covidnotifier** is a Python-based desktop application that provides real-time updates on COVID-19 cases in India. It fetches the latest data from a reliable source and displays it as a desktop notification, ensuring users stay informed without needing to open a browser or application.

## 🦠 Features

- **Real-Time Updates**: Fetches the latest COVID-19 statistics for India.
- **Desktop Notifications**: Displays the information as a system notification.
- **Lightweight**: Minimal resource usage with no GUI.

## 🛠️ Prerequisites

- **Python 3.x**
- **Required Libraries**:
  - `urllib.request`
  - `bs4` (BeautifulSoup)
  - `win10toast`

*Note*: Ensure you have the required libraries installed. You can install them using pip:

```bash
pip install beautifulsoup4 win10toast
```

## 📦 Installation

1. **Clone the Repository**:

```bash
git clone https://github.com/Vinayakrai/covidnotifier.git
cd covidnotifier
```

2. **Run the Application**:

```bash
python covidnotifier.py
```

Upon execution, a desktop notification will appear displaying the current COVID-19 cases in India.

## 📁 Project Structure

```
covidnotifier/
├── covidnotifier.py   # Main script
├── covid.ico          # Icon used for the notification
└── README.md          # Project documentation
```

## 📝 Notes

- The application fetches data from a specific website. Ensure that the source website's structure hasn't changed; otherwise, the scraping logic may need adjustments.
- The `covid.ico` file is used to display an icon in the notification. Ensure this file is present in the same directory as the script.


