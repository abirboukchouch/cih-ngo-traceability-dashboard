# CIH NGO Traceability Dashboard

A comprehensive financial traceability and impact monitoring dashboard for NGOs, built for CIH Bank's digital ecosystem.

## Overview

This prototype demonstrates a fully functional NGO Traceability Dashboard that integrates with CIH Bank's Wallet Management API to provide real-time financial transparency, impact tracking, and loan eligibility assessment for NGOs.

##  Features

- **Financial Traceability**: Real-time wallet balance and transaction monitoring
- **Impact Analytics**: Track program outcomes and beneficiary reach
- **Document Management**: Upload and validate financial documents
- **CIH Loan Eligibility**: AI-powered scoring system (1-3 scale)
- **Wallet Integration**: Full CIH mobile wallet functionality
- **Real-time Notifications**: Transaction alerts and status updates

##  Technologies Used

- **Frontend**: HTML5, CSS, JavaScript
- **Charts**: Chart.js for data visualization
- **Icons**: Font Awesome
- **API Integration**: CIH Wallet Management KIT

##  API Integration

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

##  Quick Start

# Using Python
python -m http.server 8000
# Then visit http://localhost:8000

Prototype Features
Dashboard Sections:
Financial Overview - Real-time balance and transaction history

Impact Metrics - Program outcomes and beneficiary tracking

Document Upload - Drag & drop financial document management

Loan Eligibility - AI-powered scoring (1-3 scale)

Notifications - Real-time alerts and updates

Key Functionality:
Real CIH API integration structure
Mock data with realistic NGO scenarios
Responsive design for mobile and desktop
Interactive charts and data visualization
Complete user workflow demonstration

Use Case
For NGOs:
Track donation allocation and program spending

Prove financial transparency to donors

Access CIH performance-based loans

Monitor social impact metrics

For CIH Bank:
Reduce risk through financial traceability

Enable data-driven lending decisions

Strengthen NGO banking relationships

Enhance CSR and ESG positioning

Future Enhancements
Real backend API integration

User authentication and multi-tenant support

Document OCR and automated validation

Advanced AI impact scoring

Mobile app version

Donor portal access

Contact
Built for CIH Bank Hackathon - Demonstrating the future of NGO banking and financial transparency.



