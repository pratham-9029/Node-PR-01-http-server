# Node.js HTTP Server

A lightweight Node.js HTTP server that serves static HTML pages with routing capabilities. This project demonstrates a simple approach to handling HTTP requests and serving static content.

## >> Live Preview

- [http-server](https://node-pr-01-http-server.vercel.app/)

## 🚀 Features

- **Static File Serving**: Serves HTML, CSS, and other static assets
- **Route Handling**: Supports multiple routes including home, feature, and pricing pages
- **404 Error Handling**: Displays a custom 404 page for invalid routes
- **Responsive Design**: Mobile-friendly UI built with Tailwind CSS

## 🛠️ Tech Stack

- **Backend**: Node.js with native `http` module
- **Frontend**: HTML, CSS with Tailwind CSS
- **Build Tool**: Vite for development
- **Package Manager**: npm

## 📁 Project Structure

```
├── index.js          # Main server file
├── index.html        # Home page
├── feature.html      # Features page
├── 404.html          # Error page
├── main.css          # Stylesheet
├── package.json      # Dependencies and scripts
└── README.md         # Documentation
```

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

## 🔧 Installation

Clone or download this repository:
   ```bash
   git clone https://github.com/pratham-9029/Node-PR-01-http-server.git
   cd Node-PR-01-http-server
   ```

## 🚀 Running the Application

To start the development server:

```bash
npm run dev
```

The server will start on `http://localhost:8080`. You can access the following routes:

- `/` - Home page (redirects to index.html)
- `/home` - Home page
- `/feature` - Features page
- `/pricing` - Pricing page
- Any other route - Shows 404 page

## ⚙️ Configuration

The server runs on port `8080` by default. To change the port:

1. Open `index.js`
2. Modify the `PORT` variable:
   ```javascript
   const PORT = 8080; // Change this to your desired port
   ```

## 🏗️ How It Works

The server uses Node.js's built-in `http` module to create an HTTP server. It handles requests by:

1. Checking the requested URL
2. Mapping the URL to the corresponding HTML file
3. Reading the file from the filesystem
4. Sending the file content as the response

## 📄 Routes

| Route | File Served |
|-------|-------------|
| `/home` | `index.html` |
| `/feature` | `feature.html` |
| `/pricing` | `pricing.html` |
| Any other route | `404.html` |

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the ISC License.

## 🆘 Support

If you encounter any issues or have questions, feel free to open an issue in the repository.
