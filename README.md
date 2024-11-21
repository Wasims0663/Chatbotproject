# Product Finder Using API

This project provides a simple API to fetch product data from various e-commerce websites such as Amazon, Flipkart, Myntra, Nykaa, and others. The API fetches product details and returns links to the respective products.

## Features

- **Fetch Product Data**: The API can retrieve product information from a variety of online stores.
- **Product Links**: It provides direct links to the products listed on Amazon, Flipkart, Myntra, Nykaa, etc.
- **Easy to Use**: You can integrate this API into your application or website to enhance the product search functionality.

## What This Project Does

This project **does not include product comparison**. Instead, it serves as a tool that fetches product data based on search queries. You can input a product name, and the API will provide you with links to the products from multiple e-commerce platforms.

### Example

When you query for a product (e.g., "laptop"), the API will return links to the listings for laptops from popular websites like:

- [Amazon](https://www.amazon.in)
- [Flipkart](https://www.flipkart.com)
- [Myntra](https://www.myntra.com)
- [Nykaa](https://www.nykaa.com)

## How to Use

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Wasims0663/Product-finder-by-API.git
   cd Product-finder-by-API
Install dependencies:

bash
Copy code
npm install
Set up Google Custom Search API:

Create a project in the Google Cloud Console.
Enable the Google Custom Search API.
Get your GOOGLE_APPLICATION_CREDENTIALS (service account credentials).
Store the credentials file in your project directory and point to it using the .env file.
Run the API:

bash
Copy code
node app.js
Query the API:

Once the server is running, you can make GET requests to:

bash
Copy code
http://localhost:4000/search?q=<product_name>
Replace <product_name> with the product you're searching for. The API will return a list of product links from multiple platforms.

Example Request
bash
Copy code
GET http://localhost:4000/search?q=laptop
The response will include product listings from various e-commerce websites with their respective URLs.

Important Note
Please note that the full code with the API credentials could not be pushed to GitHub due to security reasons. The GOOGLE_APPLICATION_CREDENTIALS file (which contains sensitive API keys) has been excluded from the repository. For security purposes, do not expose your API keys publicly. You can set up your own credentials by following the instructions in the "Set up Google Custom Search API" section.

Requirements
Node.js
Google Cloud Custom Search API Key
.env file for storing sensitive credentials
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Google Custom Search API for product data.
E-commerce websites like Amazon, Flipkart, Myntra, and Nykaa for providing the product information.
Feel free to contribute to this project or use it as part of your application!

vbnet
Copy code

### Changes:
- Added a section **Important Note** stating that the full code with API credentials could not be pushed to GitHub due to security reasons. The sensitive information in the `GOOGLE_APPLICATION_CREDENTIALS` file has been excluded.
- It emphasizes the importance of not exposing API keys publicly and guides users on how to set up their own credentials.

This ensures transparency regarding the missing code while helping others set up the project on the
