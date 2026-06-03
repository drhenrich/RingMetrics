# Privacy Policy for OOura

**Last Updated: June 03, 2026**

At OOura ("we," "our," or "us"), we are committed to protecting your privacy and ensuring you have complete control over your health and wellness data. This Privacy Policy describes how we collect, use, store, and share your personal data when you use the OOura iOS application and watchOS companion app.

## 1. Data Collection and framework usage
OOura requests access to Apple’s HealthKit framework to read and display your wellness metrics. Specifically, we collect:
*   **Sleep Metrics**: Sleep stages, sleep duration, sleep efficiency, lowest heart rate, and average HRV.
*   **Activity Metrics**: Daily steps, active calorie burn, and workout details.
*   **Readiness Metrics**: Autonomic recovery stats (resting heart rate, HRV balance, and body temperature deviation).

This data is used exclusively to display wellness analytics, populate historical trends charts, and compute personalized cognitive recovery scores.

## 2. On-Device Local Processing
All biometric and HealthKit data is processed **locally on your device**. 
*   **Local Storage**: Biometric metrics are cached directly in a high-performance SQLite database on your iPhone.
*   **Optional Local Server Sync**: If you choose to configure the "Local Server" option in Settings, data is synced strictly to your private self-hosted server on your local network.
*   **No Commercial Cloud Transmission**: We do **not** upload, store, or transmit your health records to any commercial cloud servers, advertisers, or third-party databases.

## 3. Strict AI Privacy & Zero Third-Party Sharing
OOura features an interactive AI Health Analyst to help you understand your wellness metrics.
*   **Local Execution**: The AI Health Analyst runs completely on-device or via your self-hosted private server.
*   **No Commercial LLM Sharing**: Your personal health data is **never** transmitted, shared, or sold to external commercial AI platforms (such as OpenAI, Anthropic, or Google) or any third-party service provider.
*   **User Permission**: The application will explicitly request your permission before accessing HealthKit and before enabling the AI Health Analyst.

## 4. Data Control and Deletion
You have complete ownership of your data:
*   **Revoke Health Access**: You can revoke HealthKit access at any time in the iOS Settings app under `Privacy > Health > OOura`.
*   **Delete History**: You can wipe your SQLite database history directly inside the app's settings or by uninstalling the application.

## 5. Contact Information & Support
If you have any questions or require support regarding your privacy, please visit:
*   Support Webpage: `https://github.com/drhenrich`
*   Developer Profile: `https://github.com/drhenrich`
