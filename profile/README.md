# KluangPay

A project of Application Development that allow Pejabat Daerah Kluang (PDK) to collect rent from tenants and for tenants to pay off outstanding rent.

## Group Members

| Name | Matric No. | Subsystem |
| :--- | :--- | :--- |
| Lutfi Haziq bin Mohamad Hapisol | A24CS0266 | User Management Subsystem |
| Aqil Dzarfan bin Asrul Sharaff | A24CS0049 | Billing and Fee Management Subsystem |
| Noor Aidid Izmer bin Noor Habib | A24CS0288 | Payment Gateway Subsystem |
| Lukhman Nur Iskandar bin Khairudin | A24CS0265 | AI Subsystem |
| Raid bin Rohisham | A24CS0293 | Notification Subsystem |

---

## User Management Subsystem

**Developer: LUTFI HAZIQ BIN MOHAMAD HAPISOL**

| Module Name | Frontend | Backend |
| :--- | :--- | :--- |
| User Authentication Module | Screens:<br>• [LoginPage.tsx](src/app/components/LoginPage.tsx)<br> | Backend:<br>• [server.js](#) |
| Profile Management Module | Screens:<br>• [ProfileManagement.tsx](src/app/components/ProfileManagement.tsx)<br> | Controllers:<br>• [adminController.js](#)<br> |
| User Roles Module | Screens:<br>• [AdminDashboard.tsx](src/app/components/AdminDashboard.tsx)<br>• [TenantDashboard.tsx](src/app/components/TenantDashboard.tsx)<br> | Controllers:<br>• [accountController.js](#)<br> |

---

## Billing and Fee Management Subsystem

**Developer: AQIL DZARFAN BIN ASRUL SHARAFF**

| Module Name | Frontend | Backend |
| :--- | :--- | :--- |
| Outstanding Balance Module | Screens:<br>• [LoginScreen.js](#)<br>• [RecoverPasswordScreen.js](#)<br>• [RegisterScreen.js](#)<br>• [ResetPasswordScreen.js](#) | Backend:<br>• [server.js](#) |
| Invoice and Due Dates Module | Screens:<br>• [AdminHistoryScreen.js](#)<br>• [AdminReviewScreen.js](#)<br>• [ProfileScreen.js](#)<br>• [ReviewSubmissionScreen.js](#)<br>• [VerificationScreen.js](#)<br>• [DetailsScreen.js](#) | Controllers:<br>• [adminController.js](#)<br>• [emailController.js](#)<br>• [profileController.js](#)<br>• [verifyController.js](#)<br>• [server.js](#)<br><br>MiddleWare:<br>• [authMiddleWare.js](#)<br><br>Routes:<br>• [adminRoutes.js](#)<br>• [emailRoutes.js](#)<br>• [profileRoutes.js](#)<br>• [verifyRoutes.js](#)<br><br>Config:<br>• [db.js](#)<br><br>To start up Cloudflare tunnel and request new quick Tunnel on trycloudflare.com:<br>• [start.bat](#) |
| Fee Calculation Module | Screens:<br>• [AdminDashboardScreen.js](#)<br>• [DemoMarketplaceScreen.js](#)<br>• [DemoSellItemScreen.js](#)<br>• [HomePage.js](#)<br>• [ReportDetailScreen.js](#)<br>• [UserAccessManagementScreen.js](#)<br><br>Components:<br>• [TransactionGuard.js](#) | Controllers:<br>• [accountController.js](#)<br>• [server.js](#)<br><br>MiddleWare:<br>• [authMiddleWare.js](#)<br><br>Routes:<br>• [adminRoutes.js](#)<br>• [emailRoutes.js](#)<br>• [profileRoutes.js](#)<br>• [verifyRoutes.js](#)<br>• [accountRoutes.js](#)<br><br>Config:<br>• [db.js](#) |

---

## Payment Gateway Subsystem

**Developer: NOOR AIDID IZMER BIN NOOR HABIB**

| Module Name | Frontend | Backend |
| :--- | :--- | :--- |
| Payment Authorization Module | Screens:<br>• [LoginPage.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/LoginPage.tsx)<br>• [PaymentPage.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/PaymentPage.tsx)<br>• [AdminReviewScreen.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/AdminReviewScreen.tsx)<br>• [ProfileManagement.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/ProfileManagement.tsx)<br>• [InvalidPaymentPopup.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/InvalidPaymentPopup.tsx) | • [Controller.php](https://github.com/krononiaga/kluangpay-backend/blob/master/app/Http/Controllers/Controller.php) |
| Provider Integration Module | Screens:<br>• [ProviderIntegrationModule.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/ProviderIntegrationModule.tsx)<br>• [BillingModule.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/BillingModule.tsx)<br>• [RetrySwitchScreen.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/RetrySwitchScreen.tsx) | • [Controller.php](https://github.com/krononiaga/kluangpay-backend/blob/master/app/Http/Controllers/Controller.php) <br>• [adminController.js](#)<br>• [emailController.js](#)<br>• [profileController.js](#)<br>• [verifyController.js](#)<br>• [server.js](#)<br><br>MiddleWare:<br>• [authMiddleWare.js](#)<br><br>Routes:<br>• [adminRoutes.js](#)<br>• [emailRoutes.js](#)<br>• [profileRoutes.js](#)<br>• [verifyRoutes.js](#)<br><br>Config:<br>• [db.js](#)<br><br>To start up Cloudflare tunnel and request new quick Tunnel on trycloudflare.com:<br>• [start.bat](#) |
| Settlement Module | Screens:<br>• [SettlementModule.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/SettlementModule.tsx)<br>• [ReceiptConfirmation.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/ReceiptConfirmation.tsx)<br>• [ReceiptDeliveryLog.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/ReceiptDeliveryLog.tsx)<br>• [TenantDashboard.tsx](https://github.com/krononiaga/kluangpay-frontend/blob/master/src/app/components/TenantDashboard.tsx) | • [Controller.php](https://github.com/krononiaga/kluangpay-backend/blob/master/app/Http/Controllers/Controller.php) <br>• [accountController.js](#)<br>• [server.js](#)<br><br>MiddleWare:<br>• [authMiddleWare.js](#)<br><br>Routes:<br>• [adminRoutes.js](#)<br>• [emailRoutes.js](#)<br>• [profileRoutes.js](#)<br>• [verifyRoutes.js](#)<br>• [accountRoutes.js](#)<br><br>Config:<br>• [db.js](#) |

---

## AI Subsystem

**Developer: LUKHMAN NUR ISKANDAR BIN KHAIRUDIN**

| Module Name | Frontend | Backend |
| :--- | :--- | :--- |
| AI Chatbot Module | Screens:<br>• [TenantChatbot.tsx](src/app/components/TenantChatbot.tsx)<br> | Backend:<br>• [server.js](#) |
| Analytics and Reporting Module | Screens:<br>• [BehavioralAnalyticsModule.tsx](src/app/components/BehavioralAnalyticsModule.tsx)<br> | |
| Tenant Profile Update Module | Screens:<br>• [TenantBehavioralProfile.tsx](src/app/components/TenantBehavioralProfile.tsx)<br> | |

---

## Notification Subsystem

**Developer: RAID BIN ROHISHAM**

| Module Name | Frontend | Backend |
| :--- | :--- | :--- |
| Receipt Delivery Module | Screens:<br>• [LoginScreen.js](#)<br>• [RecoverPasswordScreen.js](#)<br>• [RegisterScreen.js](#)<br>• [ResetPasswordScreen.js](#) | Backend:<br>• [server.js](#) |
| Reminder Schedule Module | Screens:<br>• [AdminHistoryScreen.js](#)<br>• [AdminReviewScreen.js](#)<br>• [ProfileScreen.js](#)<br>• [ReviewSubmissionScreen.js](#)<br>• [VerificationScreen.js](#)<br>• [DetailsScreen.js](#) | Controllers:<br>• [adminController.js](#)<br>• [emailController.js](#)<br>• [profileController.js](#)<br>• [verifyController.js](#)<br>• [server.js](#)<br><br>MiddleWare:<br>• [authMiddleWare.js](#)<br><br>Routes:<br>• [adminRoutes.js](#)<br>• [emailRoutes.js](#)<br>• [profileRoutes.js](#)<br>• [verifyRoutes.js](#)<br><br>Config:<br>• [db.js](#)<br><br>To start up Cloudflare tunnel and request new quick Tunnel on trycloudflare.com:<br>• [start.bat](#) |
| Notification Preference Module | Screens:<br>• [AdminDashboardScreen.js](#)<br>• [DemoMarketplaceScreen.js](#)<br>• [DemoSellItemScreen.js](#)<br>• [HomePage.js](#)<br>• [ReportDetailScreen.js](#)<br>• [UserAccessManagementScreen.js](#)<br><br>Components:<br>• [TransactionGuard.js](#) | Controllers:<br>• [accountController.js](#)<br>• [server.js](#)<br><br>MiddleWare:<br>• [authMiddleWare.js](#)<br><br>Routes:<br>• [adminRoutes.js](#)<br>• [emailRoutes.js](#)<br>• [profileRoutes.js](#)<br>• [verifyRoutes.js](#)<br>• [accountRoutes.js](#)<br><br>Config:<br>• [db.js](#) |

---
