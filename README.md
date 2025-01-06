# WebScrapper - Firecrawl 🚀

A modern, powerful web scraping application built with Next.js and Firecrawl. This application allows you to scrape individual URLs or crawl entire websites, converting the content into clean markdown format with a beautiful, responsive UI.

## 🌐 Web Proxy Service

For reliable web scraping, especially when dealing with rate limits or IP blocks, we recommend using [Toolip.io Premium Proxies](https://toolip.io/?ref=themetaverseguy).

### Features of Toolip.io:
- 🚀 High-performance proxy servers
- 🌍 Multiple global locations
- ⚡ Ultra-fast response times
- 🔒 Secure and anonymous
- 🎯 Perfect for web scraping projects
- 💪 Reliable uptime
- 🔄 Automatic rotation
- 🛡️ Advanced IP protection

### Why Use Toolip.io?
- Bypass rate limiting
- Avoid IP blocks
- Access geo-restricted content
- Enhance scraping reliability
- Improve success rates
- Scale your scraping operations

[Get Started with Toolip.io](https://toolip.io/?ref=themetaverseguy)

---

![WebScrapper Preview](preview.png)

## ✨ Features

- 🌐 Single URL scraping with instant results
- 🕷️ Full website crawling with configurable depth
- 📝 Clean markdown output
- 🎨 Modern, responsive UI with dark mode
- ⚡ Real-time status updates
- 🔄 Automatic polling for crawl status
- 💅 Beautiful glassmorphism design
- ♿ Fully accessible components

## 🛠️ Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** TailwindCSS
- **Icons:** Lucide Icons
- **API:** Firecrawl
- **Animations:** TailwindCSS Animate
- **Deployment:** Vercel (recommended)

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js 18.x or higher
- npm or yarn package manager
- Git

## 🚀 Quick Start

### 1. Clone the Repository

```bash
# Clone the repository
git clone https://github.com/yourusername/webscrapper-firecrawl.git

# Navigate to the project directory
cd webscrapper-firecrawl
```

### 2. Install Dependencies

```bash
# Using npm
npm install

# Using yarn
yarn install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_FIRECRAWL_API_KEY=your_firecrawl_api_key
```

Replace `your_firecrawl_api_key` with your actual Firecrawl API key. You can get one at [Firecrawl's website](https://firecrawl.dev).

### 4. Start the Development Server

```bash
# Using npm
npm run dev

# Using yarn
yarn dev
```

The application will be available at `http://localhost:3000`.

## 🎯 Usage

1. **Single URL Scraping:**
   - Enter the target URL in the input field
   - Click "Scrape URL"
   - View the results in markdown and HTML format

2. **Website Crawling:**
   - Enter the website's URL
   - Click "Crawl Website"
   - Monitor the progress in real-time
   - View all scraped pages in the results

## 🏗️ Project Structure

```
webscrapper-firecrawl/
├── src/
│   ├── app/
│   │   ├── layout.tsx    # Root layout component
│   │   ├── page.tsx      # Main application page
│   │   └── globals.css   # Global styles
│   └── components/       # Reusable components
├── public/              # Static assets
├── tailwind.config.ts   # TailwindCSS configuration
├── next.config.js       # Next.js configuration
└── package.json         # Project dependencies
```

## 🔧 Configuration Options

### Firecrawl Options

You can modify the scraping and crawling options in `src/app/page.tsx`:

```typescript
// Scraping options
const scrapeOptions = {
  formats: ['markdown', 'html']
};

// Crawling options
const crawlOptions = {
  limit: 100,
  scrapeOptions: { formats: ['markdown', 'html'] }
};
```

### Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `NEXT_PUBLIC_FIRECRAWL_API_KEY` | Your Firecrawl API key | Yes |

## 🚀 Deployment

### Deploy to Vercel

The easiest way to deploy your Next.js app is to use [Vercel](https://vercel.com).

1. Push your code to GitHub
2. Import your repository to Vercel
3. Add your environment variables
4. Deploy!

### Other Deployment Options

You can also deploy to other platforms like:
- Netlify
- AWS Amplify
- Digital Ocean
- Self-hosted

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Firecrawl](https://firecrawl.dev) for the amazing API
- [Next.js](https://nextjs.org) for the awesome framework
- [TailwindCSS](https://tailwindcss.com) for the styling utilities
- [Lucide](https://lucide.dev) for the beautiful icons

## 📧 Support

For support, email your-email@example.com or open an issue in the GitHub repository.

---

Made with ❤️ by [Your Name] 