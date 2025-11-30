# CIH NGO Traceability Dashboard

A comprehensive financial traceability and impact monitoring dashboard for NGOs, built specifically for CIH Bank's digital ecosystem.

## 🚀 Overview

This prototype demonstrates a fully functional NGO Traceability Dashboard that integrates with CIH Bank's Wallet Management API to provide real-time financial transparency, impact tracking, and loan eligibility assessment for NGOs.

## ✨ Features

- **Financial Traceability**: Real-time wallet balance and transaction monitoring
- **Impact Analytics**: Track program outcomes and beneficiary reach
- **Document Management**: Upload and validate financial documents
- **CIH Loan Eligibility**: AI-powered scoring system (1-3 scale)
- **Wallet Integration**: Full CIH mobile wallet functionality
- **Real-time Notifications**: Transaction alerts and status updates

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for data visualization
- **Icons**: Font Awesome
- **API Integration**: CIH Wallet Management KIT

## 🔌 API Integration

This prototype implements the complete CIH Wallet Management API specification:

### Implemented Endpoints:
- `GET /wallet/balance` - Real-time wallet balance
- `GET /wallet/operations` - Transaction history
- `POST /wallet/clientinfo` - Customer profile data
- `POST /wallet/cash/in` - Deposit operations (2-step process)
- `POST /wallet/transfer/wallet` - Wallet-to-wallet transfers (3-step process)

### API Features:
- **Multi-step Transactions**: Complete flows for cash operations and transfers
- **OTP Security**: Secure transaction validation
- **Real-time Data**: Auto-refresh every 30 seconds
- **Error Handling**: Graceful fallback to mock data

## 🚀 Quick Start

### Option 1: Direct Browser Opening
```bash
# Download index.html and open in browser
start index.html
# or double-click the index.html file
