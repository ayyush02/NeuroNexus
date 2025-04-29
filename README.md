# NeuroNexus
NeuroNexus Innovations is a beacon of technological advancement in the realm of IT  services and Artificial Intelligence. Founded by a group of ambitious pre-final year  students, our company is a testament to the power of youthful energy and innovative  thinking.

# Contact Form

A simple Google Form-like contact form built with HTML and CSS.

## Features

- Responsive design
- Form validation
- Modern UI with hover effects
- Clean and minimalistic design
- Animated background
- Glass-morphic design elements

## Local Development

### Prerequisites
- Python 3.x (for local server)
- Web browser

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/ayyush02/NeuroNexus.git
   cd NeuroNexus
   ```

2. Start the local server:
   ```bash
   # Using Python's built-in HTTP server
   python3 -m http.server 8000
   ```

3. Open your web browser and visit:
   ```
   http://localhost:8000
   ```

4. To stop the server:
   - Press `Ctrl+C` in the terminal

### Alternative Server Options

You can also use other local servers:

1. Using Node.js (if installed):
   ```bash
   npx http-server
   ```

2. Using PHP (if installed):
   ```bash
   php -S localhost:8000
   ```

## Deployment

This project is configured for deployment on Vercel. To deploy:

1. Create a Vercel account at [vercel.com](https://vercel.com)
2. Install Vercel CLI (optional):
   ```bash
   npm i -g vercel
   ```
3. Deploy using one of these methods:
   - Drag and drop the project folder to Vercel's dashboard
   - Use Vercel CLI:
     ```bash
     vercel
     ```
   - Connect your GitHub repository to Vercel

## Project Structure

- `index.html` - Main HTML file
- `styles.css` - CSS styles
- `vercel.json` - Vercel configuration

## Note
The form is currently static (HTML/CSS only). Form submissions will not be processed without additional backend implementation.
