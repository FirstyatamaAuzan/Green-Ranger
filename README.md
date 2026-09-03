from pathlib import Path

readme = r'''# Green Ranger

### Digital Waste Management & Recycling Platform

Green Ranger is a web-based application designed to encourage sustainable waste management by connecting waste collection activities with a **reward-based system**.

The platform helps users manage recyclable waste, request waste pickup, earn points from collected materials, and redeem those points for useful rewards. Green Ranger aims to make recycling more accessible, structured, and rewarding for the community.

---

## Features

### User Management
- User registration and authentication
- User profile management
- Secure login and logout
- Personal activity tracking

### Waste Collection
- Submit recyclable waste collection requests
- Schedule waste pickup
- Monitor collection status
- Record collected waste

### Reward Points
- Earn points from recyclable waste
- View accumulated points
- Track point transaction history
- Redeem points for available rewards

### Waste Information
- Information about recyclable waste
- Waste categories and types
- Recycling guidance
- Educational content related to environmental sustainability

### Location & Pickup
- Pickup location management
- Location information for waste collection
- Support for waste collection activities based on user location

### Reward Redemption
Users can exchange accumulated points for available rewards, such as essential goods and other useful items.

---

## System Workflow

```text
            ┌─────────────────┐
            │      User       │
            └────────┬────────┘
                     │
                     ▼
            ┌─────────────────┐
            │ Register / Login│
            └────────┬────────┘
                     │
                     ▼
            ┌─────────────────┐
            │ Submit Waste    │
            │ Collection      │
            └────────┬────────┘
                     │
                     ▼
            ┌─────────────────┐
            │ Waste Pickup /  │
            │ Collection      │
            └────────┬────────┘
                     │
                     ▼
            ┌─────────────────┐
            │ Points Earned   │
            └────────┬────────┘
                     │
                     ▼
            ┌─────────────────┐
            │ Reward          │
            │ Redemption      │
            └─────────────────┘
