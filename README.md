# MNEEPay---Enterprise-Crypto-Financial-Platform
MNEEPay is the all-in-one platform for enterprise crypto. It seamlessly integrates corporate VISA cards, B2B Invoicing, and Staking into a premium Dashboard. Featuring deep Analytics and a Smart Extension for web-wide payments, MNEEPay bridges the gap between traditional corporate treasury and the speed of stablecoins.


> **The Operating System for Modern Finance.**
> Bridging the gap between traditional corporate treasury and the MNEE Stablecoin ecosystem.

MEGA Drive: https://mega.nz/folder/i15wVSIb#PLu1CM1xQqbYVVnaDcqRKw

DEMO APP: https://mneepay.netlify.app/

VIDEO DEMONSTRATION: https://www.loom.com/share/1334581edde14d7fb2475795cd920346

## 📖 Overview

MNEEPay is a comprehensive **Enterprise Resource Planning (ERP)** tool for the crypto age. It is designed for merchants, CFOs, and businesses that need to manage both fiat-like stablecoin operations and traditional card expenditures in one unified interface.

It consists of two synchronized applications:
1.  **Merchant Dashboard**: A robust web application for invoicing, analytics, and treasury management.
2.  **Browser Extension**: A "Smart Companion" that brings MNEE payments to any webpage.

---

## 🚀 Key Features

### 🏢 Enterprise Dashboard
*   **Invoicing System**: Create, track, and manage B2B invoices.
    *   **Public Payment Pages**: Shareable branded links (e.g., `/pay/INV-001`) for customers to pay via crypto.
    *   **PDF Exports**: Generate professional invoices with a single click.
    *   **CSV Data**: Export financial data for external accounting.
*   **Analytics Intelligence**: Deep-dive into spending habits with colorful, category-based visualizations.
*   **Financial Health**: Real-time tracking of "Net Position", "Runway", and "Total Spend".

### 🧩 Smart Extension
*   **MNEE Earn**: A dedicated staking interface allowing users to earn 5.2% APY on idle capital directly from the browser.
*   **Smart Context Scanning**: Automatically detects payment requests on supported merchant sites (e.g., `merchant-demo`) and pre-fills transaction data.
*   **Activity History**: A detailed transaction log with drill-down views for hashes, fees, and status.

### 🛡️ Enterprise Grade
*   **Role-Based Access Control (Simulated)**: Structure designed for teams (Admin, Developer, Viewer).
*   **Compliance Ready**: "Tax Vault" concepts and rigorous data tracking for audit trails.
*   **Mock Data Engine**: Powered by a sophisticated `mockData.ts` generator that creates realistic B2B scenarios (Payroll, Cloud Infra, Legal Retainers).

---

## 🛠️ Technical Stack

*   **Framework**: [React 19](https://react.dev/) + [Vite 7](https://vitejs.dev/)
*   **Language**: TypeScript
*   **Styling**: [TailwindCSS 3.4](https://tailwindcss.com/) (Midnight Dark Theme)
*   **Animation**: Framer Motion for premium interactions.
*   **Blockchain**: Ethers.js v6 for wallet simulation.
*   **Reporting**: `jspdf` for on-the-fly PDF generation.

---

## ⚡ Quick Start

1.  **Install Dependencies**
    ```bash
    npm install
    ```

2.  **Run Development Environment**
    ```bash
    npm run dev
    ```

3.  **Explore**
    *   **Dashboard**: `http://localhost:5173/dashboard/invoices`
    *   **Extension**: `http://localhost:5173/popup`
    *   **Public Checkout**: `http://localhost:5173/pay/INV-001`
    *   **Demo Store**: `http://localhost:5173/merchant-demo`

---

## 🔮 Future Roadmap

*   **AI CFO Agent**: Natural language querying for treasury data ("How much did we spend on AWS last month?").
*   **Developer Portal**: API Key management and Webhook event logs.
*   **Mass Payouts**: CSV-based batch payment processing for payroll.

---

**License**
MIT
