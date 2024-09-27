Here is an example of a Markdown help guide for a system where users can create companies and configure them to connect to accounting and banking systems:

---

# System Help Guide: Company Creation and Configuration

Welcome to the **Company Creation and Configuration System**. This guide will walk you through the steps to create a company in the system, connect it to an accounting platform, and configure banking integration.

---

## Table of Contents

1. [Creating a New Company](#creating-a-new-company)
2. [Configuring Accounting System Integration](#configuring-accounting-system-integration)
3. [Configuring Banking System Integration](#configuring-banking-system-integration)
4. [Troubleshooting & FAQs](#troubleshooting--faqs) 
5. [Configuring the Company](#configuring--the--company)
6. [Contact Support](#contact-support)

---

## 1. Creating a New Company

To create a new company, follow these steps:

1. **Login** to your account using your credentials.
2. Navigate to the **All Companies** section in the main dashboard.
3. Click the **+** button.
4. Fill in the following company details:
    - **Company Name (Name)**: Enter the legal name of the company.
    - **Company Registration Number (RegId)**: Enter the official registration number provided by your country's business authority.
    - **Address**: Provide the company’s headquarters address.
    - **Country**: Enter the company's country.
    - **ISAT**: Enter the company's ISAT code.
5. Click **Save** to create the company in the system.

Once created, the company will appear in your **Companies List**, and you can begin the configuration process.

---

## 2. Configuring Accounting System Integration

To connect your company to an accounting system (e.g., QuickBooks, Xero):

1. Go to the **All Companies** section and select the company you want to configure.
2. Click on **Company name** in then top left corner.
3. Click on **Connections** 
4. Click on **New connection** in the Accounting System section. 
5. Choose the accounting platform you want to integrate with:
    - **Uniconta**
    - **DK**
    - **Other** (Follow the instructions for custom integration)
6. Provide the required API keys or login credentials for the chosen accounting platform.
7. Provide the **Company ID** the accounting system.
    - **Uniconta** Your company ID is listed in the top left hand corner of your Uniconta client. It is the number in brackets.
    - **DK** Please visit Auðkenningar tákn and create new access token
    - **Other** (Follow the instructions for custom integration)
8. Don't choose **App**
9. Click **Save** to create the connection in the system.

The system will now regularly sync accounting data between the two systems based on the preferences you’ve selected.

---

## 3. Configuring Banking System Integration

To link your company's bank accounts for transactions and reporting:

1. Click on **Company name** in then top left corner.
2. Click on **Connections**
3. Click on **New connection** in the Banking System section:
    - **Arion banki**
    - **Íslandsbanki**
    - **Landsbankinn**
    - **Other** (for custom bank configurations)
5. Enter the following information:
    - **Bank** Choose the bank
    - **Bank's username**
    - **Bank's password**
    - **Claim Identifier** Only required if KLAR is going to create claims.
    - **Claim Bank** Only required if KLAR is going to create claims.
    - **Access** Choose the access you are going to give
5. Click **Save** to initiate the connection.

After the connection is created, the banking connection can be tested by using the **Validate** button.

---

## 4. Configuring the Company

1. Click on **Company name** in then top left corner.
2. Click on **Company profile**
3. Click on **Preferences* tab:
    - **Collection partner** Choose the collection partner for the company.
    - **Automatic payments** If banking connection has been created and default banking account chosen then Automatic payments can be enabled. 
    - **Auto create claims** If the collection partner "Inkasso" has been chosen then claims will be created through "Inkasso" from monitoring open invoices in the accounting system. 
    - **Auto import claims** if accounting connection has been created, claim payments will be imported into journal in the Accounting system
    - **Other** (for custom bank configurations)
4. Click **Save** to initiate the connection.

After the company's profile has been updated the changes will take affect next day.

---

## 4. Troubleshooting & FAQs

### Common Issues:
- **Unable to connect to the accounting system**:
    - Ensure API keys are entered correctly.
    - Check if your accounting software supports third-party integrations.
    - Try reauthorizing the connection through the accounting system's admin panel.

- **Bank connection failed**:
    - Double-check bank account credentials.
    - Verify if your bank supports API integrations with the system.
    - Contact your bank's technical support if the connection fails repeatedly.

For more detailed troubleshooting steps, visit our [FAQ page](#).

---

## 5. Contact Support

If you encounter any issues during the configuration process, please feel free to contact our support team:

- **Email**: support@klarbanking.com
- **Phone**: +354-821-0885

---

We hope this guide helps you successfully create and configure companies within the system. For additional questions, refer to our [documentation](#) or reach out to support.

---

