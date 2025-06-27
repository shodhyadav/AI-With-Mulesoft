# 🎫 AI Ticket Assistant (MuleSoft + AI Integration)

An intelligent MuleSoft-based ticketing assistant that automates ticket intake, AI-based triage, routing, and notifications — designed for IT service management and support operations.

---

## 🚀 Features

- ✅ Accepts tickets via API, Email, or Scheduler
- 🧠 Uses AI (Azure/OpenAI) to:
  - Classify intent
  - Determine priority
  - Auto-generate summary/responses
- 🗃️ Stores data in a database
- 📤 Sends email notifications to users & teams
- 📁 Supports batch processing via SFTP or queues (JMS/VM)
- 🧪 MUnit test coverage with SonarQube analysis

---

## 🛠️ Tech Stack

| Component     | Technology                     |
|---------------|---------------------------------|
| API Layer     | MuleSoft HTTP Listener          |
| AI Analysis   | Azure AI / OpenAI (Text models) |
| Storage       | Mule DB Connector (JDBC)        |
| Queues        | JMS / VM Queue                  |
| Logging       | Mule Object Store + JSON Logger |
| Notifications | Email Connector                 |
| Testing       | MUnit, Maven, SonarQube         |

---

