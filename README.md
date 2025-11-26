# Netflix Clone

A Netflix India landing page clone built with HTML and CSS. This project replicates the visual design of Netflix's homepage with responsive layouts, video backgrounds, and interactive elements.

## Features

- Netflix-style landing page design
- Video backgrounds and animations
- FAQ section
- Responsive navigation bar
- Sign-up form mockup
- Footer with links

## Prerequisites

Before you begin, ensure you have the following installed:

- **Git** - Version control system to clone the repository
- **Web Browser** - Any modern browser (Chrome, Firefox, Edge, Safari)

### Installing Git

#### On Windows

1. Download Git from [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Run the installer and follow the installation wizard
3. Verify installation by opening Command Prompt or PowerShell and running:
   ```
   git --version
   ```

#### On Linux

**Ubuntu/Debian:**
```bash
sudo apt update
sudo apt install git
```

**Fedora:**
```bash
sudo dnf install git
```

**Arch Linux:**
```bash
sudo pacman -S git
```

Verify installation:
```bash
git --version
```

## Cloning the Repository

### On Windows

1. Open **Command Prompt** or **PowerShell**
2. Navigate to the directory where you want to clone the project:
   ```
   cd C:\path\to\your\projects
   ```
3. Clone the repository:
   ```
   git clone https://github.com/ogkrn/NETFLIX.git
   ```
4. Navigate into the project folder:
   ```
   cd NETFLIX
   ```

### On Linux

1. Open a **Terminal**
2. Navigate to the directory where you want to clone the project:
   ```bash
   cd /path/to/your/projects
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/ogkrn/NETFLIX.git
   ```
4. Navigate into the project folder:
   ```bash
   cd NETFLIX
   ```

## Running the Project

This is a static HTML/CSS project, so no build process is required. Simply open the HTML file in your web browser.

### Method 1: Direct File Open

#### On Windows
- Navigate to the `new 39-netflix` folder
- Double-click on `netflix.html` to open it in your default browser

#### On Linux
- Navigate to the `new 39-netflix` folder
- Double-click on `netflix.html`, or run:
  ```bash
  xdg-open "new 39-netflix/netflix.html"
  ```

### Method 2: Using a Local Server (Optional)

For a better development experience, you can use a local server.

#### Using Python (Pre-installed on most Linux systems)

**Python 3:**
```bash
cd "new 39-netflix"
python3 -m http.server 8000
```

**Python 2:**
```bash
cd "new 39-netflix"
python -m SimpleHTTPServer 8000
```

Then open `http://localhost:8000/netflix.html` in your browser.

#### Using VS Code Live Server Extension

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Install the "Live Server" extension
3. Open the project folder in VS Code
4. Right-click on `netflix.html` and select "Open with Live Server"

## Project Structure

```
NETFLIX/
├── README.md
└── new 39-netflix/
    ├── netflix.html          # Main HTML file
    ├── netflix.css           # Stylesheet
    ├── favicon.ico           # Browser favicon
    ├── NetflixSans-Regular.otf  # Custom font
    ├── images/               # Image assets
    │   ├── background.jpg
    │   ├── logo.svg
    │   ├── tv.jpg
    │   └── ...
    └── videos/               # Video assets
        ├── menu.mp4
        └── pajji.m4v
```

## Technologies Used

- HTML5
- CSS3
- Google Fonts (Martel Sans, Poppins)

## License

This project is for educational purposes only. Netflix and its logo are trademarks of Netflix, Inc.
