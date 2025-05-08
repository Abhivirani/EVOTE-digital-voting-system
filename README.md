# EVOTE - Digital Voting System 🗳️

EVOTE is a secure and efficient digital voting platform designed to support transparent and tamper-proof elections. It enables election authorities to manage voters and candidates, while ensuring that only authorized users can cast encrypted votes.

---

## 🚀 Features

- **Role-based Access:** Election Authority (Admin) and Voter accounts.
- **Authentication System:** JWT-based login and registration.
- **Voter Validation:** Only pre-registered voters added by the authority can access voting features.
- **AES Encryption:** Votes are encrypted using AES to ensure privacy and security.
- **Voting Status:** Voters can view their voting status before casting a vote.
- **Result Visibility:** Election results are only displayed after the election ends.
- **Election Creation with Custom Deadlines:** Admins can set voting periods and close elections automatically after the deadline.
- **Automatic Vote Counting:** Once an election ends, vote tallying and result computation happen instantly.
- **Modern Responsive UI:** Built with Next.js for fast, responsive, and SEO-friendly user experience.
- **Dashboards:**
  - **Admin Dashboard:** Add/manage voters and candidates, close elections, and view results.
  - **Voter Dashboard:** Check voting status and cast vote if eligible.

---

## 🛠️ Tech Stack

**Frontend:**
- Next.js
- Tailwind CSS (optional)

**Backend:**
- Node.js
- Express.js
- MongoDB (via MongoDB Atlas)
- JSON Web Tokens (JWT) for authentication

**Security:**
- AES encryption for secure vote storage
- Role-based route protection
- Only validated users can access voting system

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/evote.git
cd evote
cd backend
npm install
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT = 5000
npm run dev
cd ../frontend
npm install
npm run dev

