# Amazon Web Scraper Project using Python 🛒

## 📌 About
This project scrapes product details (Title & Price) from Amazon using Python and stores the data 
in a structured CSV file for further analysis.

## 🛠️ Libraries Used
- `requests`       → Fetching the Amazon webpage
- `BeautifulSoup`  → Parsing & extracting HTML data
- `pandas`         → Storing data in DataFrame
- `datetime`       → Timestamping the data

## ▶️ How It Works
1. Sends a request to Amazon product page with headers
2. Extracts product details using BeautifulSoup
3. Stores data into a pandas DataFrame
4. Exports the DataFrame to a CSV file

## 📂 Data Extracted
- Product Title
- Price

## 🔗 Source
[Amazon.in](https://www.amazon.in/T-Shirt-Graphic-Classic-Cotton-Regular/dp/B0F53TYXZ8/ref=sr_1_4?crid=3AKDMU4PVO9ZK&dib=eyJ2IjoiMSJ9.lrYn9RK_je3Bu7Uh4TtEp05kbL94yBz3b4DNhr8CA4SquePg0qT9sGIF1Sq0L18ymWihDd9iTryiJZO90YPxM6sl57j4VcjOjni0J_P1KtrnuXWekhp_P2PVaRTbYNtVaJznKse99a2WQShreTJKAIrd5jnyebaRQNysoFab9M1w3Z1b_6t44fAZo5sJpy45N9CTe_eXVZthMB-HTODEzSo_o84VXlmdNvMe1LfUPkFMn_-atZSxBBYLeAECV4CBz5wK2nOQnmC2A27KVcs7SwsAUjt2FLDBKx-O3nyGRXQ.zQmvUZ5cxhAmHKO9YR_ACtulP9A-av03q6bQ7XD8ME0&dib_tag=se&keywords=FUnny%2Bgot%2Bdata%2Btshirt&qid=1773664464&sprefix=funny%2Bgot%2Bdata%2Btshie%2Caps%2C422&sr=8-4&th=1&psc=1)
