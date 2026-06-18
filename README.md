# Fresh to Home eCommerce Website - Business Analysis & SRS

## 📌 Project Overview
A comprehensive Software Requirements Specification (SRS) for "Fresh to Home," a digital storefront designed to transition a physical supermarket in Ernakulam into a fully functional online grocery platform[cite: 1]. This project outlines the core functionalities required to manage local delivery logistics, multi-store inventory routing, and modern payment integrations[cite: 1].

## 🎯 Business Problem & Solution
The client needed a digital solution to capture customer data and streamline the daily delivery of groceries, meat, and milk[cite: 1]. The proposed system restricts access to a 7km radius, automatically routes orders to the nearest physical branch, and introduces a subscription model for recurring daily essentials[cite: 1].

## 🛠️ Key Artifacts & Documentation
* **Comprehensive SRS Document:** Covering detailed Functional and Non-Functional Requirements[cite: 1].
* **Detailed User Stories:** 10 documented user stories with strict acceptance criteria covering customer and admin workflows[cite: 1].
* **UML Visualizations:** Activity Diagrams for system logic and Use Case Diagrams for actor interactions[cite: 2, 3].

## 📂 Project Highlights & UML Diagrams

### 1. Smart Location & Order Routing (Activity Diagram)
Designed the logical flow for location-based access. The system validates the user's PIN code to ensure they are within the 7km service area before allowing access to the store, and dynamically routes the checkout process based on subscription or standard order types[cite: 1, 2].
![Process Flowchart](process-flowchart.png)

### 2. System Actors & Interactions (Use Case Diagram)
Mapped out the distinct permissions and system interactions for three primary actors: Customers, Store Admins, and Delivery Partners. This includes complex use cases like Binance cryptocurrency payment integrations and managing same-day delivery logistics[cite: 1, 3].
![Use Case Diagram](use-case-diagram.png)

### 3. Subscription & Multi-Store Management
Authored requirements for a centralized admin panel that controls inventory across two physical branches and generates automated morning dispatch lists for active milk and grocery subscriptions[cite: 1]. 

## 📥 Access the Full Documentation
[📄 View the Full SRS Document (PDF)](./Fresh_to_Home_SRS_Document.pdf)
