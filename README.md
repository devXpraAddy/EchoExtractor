# EchoExtractor

EchoExtractor is an e-commerce product scraping site developed using Next.js and Bright Data's webunlocker. It assists users in making informed decisions by notifying them when a product drops in price and helping competitors by alerting them when the product is out of stock. All these features are managed through cron jobs.

## ⚙️ Tech Stack

- **Next.js**
- **Bright Data**
- **Cheerio**
- **Nodemailer**
- **MongoDB**
- **Headless UI**
- **Tailwind CSS**

## 🔋 Features

- **Header with Carousel**: Visually appealing header with a carousel showcasing key features and benefits.
- **Product Scraping**: A search bar allowing users to input Amazon product links for scraping.
- **Scraped Projects**: Displays the details of products scraped so far, offering insights into tracked items.
- **Scraped Product Details**: Showcases the product image, title, pricing, details, and other relevant information scraped from the original website.
- **Track Option**: Modal for users to provide email addresses and opt-in for tracking.
- **Email Notifications**: Sends product alert emails for various scenarios, e.g., back in stock alerts or lowest price notifications.
- **Automated Cron Jobs**: Utilizes cron jobs to automate periodic scraping, ensuring data is up-to-date.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn
- MongoDB

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/devXpraAddy/EchoExtractor.git
    cd EchoExtractor
    ```

2. Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    ```

3. Set up environment variables. Create a `.env` file in the root directory and add the necessary environment variables:

    ```env
    MONGODB_URI=your_mongodb_uri
    EMAIL_USER=your_email_user
    EMAIL_PASS=your_email_pass
    ```

### Running the Application

1. Start the development server:

    ```bash
    npm run dev
    # or
    yarn dev
    ```

2. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application in action.

### Running Cron Jobs

Set up cron jobs to run the scraping tasks periodically. This can be done using a task scheduler like `cron` on Unix-based systems or Task Scheduler on Windows.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new features to add.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📧 Contact

For any inquiries or support, please contact [devXpraAddy](https://github.com/devXpraAddy).
