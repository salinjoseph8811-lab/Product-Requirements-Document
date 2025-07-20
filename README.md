## Product Requirements Document (PRD) Overview: Account Summary View

The goal of this PRD is to provide 8x8 customers with a comprehensive and actionable account summary view that consolidates invoice data, payment history, and credit adjustments into a single, intuitive interface within the Gaviti external dashboard. This summary page is designed to enhance billing transparency, self-service capabilities, and customer satisfaction by enabling users to quickly assess their financial standing and take key actions.

### Key Capabilities:

* **Displaying total account balance** with drill-down access to open, past due, and closed invoices.
* **Highlighting account status** (e.g., Active, CC Suspended, Suspended) to give immediate visibility into billing risk or restrictions.
* **Enabling one-time payments** via credit card based on currency and payment method eligibility.
* **Providing a dispute option** directly from the summary view.
* **Linking to knowledge articles** to support self-resolution and reduce support ticket volume.

### Integration and Data Flow:

This account summary experience is tightly integrated with 8x8’s Billing Manager and Gaviti platforms. All invoice and customer data will be provided in the agreed format already shared with Gaviti, and updates (e.g., invoice status changes post-payment) will be reflected with a known data sync lag (up to 24 hours). Additional validations and payment eligibility rules will be enforced based on customer billing configuration (e.g., currency type, primary payment method).

### Business Impact:

This functionality not only empowers customers to manage their financial relationship with 8x8 more efficiently but also supports internal goals around collections automation, payment accuracy, and customer experience optimization.
