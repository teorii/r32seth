# r32seth Website

A modern, responsive website built with Node.js and Express.js.

## Features

- 🚀 **Fast & Lightweight** - Built with Express.js for optimal performance
- 📱 **Responsive Design** - Modern, mobile-first design that works on all devices
- ⚡ **Real-time API** - RESTful API endpoints for dynamic content
- 🎨 **Beautiful UI** - Clean, modern interface with smooth animations
- 🔧 **Easy to Customize** - Well-structured code for easy modifications

## Technologies Used

- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactive functionality

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone or download this repository
2. Navigate to the project directory:
   ```bash
   cd r32seth-website
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Website

#### Development Mode (with auto-reload)
```bash
npm run dev
```

#### Production Mode
```bash
npm start
```

The website will be available at `http://localhost:3000`

## Project Structure

```
r32seth-website/
├── server.js          # Main server file
├── package.json       # Project dependencies and scripts
├── README.md         # This file
└── public/           # Static files
    ├── index.html    # Homepage
    ├── about.html    # About page
    ├── contact.html  # Contact page
    ├── 404.html      # 404 error page
    ├── styles.css    # Main stylesheet
    └── script.js     # JavaScript functionality
```

## Pages

- **Home** (`/`) - Landing page with hero section and features
- **About** (`/about`) - Information about the website and technologies
- **Contact** (`/contact`) - Contact form and contact information
- **404** - Custom error page for missing routes

## API Endpoints

- `GET /api/status` - Returns server status and timestamp

## Customization

### Styling
- Edit `public/styles.css` to modify the appearance
- The website uses CSS Grid and Flexbox for layout
- Color scheme can be easily changed by modifying CSS variables

### Content
- Update HTML files in the `public/` directory to change content
- Modify `server.js` to add new routes or API endpoints

### Functionality
- Edit `public/script.js` to add new interactive features
- The contact form can be connected to a real backend service

## Deployment

### Local Development
The website runs on port 3000 by default. You can change this by setting the `PORT` environment variable:

```bash
PORT=8080 npm start
```

### Production Deployment
For production deployment, consider:

1. **Environment Variables**: Set `NODE_ENV=production`
2. **Process Manager**: Use PM2 or similar for process management
3. **Reverse Proxy**: Use Nginx or Apache as a reverse proxy
4. **SSL**: Enable HTTPS with Let's Encrypt or similar

Example with PM2:
```bash
npm install -g pm2
pm2 start server.js --name "r32seth-website"
pm2 startup
pm2 save
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Support

If you have any questions or need help, feel free to:
- Open an issue on GitHub
- Contact through the website's contact form
- Check the console for helpful messages

---

Built with ❤️ using Node.js and Express
