# AquaSmart - Complete Project Structure

## Directory Layout

```
AquaSmart/
│
├── 📁 website/                          # Next.js Marketing Website
│   ├── 📁 public/
│   │   ├── 📁 images/
│   │   │   ├── logo.png
│   │   │   ├── hero-banner.png
│   │   │   ├── device-mockup.png
│   │   │   ├── app-mockup.png
│   │   │   ├── dashboard-preview.png
│   │   │   └── water-animation.gif
│   │   ├── 📁 icons/
│   │   │   ├── water.svg
│   │   │   ├── lightning.svg
│   │   │   ├── lock.svg
│   │   │   ├── star.svg
│   │   │   └── check.svg
│   │   └── favicon.ico
│   │
│   ├── 📁 src/
│   │   ├── 📁 components/
│   │   │   ├── 📁 header/
│   │   │   │   ├── Navbar.tsx
│   │   │   │   ├── MobileMenu.tsx
│   │   │   │   └── header.module.css
│   │   │   ├── 📁 hero/
│   │   │   │   ├── HeroSection.tsx
│   │   │   │   ├── HeroAnimation.tsx
│   │   │   │   └── hero.module.css
│   │   │   ├── 📁 products/
│   │   │   │   ├── ProductGrid.tsx
│   │   │   │   ├── ProductCard.tsx
│   │   │   │   ├── PricingComparison.tsx
│   │   │   │   └── products.module.css
│   │   │   ├── 📁 features/
│   │   │   │   ├── FeaturesSection.tsx
│   │   │   │   ├── FeatureCard.tsx
│   │   │   │   ├── HowItWorks.tsx
│   │   │   │   └── features.module.css
│   │   │   ├── 📁 testimonials/
│   │   │   │   ├── TestimonialSlider.tsx
│   │   │   │   ├── TestimonialCard.tsx
│   │   │   │   └── testimonials.module.css
│   │   │   ├── 📁 blog/
│   │   │   │   ├── BlogGrid.tsx
│   │   │   │   ├── BlogCard.tsx
│   │   │   │   ├── BlogPost.tsx
│   │   │   │   └── blog.module.css
│   │   │   ├── 📁 faq/
│   │   │   │   ├── FAQ.tsx
│   │   │   │   ├── FAQItem.tsx
│   │   │   │   └── faq.module.css
│   │   │   ├── 📁 contact/
│   │   │   │   ├── ContactForm.tsx
│   │   │   │   ├── ContactMap.tsx
│   │   │   │   └── contact.module.css
│   │   │   ├── 📁 booking/
│   │   │   │   ├── BookDemoModal.tsx
│   │   │   │   ├── DemoForm.tsx
│   │   │   │   ├── DemoSuccess.tsx
│   │   │   │   └── booking.module.css
│   │   │   ├── 📁 orders/
│   │   │   │   ├── OrderForm.tsx
│   │   │   │   ├── OrderSuccess.tsx
│   │   │   │   └── orders.module.css
│   │   │   ├── 📁 footer/
│   │   │   │   ├── Footer.tsx
│   │   │   │   ├── FooterLinks.tsx
│   │   │   │   └── footer.module.css
│   │   │   ├── 📁 common/
│   │   │   │   ├── Button.tsx
│   │   │   │   ├── Modal.tsx
│   │   │   │   ├── Input.tsx
│   │   │   │   ├── Toast.tsx
│   │   │   │   └── common.module.css
│   │   │   └── 📁 subscription/
│   │   │       ├── SubscriptionPlans.tsx
│   ��   │       ├── PlanCard.tsx
│   │   │       └── subscription.module.css
│   │   │
│   │   ├── 📁 pages/
│   │   │   ├── _app.tsx
│   │   │   ├── _document.tsx
│   │   │   ├── _error.tsx
│   │   │   ├── index.tsx
│   │   │   ├── about.tsx
│   │   │   ├── products.tsx
│   │   │   ├── features.tsx
│   │   │   ├── pricing.tsx
│   │   │   ├── blog.tsx
│   │   │   ├── blog/[slug].tsx
│   │   │   ├── faq.tsx
│   │   │   ├── contact.tsx
│   │   │   ├── demo.tsx
│   │   │   ├── order.tsx
│   │   │   ├── order-success.tsx
│   │   │   ├── demo-success.tsx
│   │   │   ├── privacy.tsx
│   │   │   ├── terms.tsx
│   │   │   └── 📁 api/
│   │   │       ├── contact.ts
│   │   │       ├── book-demo.ts
│   │   │       ├── place-order.ts
│   │   │       ├── subscribe.ts
│   │   │       ├── feedback.ts
│   │   │       └── payment-webhook.ts
│   │   │
│   │   ├── 📁 styles/
│   │   │   ├── globals.css
│   │   │   ├── variables.css
│   │   │   ├── animations.css
│   │   │   └── responsive.css
│   │   │
│   │   ├── 📁 utils/
│   │   │   ├── firebase.ts
│   │   │   ├── razorpay.ts
│   │   │   ├── email.ts
│   │   │   ├── validators.ts
│   │   │   ├── api-client.ts
│   │   │   └── helpers.ts
│   │   │
│   │   ├── 📁 hooks/
│   │   │   ├── useAuth.ts
│   │   │   ├── useForm.ts
│   │   │   ├── useToast.ts
│   │   │   ├── useFetch.ts
│   │   │   └── useLocalStorage.ts
│   │   │
│   │   ├── 📁 types/
│   │   │   ├── index.ts
│   │   │   ├── user.ts
│   │   │   ├── product.ts
│   │   │   ├── order.ts
│   │   │   └── device.ts
│   │   │
│   │   ├── 📁 data/
│   │   │   ├── products.ts
│   │   │   ├── features.ts
│   │   │   ├── testimonials.ts
│   │   │   ├── blog-posts.ts
│   │   │   ├── faq.ts
│   │   │   └── constants.ts
│   │   │
│   │   └── 📁 config/
│   │       ├── firebase-config.ts
│   │       ├── razorpay-config.ts
│   │       └── app-config.ts
│   │
│   ├── .env.example
│   ├── .env.local
│   ├── next.config.js
│   ├── tsconfig.json
│   ├── package.json
│   ├── package-lock.json
│   └── README.md
│
├── 📁 mobile-app/                       # React Native Mobile App
│   ├── 📁 src/
│   │   ├── 📁 navigation/
│   │   │   ├── RootNavigator.tsx
│   │   │   ├── AuthNavigator.tsx
│   │   │   ├── AppNavigator.tsx
│   │   │   └── linking.ts
│   │   │
│   │   ├── 📁 screens/
│   │   │   ├── 📁 auth/
│   │   │   │   ├── SplashScreen.tsx
│   │   │   │   ├── LoginScreen.tsx
│   │   │   │   ├── SignupScreen.tsx
│   │   │   │   ├── ForgotPasswordScreen.tsx
│   │   │   │   ├── OTPScreen.tsx
│   │   │   │   └── GoogleLoginScreen.tsx
│   │   │   ├── 📁 dashboard/
│   │   │   │   ├── DashboardScreen.tsx
│   │   │   │   ├── TankLevelCard.tsx
│   │   │   │   ├── MotorControlCard.tsx
│   │   │   │   ├── QuickStats.tsx
│   │   │   │   └── NotificationCenter.tsx
│   │   │   ├── 📁 devices/
│   │   │   │   ├── DeviceListScreen.tsx
│   │   │   │   ├── DeviceDetailScreen.tsx
│   │   │   │   ├── AddDeviceScreen.tsx
│   │   │   │   ├── QRScannerScreen.tsx
│   │   │   │   ├── RenameDeviceScreen.tsx
│   │   │   │   └── RemoveDeviceScreen.tsx
│   │   │   ├── 📁 motor-control/
│   │   │   │   ├── MotorControlScreen.tsx
│   │   │   │   ├── MotorStatus.tsx
│   │   │   │   ├── AutoControlSettings.tsx
│   │   │   │   ├── ScheduleMotor.tsx
│   │   │   │   └── MotorHistory.tsx
│   │   │   ├── 📁 analytics/
│   │   │   │   ├── AnalyticsScreen.tsx
│   │   │   │   ├── UsageChart.tsx
│   │   │   │   ├── DailyAnalysis.tsx
│   │   │   │   ├── WeeklyReport.tsx
│   │   │   │   ├── MonthlyReport.tsx
│   │   │   │   └── CostSavings.tsx
│   │   │   ├── 📁 notifications/
│   │   │   │   ├── NotificationsScreen.tsx
│   │   │   │   ├── NotificationItem.tsx
│   │   │   │   ├── NotificationSettings.tsx
│   │   │   │   └── NotificationPreferences.tsx
│   │   │   ├── 📁 subscription/
│   │   │   │   ├── SubscriptionScreen.tsx
│   │   │   │   ├── PlanCard.tsx
│   │   │   │   ├── PaymentScreen.tsx
│   │   │   │   ├── UpgradeModal.tsx
│   │   │   │   └── InvoiceScreen.tsx
│   │   │   ├── 📁 profile/
│   │   │   │   ├── ProfileScreen.tsx
│   │   │   │   ├── EditProfileScreen.tsx
│   │   │   │   ├── ChangePasswordScreen.tsx
│   │   │   │   ├── NotificationPrefsScreen.tsx
│   │   │   │   ├── PrivacyScreen.tsx
│   │   │   │   ├── HelpScreen.tsx
│   │   │   │   ├── AboutScreen.tsx
│   │   │   │   └── LogoutScreen.tsx
│   │   │   ├── 📁 leak-detection/
│   │   │   │   ├── LeakDetectionScreen.tsx
│   │   │   │   ├── LeakAlert.tsx
│   │   │   │   ├── LeakHistory.tsx
│   │   │   │   └── LeakAnalysis.tsx
│   │   │   └── 📁 ai-insights/
│   │   │       ├── AIInsightsScreen.tsx
│   │   │       ├── WaterPrediction.tsx
│   │   │       ├── UsageTrends.tsx
│   │   │       └── AIRecommendations.tsx
│   │   │
│   │   ├── 📁 components/
│   │   │   ├── 📁 common/
│   │   │   │   ├── Button.tsx
│   │   │   │   ├── Input.tsx
│   │   │   │   ├── Text.tsx
│   │   │   │   ├── Card.tsx
│   │   │   │   ├── Modal.tsx
│   │   │   │   ├── Loader.tsx
│   │   │   │   ├── Toast.tsx
│   │   │   │   ├── BottomSheet.tsx
│   │   │   │   ├── Header.tsx
│   │   │   │   └── SafeArea.tsx
│   │   │   ├── 📁 device/
│   │   │   │   ├── DeviceCard.tsx
│   │   │   │   ├── DeviceTile.tsx
│   │   │   │   └── DeviceStatus.tsx
│   │   │   ├── 📁 charts/
│   │   │   │   ├── LineChart.tsx
│   │   │   │   ├── BarChart.tsx
│   │   │   │   ├── PieChart.tsx
│   │   │   │   └── AreaChart.tsx
│   │   │   └── 📁 auth/
│   │   │       ├── AuthForm.tsx
│   │   │       ├── SocialLogin.tsx
│   │   │       └── PasswordInput.tsx
│   │   │
│   │   ├── 📁 services/
│   │   │   ├── firebase-service.ts
│   │   │   ├── auth-service.ts
│   │   │   ├── device-service.ts
│   │   │   ├── motor-service.ts
│   │   │   ├── analytics-service.ts
│   │   │   ├── notification-service.ts
│   │   │   ├── subscription-service.ts
│   │   │   ├── payment-service.ts
│   │   │   ├── storage-service.ts
│   │   │   └── api-service.ts
│   │   │
│   │   ├── 📁 state/
│   │   │   ├── 📁 auth/
│   │   │   │   ├── auth-slice.ts
│   │   │   │   ├── auth-actions.ts
│   │   │   │   └── auth-selectors.ts
│   │   │   ├── 📁 devices/
│   │   │   │   ├── device-slice.ts
│   │   │   │   ├── device-actions.ts
│   │   │   │   └── device-selectors.ts
│   │   │   ├── 📁 notifications/
│   │   │   │   ├── notification-slice.ts
│   │   │   │   ├── notification-actions.ts
│   │   │   │   └── notification-selectors.ts
│   │   │   ├── 📁 subscription/
│   │   │   │   ├── subscription-slice.ts
│   │   │   │   ├── subscription-actions.ts
│   │   │   │   └── subscription-selectors.ts
│   │   │   ├── 📁 analytics/
│   │   │   │   ├── analytics-slice.ts
│   │   │   │   ├── analytics-actions.ts
│   │   │   │   └── analytics-selectors.ts
│   │   │   └── store.ts
│   │   │
│   │   ├── 📁 hooks/
│   │   │   ├── useAuth.ts
│   │   │   ├── useDevice.ts
│   │   │   ├── useNotification.ts
│   │   │   ├── useAnalytics.ts
│   │   │   ├── useMotor.ts
│   │   │   ├── usePush.ts
│   │   │   └── usePermissions.ts
│   │   │
│   │   ├── 📁 types/
│   │   │   ├── index.ts
│   │   │   ├── auth.ts
│   │   │   ├── device.ts
│   │   │   ├── motor.ts
│   │   │   ├── analytics.ts
│   │   │   ├── notification.ts
│   │   │   └── subscription.ts
│   │   │
│   │   ├── 📁 utils/
│   │   │   ├── firebase-config.ts
│   │   │   ├── constants.ts
│   │   │   ├── helpers.ts
│   │   │   ├── validators.ts
│   │   │   ├── permissions.ts
│   │   │   ├── date-utils.ts
│   │   │   └── storage-utils.ts
│   │   │
│   │   ├── 📁 config/
│   │   │   ├── firebase-config.ts
│   │   │   ├── app-config.ts
│   │   │   └── theme.ts
│   │   │
│   │   ├── 📁 assets/
│   │   │   ├── 📁 images/
│   │   │   ├── 📁 icons/
│   │   │   ├── 📁 fonts/
│   │   │   └── 📁 animations/
│   │   │
│   │   └── App.tsx
│   │
│   ├── 📁 __tests__/
│   │   ├── services.test.ts
│   │   ├── auth.test.ts
│   │   ├── device.test.ts
│   │   └── motor.test.ts
│   │
│   ├── .env.example
│   ├── .env.local
│   ├── app.json
│   ├── babel.config.js
│   ├── tsconfig.json
│   ├── package.json
│   ├── package-lock.json
│   └── README.md
│
├── 📁 backend/                          # Firebase Cloud Functions & Backend
│   ├── 📁 functions/
│   │   ├── 📁 src/
│   │   │   ├── 📁 auth/
│   │   │   │   ├── auth-controller.ts
│   │   │   │   ├── auth-service.ts
│   │   │   │   ├── auth-validation.ts
│   │   │   │   └── auth-middleware.ts
│   │   │   ├── 📁 users/
│   │   │   │   ├── user-controller.ts
│   │   │   │   ���── user-service.ts
│   │   │   │   ├── user-validation.ts
│   │   │   │   └── user-schema.ts
│   │   │   ├── 📁 devices/
│   │   │   │   ├── device-controller.ts
│   │   │   │   ├── device-service.ts
│   │   │   │   ├── device-validation.ts
│   │   │   │   └── device-schema.ts
│   │   │   ├── 📁 motors/
│   │   │   │   ├── motor-controller.ts
│   │   │   │   ├── motor-service.ts
│   │   │   │   ├── motor-validation.ts
│   │   │   │   └── motor-schema.ts
│   │   │   ├── 📁 orders/
│   │   │   │   ├── order-controller.ts
│   │   │   │   ├── order-service.ts
│   │   │   │   ├── order-validation.ts
│   │   │   │   ├── order-schema.ts
│   │   │   │   └── order-notifications.ts
│   │   │   ├── 📁 payments/
│   │   │   │   ├── payment-controller.ts
│   │   │   │   ├── payment-service.ts
│   │   │   │   ├── razorpay-service.ts
│   │   │   │   ├── payment-validation.ts
│   │   │   │   └── webhook-handler.ts
│   │   │   ├── 📁 subscriptions/
│   │   │   │   ├── subscription-controller.ts
│   │   │   │   ├── subscription-service.ts
│   │   │   │   ├── subscription-validation.ts
│   │   │   │   └── subscription-schema.ts
│   │   │   ├── 📁 analytics/
│   │   │   │   ├── analytics-controller.ts
│   │   │   │   ├── analytics-service.ts
│   │   │   │   ├── analytics-processor.ts
│   │   │   │   ├── usage-calculator.ts
│   │   │   │   └── report-generator.ts
│   │   │   ├── 📁 notifications/
│   │   │   │   ├── notification-controller.ts
│   │   │   │   ├── notification-service.ts
│   │   │   │   ├── email-service.ts
│   │   │   │   ├── push-service.ts
│   │   │   │   ├── sms-service.ts
│   │   │   │   └── notification-templates.ts
│   │   │   ├── 📁 feedback/
│   │   │   │   ├── feedback-controller.ts
│   │   │   │   ├── feedback-service.ts
│   │   │   │   ├── feedback-validation.ts
│   │   │   │   └── feedback-schema.ts
│   │   │   ├── 📁 booking/
│   │   │   │   ├── booking-controller.ts
│   │   │   │   ├── booking-service.ts
│   │   │   │   ├── booking-validation.ts
│   │   │   │   └── booking-schema.ts
│   │   │   ├── 📁 admin/
│   │   │   │   ├── admin-controller.ts
│   │   │   │   ├── admin-service.ts
│   │   │   │   ├── admin-validation.ts
│   │   │   │   ├── dashboard-service.ts
│   │   │   │   └── report-service.ts
│   │   │   ├── 📁 middleware/
│   │   │   │   ├── auth-middleware.ts
│   │   │   │   ├── error-handler.ts
│   │   │   │   ├── rate-limiter.ts
│   │   │   │   ├── cors-handler.ts
│   │   │   │   └── validation-middleware.ts
│   │   │   ├── 📁 utils/
│   │   │   │   ├── logger.ts
│   │   │   │   ├── response-formatter.ts
│   │   │   │   ├── error-formatter.ts
│   │   │   │   ├── email-templates.ts
│   │   │   │   ├── validators.ts
│   │   │   │   ├── date-utils.ts
│   │   │   │   └── helpers.ts
│   │   │   ├── 📁 config/
│   │   │   │   ├── firebase-config.ts
│   │   │   │   ├── environment.ts
│   │   │   │   ├── razorpay-config.ts
│   │   │   │   ├── email-config.ts
│   │   │   │   └── notification-config.ts
│   │   │   ├── 📁 constants/
│   │   │   │   ├── error-codes.ts
│   │   │   │   ├── messages.ts
│   │   │   │   ├── status-codes.ts
│   │   │   │   └── subscription-tiers.ts
│   │   │   ├── 📁 types/
│   │   │   │   ├── express.ts
│   │   │   │   ├── firebase.ts
│   │   │   │   ├── index.ts
│   │   │   │   ├── user.ts
│   │   │   │   ├── device.ts
│   │   │   │   ├── motor.ts
│   │   │   │   ├── order.ts
│   │   │   │   ├── payment.ts
│   │   │   │   ├── subscription.ts
│   │   │   │   └── notification.ts
│   │   │   ├── 📁 routes/
│   │   │   │   ├── auth-routes.ts
│   │   │   │   ├── user-routes.ts
│   │   │   │   ├── device-routes.ts
│   │   │   │   ├── motor-routes.ts
│   │   │   │   ├── order-routes.ts
│   │   │   │   ├── payment-routes.ts
│   │   │   │   ├── subscription-routes.ts
│   │   │   │   ├── analytics-routes.ts
│   │   │   │   ├── notification-routes.ts
│   │   │   │   ├── feedback-routes.ts
│   │   │   │   ├── booking-routes.ts
│   │   │   │   ├── admin-routes.ts
│   │   │   │   └── index.ts
│   │   │   └── index.ts
│   │   │
│   │   ├── 📁 triggers/
│   │   │   ├── user-triggers.ts
│   │   │   ├── order-triggers.ts
│   │   │   ├── payment-triggers.ts
│   │   │   ├── subscription-triggers.ts
│   │   │   ├── notification-triggers.ts
│   │   │   ├── device-triggers.ts
│   │   │   ├── feedback-triggers.ts
│   │   │   └── scheduled-triggers.ts
│   │   │
│   │   ├── 📁 firestore/
│   │   │   ├── collections.ts
│   │   │   ├── indexes.ts
│   │   │   ├── security-rules.ts
│   │   │   └── migration.ts
│   │   │
│   │   ├── .env.example
│   │   ├── .env
│   │   ├── package.json
│   │   ├── tsconfig.json
│   │   └── index.ts
│   │
│   ├── 📁 firestore/
│   │   ├── firestore.rules
│   │   ├── firestore.indexes.json
│   │   └── collections/
│   │       ├── users.ts
│   │       ├── devices.ts
│   │       ├── motors.ts
│   │       ├── orders.ts
│   │       ├── payments.ts
│   │       ├── subscriptions.ts
│   │       ├── analytics.ts
│   │       ├── notifications.ts
│   │       ├── feedback.ts
│   │       └── bookings.ts
│   │
│   ├── 📁 emulators/
│   │   ├── auth-emulator-config.ts
│   │   ├── firestore-emulator-config.ts
│   │   └── setup.ts
│   │
│   ├── 📁 tests/
│   │   ├── auth.test.ts
│   │   ├── user.test.ts
│   │   ├── device.test.ts
│   │   ├── order.test.ts
│   │   ├── payment.test.ts
│   │   └── subscription.test.ts
│   │
│   ├── .env.example
│   ├── .env
│   ├── firebase.json
│   ├── package.json
│   ├── tsconfig.json
│   ├── README.md
│   └── .eslintrc.js
│
├── 📁 admin-dashboard/                  # React Admin Dashboard
│   ├── 📁 public/
│   │   ├── 📁 images/
│   │   └── favicon.ico
│   │
│   ├── 📁 src/
│   │   ├── 📁 components/
│   │   │   ├── 📁 layout/
│   │   │   │   ├── Sidebar.tsx
│   │   │   │   ├── Header.tsx
│   │   │   │   ├── MainLayout.tsx
│   │   │   │   └── layout.module.css
│   │   │   ├── 📁 dashboard/
│   │   │   │   ├── DashboardOverview.tsx
│   │   │   │   ├── StatCard.tsx
│   │   │   │   ├── Charts.tsx
│   │   │   │   └── dashboard.module.css
│   │   │   ├── 📁 users/
│   │   │   │   ├── UsersList.tsx
│   │   │   │   ├── UserDetail.tsx
│   │   │   │   ├── UserForm.tsx
│   │   │   │   └── users.module.css
│   │   │   ├── 📁 orders/
│   │   │   │   ├── OrdersList.tsx
│   │   │   │   ├── OrderDetail.tsx
│   │   │   │   ├── OrderStatus.tsx
│   │   │   │   └── orders.module.css
│   │   │   ├── 📁 devices/
│   │   │   │   ├── DevicesList.tsx
│   │   │   │   ├── DeviceDetail.tsx
│   │   │   │   ├── DeviceStatus.tsx
│   │   │   │   └── devices.module.css
│   │   │   ├── 📁 subscriptions/
│   │   │   │   ├── SubscriptionsList.tsx
│   │   │   │   ├── SubscriptionDetail.tsx
│   │   │   │   └── subscriptions.module.css
│   │   │   ├── 📁 analytics/
│   │   │   │   ├── AnalyticsOverview.tsx
│   │   │   │   ├── UsageCharts.tsx
│   │   │   │   ├── RevenueCharts.tsx
│   │   │   │   └── analytics.module.css
│   │   │   ├── 📁 reports/
│   │   │   │   ├── ReportsList.tsx
│   │   │   │   ├── ReportGenerator.tsx
│   │   │   │   └── reports.module.css
│   │   │   ├── 📁 feedback/
│   │   │   │   ├── FeedbackList.tsx
│   │   │   │   ├── FeedbackDetail.tsx
│   │   │   │   └── feedback.module.css
│   │   │   ├── 📁 bookings/
│   │   │   │   ├── BookingsList.tsx
│   │   │   │   ├── BookingDetail.tsx
│   │   │   │   └── bookings.module.css
│   │   │   ├── 📁 common/
│   │   │   │   ├── Table.tsx
│   │   │   │   ├── Pagination.tsx
│   │   │   │   ├── SearchBar.tsx
│   │   │   │   ├── Button.tsx
│   │   │   │   ├── Modal.tsx
│   │   │   │   ├── Input.tsx
│   │   │   │   └── common.module.css
│   │   │   └── 📁 auth/
│   │   │       ├── LoginForm.tsx
│   │   │       └── ProtectedRoute.tsx
│   │   │
│   │   ├── 📁 pages/
│   │   │   ├── 📁 admin/
│   │   │   │   ├── Dashboard.tsx
│   │   │   │   ├── Users.tsx
│   │   │   │   ├── Orders.tsx
│   │   │   │   ├── Devices.tsx
│   │   │   │   ├── Subscriptions.tsx
│   │   │   │   ├── Analytics.tsx
│   │   │   │   ├── Reports.tsx
│   │   │   │   ├── Feedback.tsx
│   │   │   │   ├── Bookings.tsx
│   │   │   │   └── Settings.tsx
│   │   │   ├── Login.tsx
│   │   │   ├── 404.tsx
│   │   │   ├── 500.tsx
│   │   │   └── NotFound.tsx
│   │   │
│   │   ├── 📁 services/
│   │   │   ├── auth-service.ts
│   │   │   ├── user-service.ts
│   │   │   ├── order-service.ts
│   │   │   ├── device-service.ts
│   │   │   ├── subscription-service.ts
│   │   │   ├── analytics-service.ts
│   │   │   ├── report-service.ts
│   │   │   ├── feedback-service.ts
│   │   │   ├── booking-service.ts
│   │   │   ├── api-client.ts
│   │   │   └── export-service.ts
│   │   │
│   │   ├── 📁 hooks/
│   │   │   ├── useAuth.ts
│   │   │   ├── useFetch.ts
│   │   │   ├── useForm.ts
│   │   │   ├── usePagination.ts
│   │   │   ├── useSearch.ts
│   │   │   └── useExport.ts
│   │   │
│   │   ├── 📁 types/
│   │   │   ├── index.ts
│   │   │   ├── user.ts
│   │   │   ├── order.ts
│   │   │   ├── device.ts
│   │   │   ├── subscription.ts
│   │   │   ├── analytics.ts
│   │   │   └── report.ts
│   │   │
│   │   ├── 📁 utils/
│   │   │   ├── api-client.ts
│   │   │   ├── constants.ts
│   │   │   ├── helpers.ts
│   │   │   ├── validators.ts
│   │   │   ├── date-utils.ts
│   │   │   └── export-utils.ts
│   │   │
│   │   ├── 📁 styles/
│   │   │   ├── globals.css
│   │   │   ├── variables.css
│   │   │   ├── animations.css
│   │   │   └── dashboard.css
│   │   │
│   │   ├── 📁 config/
│   │   │   ├── firebase-config.ts
│   │   │   └── app-config.ts
│   │   │
│   │   ├── App.tsx
│   │   └── index.tsx
│   │
│   ├── 📁 public/
│   │   └── index.html
│   │
│   ├── .env.example
│   ├── .env
│   ├── tsconfig.json
│   ├── package.json
│   ├── package-lock.json
│   ├── craco.config.js
│   └── README.md
│
├── 📁 iot-device/                       # Arduino/ESP32 Firmware
│   ├── 📁 src/
│   │   ├── main.ino
│   │   ├── 📁 config/
│   │   │   ├── wifi-config.h
│   │   │   ├── firebase-config.h
│   │   │   ├── sensor-config.h
│   │   │   └── motor-config.h
│   │   ├── 📁 modules/
│   │   │   ├── wifi-module.cpp
│   │   │   ├── wifi-module.h
│   │   │   ├── firebase-module.cpp
│   │   │   ├── firebase-module.h
│   │   │   ├── sensor-module.cpp
│   │   │   ├── sensor-module.h
│   │   │   ├── motor-module.cpp
│   │   │   ├── motor-module.h
│   │   │   ├── alert-module.cpp
│   │   │   ├── alert-module.h
│   │   │   ├── relay-module.cpp
│   │   │   ├── relay-module.h
│   │   │   ├── ota-module.cpp
│   │   │   └── ota-module.h
│   │   ├── 📁 handlers/
│   │   │   ├── sensor-handler.cpp
│   │   │   ├── sensor-handler.h
│   │   │   ├── motor-handler.cpp
│   │   │   ├── motor-handler.h
│   │   │   ├── command-handler.cpp
│   │   │   ├── command-handler.h
│   │   │   ├── sync-handler.cpp
│   │   │   └── sync-handler.h
│   │   ├── 📁 utils/
│   │   │   ├── logger.h
│   │   │   ├── helpers.h
│   │   │   ├── time-utils.h
│   │   │   └── constants.h
│   │   └── build_flags.h
│   │
│   ├── platformio.ini
│   ├── .gitignore
│   ├── README.md
│   └── PINOUT.md
│
├── 📁 docs/
│   ├── 📁 api/
│   │   ├── authentication.md
│   │   ├── users.md
│   │   ├── devices.md
│   │   ├── motors.md
│   │   ├── orders.md
│   │   ├── payments.md
│   │   ├── subscriptions.md
│   │   ├── analytics.md
│   │   ├── notifications.md
│   │   ├── feedback.md
│   │   └── bookings.md
│   ├── 📁 deployment/
│   │   ├── firebase-setup.md
│   │   ├── website-deployment.md
│   │   ├── mobile-app-deployment.md
│   │   ├── backend-deployment.md
│   │   └── admin-dashboard-deployment.md
│   ├── 📁 architecture/
│   │   ├── system-architecture.md
│   │   ├── database-schema.md
│   │   ├── api-design.md
│   │   └── security-architecture.md
│   ├── 📁 getting-started/
│   │   ├── setup-guide.md
│   │   ├── development-setup.md
│   │   ├── testing-guide.md
│   │   └── contributing.md
│   ├── 📁 guides/
│   │   ├── authentication-guide.md
│   │   ├── device-integration.md
│   │   ├── payment-integration.md
│   │   ├── email-setup.md
│   │   ├── firebase-rules.md
│   │   └── troubleshooting.md
│   └── FAQ.md
│
├── .env.example
├── .gitignore
├── README.md
├── PROJECT_STRUCTURE.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── LICENSE
```

## File Count Summary

- **Website**: 120+ files
- **Mobile App**: 150+ files
- **Backend**: 100+ files
- **Admin Dashboard**: 80+ files
- **IoT Device**: 30+ files
- **Documentation**: 20+ files
- **Total**: 500+ files

---

## Key Features by Module

### Website
- Responsive design
- SEO optimized
- Payment integration
- Contact forms
- Demo booking
- Blog system

### Mobile App
- Real-time dashboard
- Device management
- Motor control
- Analytics
- Push notifications
- Offline support

### Backend
- User management
- Device management
- Payment processing
- Email automation
- Analytics engine
- Admin APIs

### Admin Dashboard
- User management
- Order tracking
- Device monitoring
- Report generation
- Data export
- Analytics

### IoT Device
- WiFi connectivity
- Sensor integration
- Motor control
- OTA updates
- Alert system
- Firebase sync

---

End of complete project structure.
