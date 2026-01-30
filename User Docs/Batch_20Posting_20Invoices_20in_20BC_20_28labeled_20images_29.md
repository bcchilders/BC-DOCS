# Batch Posting Invoices in BC

## Customer Setup
- Some customer setups may be required if a custom report, report layout, and/or sending profile are needed.
- Document Layout and Document Sending Profile setups are outlined in a separate document.

## Batch Posting Process
- Search **Sales Orders** or navigate to the Sales Orders list page.
- Apply filters: **Shipped not Invoiced**, **Released**, and **Order**.
- **Select All** after the list is filtered to the orders you want to post.
- From the ribbon, choose **Post** → **Post Batch** (***NOT* Post and Send**).
- Fill in the posting dialog as needed. Clear the **No.** in the Sales Order area.
- If there are posting errors, a blue message bar will appear. Click **Details** to view affected orders.
- Use **Open Related Record** to navigate to and fix any problematic orders.
- ![Figure 1] - pic1 ](imsges/Img_pic1 "pic1"

## Printing or Emailing Invoices
- From **Posted Sales Invoices**, apply filters such as:
  - **Unpaid** (if needed)
  - **Do Not Print Invoices = No**
  - **Invoice Printing Hold** = Blank/Weekly/Monthly/Bi-Monthly
  - **Invoicing Type = Manual**
  - **No. Printed = 0**
  - **Posting Date = Today**
- Choose **Send**. This uses the Document Sending Profile on the customer record.
- When multiple invoices are selected, a confirmation message appears.

## Notes on Document Sending Profiles
- Default profiles are commonly set to **Print** or **Email**.
- Default profile is usually **Print**, so customers without a profile will default to printed invoices.
- **Mail Invoice to Ship-to** affects printed hard copies only.
- **Combine** works only when filtering for a single customer.
- Additional profiles (e.g., `EMAIL2`) can be created for special cases.

### Email Address Logic
1. Daily invoice email on **Ship-to** (highest priority)
2. Daily invoice email on **Customer**
3. Email address on the **Sales Order**
4. Customization: system will first check for **Department-level** email before Ship-to


