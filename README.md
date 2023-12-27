Certainly! Here's a simplified and concise description of your Next.js web scraper without any external links or mentions:

---

**Next.js Web Scraper for E-commerce Product Tracking**

**Description:**
This Next.js web scraper is designed for tracking e-commerce product details, including price changes and stock availability. Built with Next.js, it leverages Bright Data's webunlocker for efficient data retrieval. The scraper notifies users of price drops and stock updates through automated cron jobs.

**Tech Stack:**
- Next.js
- Bright Data
- Cheerio
- Nodemailer
- MongoDB
- Headless UI
- Tailwind CSS

**Features:**
- Header with Carousel for key feature showcase
- Product scraping with a search bar for Amazon product links
- Display of scraped product details, including images, title, pricing, and descriptions
- User option to track products with email notifications
- Automated cron jobs for periodic scraping
- Tailwind CSS for responsive and stylish UI

**Quick Start:**
1. Clone the repository: `git clone https://github.com/adrianhajdin/pricewise.git`
2. Navigate to the project directory: `cd pricewise`
3. Install dependencies: `npm install`
4. Set up environment variables in the `.env` file.
5. Run the project locally: `npm run dev`

**Code Snippets:**
- `cron.route.ts`: Handles scraping, updating product details, and sending email notifications using cron jobs.
- `generateEmailBody.ts`: Generates email content based on different notification types.
- `index.scraper.ts`: Defines the function to scrape Amazon product details using Bright Data proxy.

**Configuration:**
- Customize extraction rules and configurations in the code as needed.
- Adjust Tailwind CSS styles in the `globals.css` file for UI customization.

**Usage:**
1. Input Amazon product links in the search bar.
2. Track products and receive email notifications for price drops or stock updates.
3. Explore detailed product information on the user interface.

**Note:**
Ensure prerequisites like Git, Node.js, and npm are installed before setting up the project.

**Disclaimer:**
This web scraper is for educational and personal use only. Use responsibly and adhere to ethical scraping practices.

---

