# Stock Profit & Loss Tracker
**Developer:** P.J. Sidhu 
**Course:** Mobile Application Development

### 1. Project Description
The "Stock P&L Tracker" is a financial utility app designed to help individual investors monitor the performance of their specific positions. Unlike general news apps, this focuses specifically on the user’s personal entry points to provide real-time profit and loss (P&L) data.

### 2. Problem Addressing
Most stock apps focus on market news or general price movements. Investors often have to manually calculate their gains/losses across different brokerage accounts. This app solves the "What is my actual return?" problem by centralizing all positions in one mobile dashboard.

### 3. Platform
* **Primary Platform:** Android
* **Minimum SDK:** API 16 (Jelly Bean) to ensure compatibility with nearly 100% of Android devices.

### 4. Front/Back End Support
* **Front End:** Android XML layouts using RecyclerView for the stock list and CardView for a modern UI.
* **Back End:** SQLite database to store ticker symbols and buy prices locally on the device.
* **API Integration:** (Optional/Future) Integration with a financial API to pull current market prices.

### 5. Functionality
* **Add Position:** A form to enter a Ticker Symbol, Shares Owned, and Buy Price.
* **Real-Time Calculation:** Automated logic to calculate total gains or losses.
* **Portfolio Overview:** A dashboard showing total portfolio value.
* **Delete/Edit:** Ability to update or remove positions.

### 6. Design (Wireframes)
* **Activity 1 (Main):** A scrollable list showing Ticker, Current Price, and P&L %.
* **Activity 2 (Add Stock):** A clean input form with text fields and a "Save" button.
* **Activity 3 (Detail View):** A deeper look at a single stock with color-coded profit/loss backgrounds.
