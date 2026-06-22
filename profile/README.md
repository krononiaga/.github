# KluangPay

A project of Application Development that enables secure online rent payment for tenants of Pejabat Daerah Kluang (PDK).

## User Authentication Subsystem

### Developer: LUTFI HAZIQ BIN MOHAMAD HAPISOL

| Number | Module Name | Frontend (Screens) | Backend (Controllers) |
| :--- | :--- | :--- | :--- |
| **1** | **User Authentication Module** | • LoginPage.tsx | • AuthController.php |
| **2** | **Profile Management Module** | • ProfileManagement.tsx | • ProfileController.php |
| **3** | **User Roles Module** | • AdminDashboard.tsx<br>• TenantDashboard.tsx | • DashboardController.php<br>• UserController.php |

## Payment Gateway Subsystem

### Developer: NOOR AIDID IZMER BIN NOOR HABIB

| Sprint | Module Name | Frontend | Backend |
| :--- | :--- | :--- | :--- |
| 1 | Payment Authorization Module | Screens:<br> • [PaymentScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/PaymentScreen.tsx)<br> • [InvalidPaymentPopup.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/InvalidPaymentPopup.tsx)<br> • [AdminReviewScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/AdminReviewScreen.tsx) | Controllers:<br> • [server.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/server.ts)<br> • [paymentController.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/paymentController.ts)<br> • [adminController.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/adminController.ts) |
| 2 | Provider Integration Module | Screens:<br> • [ProviderSelectionScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/ProviderSelectionScreen.tsx)<br> • [ProviderResponseScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/ProviderResponseScreen.tsx)<br> • [RetrySwitchScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/RetrySwitchScreen.tsx) | Controllers:<br> • [providerController.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/providerController.ts)<br> • [retryController.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/retryController.ts) |
| 3 | Settlement Module | Screens:<br> • [SettlementConfirmScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/SettlementConfirmScreen.tsx)<br> • [TenantLedgerScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/TenantLedgerScreen.tsx)<br> • [ReceiptScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/ReceiptScreen.tsx)<br> • [FailedSettlementScreen.tsx](https://github.com/Lukhmannnn/KluangPay/blob/main/frontend/FailedSettlementScreen.tsx) | Controllers:<br> • [settlementController.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/settlementController.ts)<br> • [ledgerController.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/ledgerController.ts)<br> • [receiptController.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/receiptController.ts)<br> • [failedSettlementController.ts](https://github.com/Lukhmannnn/KluangPay/blob/main/backend/failedSettlementController.ts) |

## AI Advisor Chatbot Subsystem

### Developer: LUKHMAN NUR ISKANDAR BIN KHAIRUDIN

| Sprint | Module Name | Frontend | Backend |
| :--- | :--- | :--- | :--- |
| 1 | Chatbot Module | Screens:<br> • TenantChatbot.tsx<br> | Controllers: |
| 2 | Analytics and Reporting Module | Screens:<br> • Analytics.tsx<br> • Reporting.tsx<br> | Controllers: |
| 3 | Tenant Profile Update Module | Screens:<br> • TenantProfile.tsx<br> • Update.tsx<br> | Controllers: |

## Billing & Fee Management Subsystem

### Developer: AQIL DZARFAN BIN ASRUL SHARAFF

| Sprint | Module Name | Frontend | Backend |
| :--- | :--- | :--- | :--- |
| 1 | Outstanding Balance Module | Screens:<br> • TenantDashboard.tsx<br> | Controllers: |
| 2 | Invoice & Due Date Module | Screens:<br> • TenantDashboard.tsx<br> | Controllers: |
| 3 | Fee Calculation Module | Screens:<br> • TenantDashboard.tsx<br> • AdminDashboard.tsx<br> | Controllers: |

## Notes

1. Click on file names to navigate directly to their respective files in the repository.
