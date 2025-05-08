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
- **Dashboards:**
  - **Admin Dashboard:** Add/manage voters and candidates, close elections, and view results.
  - **Voter Dashboard:** Check voting status and cast vote if eligible.

---

## 🛠️ Tech Stack

**Frontend:**
- Next.js
- Tailwind CSS 

**Backend:**
- Node.js
- Express.js
- MongoDB 
- JSON Web Tokens (JWT) for authentication

**Security:**
- AES encryption for secure vote storage
- Role-based route protection
- Only validated users can access voting system

---

