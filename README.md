<h1>Currency Converter – Lightning Web Component (LWC)</h1>

A simple and interactive **Currency Converter application built using Salesforce Lightning Web Components (LWC).**
The app allows users to convert one currency to another in real-time using an external **Exchange Rate API**.

This project demonstrates **LWC component architecture, API integration, event handling, and SLDS styling.**

**🚀 Features**

* Convert currency between different countries

* Real-time exchange rate using API

* Clean UI built with Salesforce Lightning Design System (SLDS)

* Dynamic dropdown selection

* Error handling for API failures

* Responsive card-based layout

* Custom styling using CSS variables
----------------------------------------

**🛠️ Technologies Used**

* Salesforce Lightning Web Components (LWC)

* JavaScript (ES6)

* HTML

* CSS

* Salesforce Static Resources

* ExchangeRate API

* SLDS (Salesforce Lightning Design System)

------------------------------
**⚙️ How It Works**

1. User enters an **amount**.

2. Selects **From Currency** and **To Currency** from dropdown lists.

3. Clicks the **Convert** button.

4. The component calls the **ExchangeRate API**.

5. The API returns the **conversion rate**.

6. The app calculates and displays the **converted currency value.**

--------------------------------------------------
**🔌 API Used**

This project uses the **ExchangeRate API** to fetch real-time currency conversion rates.

Example API Endpoint:

https://v6.exchangerate-api.com/v6/YOUR_API_KEY/pair/USD/AUD

-----------------------------------------------
**🧠 Key LWC Concepts Used**
**Event Handling**

The handleChange() method updates component state when users select currencies or enter an amount.

**Form Submission**

The submitHandler() method prevents default form submission and triggers the currency conversion.

**Async API Call**

The convert() method fetches exchange rate data using fetch().

API returns the **conversion rate**, which is used to calculate the converted amount.

---------------------------------------
