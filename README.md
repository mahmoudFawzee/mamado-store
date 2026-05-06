Here is the updated and polished `README.md` file for your GitHub repository. I've integrated your portfolio link prominently so that both developers and potential clients can easily see your work.

---

# FANNI (فني) - Smart Shop & POS Management

**The complete digital solution for mobile maintenance, retail stores, and financial tracking in the Egyptian market.**[cite: 1]

FANNI is a high-performance, full-stack application built to bridge the gap between traditional shop management and modern financial tracking. It is specifically tailored for the needs of Egyptian craftsmen and technicians, offering deep integration for local services like maintenance logs and wallet management (e.g., Vodafone Cash).[cite: 1]

---

## 🔗 Connect With The Developer

Interested in seeing more of my work or hiring me for a project?

*   **🌐 Portfolio:** [**Visit My Portfolio & See My Work**](https://mahmoudfawzee.github.io/portfolio-web-backend-based/)
*   **👨‍💻 About Me:** Full-Stack Developer specializing in high-performance Flutter and Node.js applications.[cite: 1]

---

## 📱 For Shop Owners

FANNI acts as your shop's "digital brain," handling complex accounting so you can focus on technical work.

### Key Features:
*   **Maintenance Tracking:** Log repairs, manage spare parts, and track service status for mobile devices.[cite: 1]
*   **Smart Balance System:** Automatically tracks if a customer owes you money (**عليك**) or has a credit balance (**لك**) using a custom "Zero-Crossing" algorithm.[cite: 1, 2]
*   **Financial Ledger (كشف حساب):** Generate professional PDF account statements in Arabic for your customers.[cite: 2, 3]
*   **Wallet & SIM Management:** Specialized tracking for local balance transfers and mobile wallet transactions.[cite: 1]
*   **Arabic-First Interface:** Full RTL (Right-to-Left) support with terminology customized for the Egyptian market.[cite: 1, 2]

---

## 🛠 For Developers

This project is built using a strict **Clean Architecture** pattern to ensure long-term scalability and code maintainability.[cite: 1]

### Tech Stack:
*   **Frontend:** Flutter (Mobile) using BLoC / Cubit for state management.[cite: 1]
*   **Backend:** Node.js with Express and TypeScript.[cite: 1]
*   **Database:** MongoDB (Mongoose) with atomic session support.[cite: 1, 2]
*   **Reporting:** PDFKit with `arabic-reshaper` and `bidi-js` for RTL text shaping and BiDi reordering.[cite: 2, 3]

### Project Structure:
*   `/fanni-backend`: RESTful API, JWT Authentication, and PDF generation logic.[cite: 1, 2]
*   `/fanni-mobile`: Flutter mobile app organized into Data, Domain, and Presentation layers.[cite: 1]

### Core Logic Implementation:
*   **Financial Integrity:** Real-time global balance updates using MongoDB `$inc` operators to ensure dashboard accuracy without expensive loops.[cite: 1, 2]
*   **RTL PDF Generation:** Custom implementation to fix Arabic character disconnection and reversal issues in PDF documents.[cite: 2, 3]

---

## 👨‍💻 Developer & Lead Engineer
**Eng. Mahmoud Fawzy El-Tohamy**  
Full-Stack Developer | Flutter & Node.js Specialist[cite: 1]

---

## ⚖️ License
Designed and developed for mobile store management in Egypt. All rights reserved.[cite: 1]
