# Smart Car Dealership Workflow 🚗

This workflow automates the process of handling car purchase requests:
- **Webhook Trigger** → receives data from Postman or a website.
- **Google Sheets** → stores purchase details (buyer, car, price).
- **Gmail** → sends notification to the dealership owner.

## Files
- `workflow.json` → n8n export (can be imported directly).
- `screenshot.png` → visual representation of the workflow.

# 🏨 Hotel Reservation Workflow (n8n + Airtable)

This project is an **automation workflow built with n8n** for handling simple hotel room reservations.

## ✨ Features
- A **form trigger** in n8n collects reservation details:
  - Guest name
  - Room type (Single, Deluxe, Suite)
- Stores the reservation data automatically in **Airtable** for easy management.

## 🛠️ Tech Stack
- **n8n** – workflow automation
- **Airtable** – database for storing reservations

## 🚀 How It Works
1. A guest fills in the form (Name + Room type).
2. The workflow triggers automatically in n8n.
3. Reservation details are recorded in Airtable.

## 📂 Files
- `hotel-reservation-workflow.json` → Exported n8n workflow (can be imported directly into n8n).

## 💡 Use Cases
- Small hotels or hostels that want to automate booking intake.
- Demo projects for learning n8n + Airtable integrations.
- Building automation portfolio projects.
