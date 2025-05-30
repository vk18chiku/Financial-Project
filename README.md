# 📊 Automated Email-to-Dashboard Financial Project

## 🔧 Project Summary

This project automates the ingestion, processing, and visualization of daily survey data received via Outlook email. By integrating Power Automate, Google Drive, a custom API, Python, and Power BI, the solution eliminates manual steps, reduces costs, and delivers real-time business insights to stakeholders.

---

## 🛠️ Technologies Used

- **Microsoft Outlook**: Receives daily emails with attachments from survey teams.
- **Power Automate (Microsoft Flow)**: Automatically extracts attachments from emails and saves them to Google Drive.
- **Google Drive**: Serves as the central repository for incoming data files.
- **Custom API**: Provides an interface to serve data files from Google Drive to Python.
- **Python**: Processes API data—combining, cleaning, and preparing it for Power BI.
- **Power BI**: Visualizes the data, providing dashboards and analytics for decision-making.

---

## 🔁 Automated Workflow

| Step | Tool | Description |
|------|------|-------------|
| 1 | Outlook + Power Automate | Automatically downloads and extracts attachments from incoming emails at 3 PM. |
| 2 | Power Automate → Google Drive | Uploads all attachments to a central Google Drive folder. |
| 3 | API | Exposes the files on Google Drive to Python through an HTTP endpoint. |
| 4 | Python | Combines and cleans the files, calculates business metrics, and outputs a clean dataset. |
| 5 | Power BI | Uses the cleaned dataset to generate dynamic visualizations and dashboards. |

---

## 📈 Delivered Insights

The Power BI dashboard provides automated analytics on:

- Key financial metrics such as income, balance, payment delays, and credit utilization.
- Age demographics, credit behavior, and risk patterns.
- Customer segmentation based on inquiries and credit behavior.
- Promotional eligibility based on Life-Time Value (LTV) calculations.
- Ownership trends of loans and credit products across age groups.
- Loan product popularity based on historical data.

---

## ⏱ Automation Timeline

| Time | Task |
|------|------|
| 3:00 PM | Emails received from survey teams across locations |
| 3:01 PM | Power Automate extracts and uploads files to Google Drive |
| 3:05 PM | Python script pulls data via API, cleans and transforms |
| 3:15 PM | Power BI automatically refreshes dashboard |
| By 8:00 PM | Insights and visuals are ready for delivery to stakeholders |

---

## 📬 Contact

**Uttam Kumar Mahato**  
📧 uttammahato379@gmail.com  
🔧 Automation & Analytics Developer

---



