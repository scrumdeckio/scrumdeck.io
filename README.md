
<img width="421" height="470" alt="scrumdeck_logo_github" src="https://github.com/user-attachments/assets/a77a93e0-882d-49a3-9b4b-9f9a0bbcae4d" />

# 🃏 [ScrumDeck.io](https://scrumdeck.io)

**Modern Planning Poker Web Application for Agile Teams**

ScrumDeck.io is a real-time Planning Poker tool designed for distributed Scrum teams to collaboratively estimate story points. Built with modern web technologies, it provides seamless remote collaboration with instant voting, team chat, and multiple scoring systems.

## ✨ Features

### 🎯 Core Planning Poker

- **Real-time Voting** - Instant synchronization across all participants
- **Multiple Scoring Systems** - Fibonacci, T-Shirt sizes, Powers of 2, and more
- **Reveal Control** - Session owners control when votes are revealed
- **Average Calculation** - Automatic story point averaging for numeric systems

### 👥 Team Collaboration

- **Live Chat** - Built-in team communication during sessions
- **Participant Management** - Add/remove team members dynamically
- **Session Sharing** - Easy session links for team distribution
- **Owner Controls** - Dedicated tools for Scrum Masters

### 🔐 User Management

- **Secure Authentication** - JWT-based user sessions
- **Premium Subscriptions** - Stripe-integrated payment processing
- **User Profiles** - Account management and preferences
- **Session History** - Track estimation activities

### 🎨 User Experience

- **Responsive Design** - Works seamlessly on desktop and mobile
- **Real-time Updates** - WebSocket-powered instant notifications
- **Clean Interface** - Intuitive design focused on usability
- **Custom Animations** - Smooth transitions and feedback

## 📖 Usage

### For Scrum Masters

1. **Create Account** - Register as a Scrum Master
2. **Start Session** - Create a new Planning Poker session
3. **Share Link** - Distribute session URL to team members
4. **Manage Session** - Control voting rounds and participant access
5. **Review Results** - Analyze voting patterns and averages

### For Team Members

1. **Join Session** - Access via shared session link
2. **Cast Votes** - Select story point estimates
3. **Participate in Chat** - Communicate with team during estimation
4. **View Results** - See collective estimates when revealed

### Session Management

- **Voting Control** - Start/stop voting rounds
- **Participant Management** - Add/remove team members
- **Scoring System Selection** - Choose from multiple estimation scales
- **Result Analysis** - Review voting outcomes and statistics

## 🏗️ Architecture

### System Overview

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Web Browser   │    │   API App        │    │   DB            │
│                 │◄──►│                  │◄──►│                 │
│  - HTML/CSS/JS  │    │  - WebSockets    │    │  - Users        │
│  - WebSockets   │    │  - REST API      │    │  - Sessions     │
│  - Real-time UI │    │  - Authentication│    │  - Preferences  │
└─────────────────┘    └──────────────────┘    └─────────────────┘
                                │
                                ▼
                       ┌──────────────────┐
                       │   Stripe API     │
                       │                  │
                       │  - Payments      │
                       │  - Subscriptions │
                       └──────────────────┘
```

### Key Components

- **WebSocket Manager** - Handles real-time communication
- **Session Engine** - Manages Planning Poker game logic
- **Authentication System** - Secure user management
- **Payment Integration** - Premium subscription handling

## 🔧 Configuration

### Scoring Systems

The application supports multiple estimation scales:

- **Fibonacci** - 1, 2, 3, 5, 8, 13, 21, 34, 55, 89
- **T-Shirt Sizes** - XS, S, M, L, XL, XXL
- **Powers of 2** - 1, 2, 4, 8, 16, 32, 64
- **Linear** - 1, 2, 3, 4, 5, 6, 7, 8, 9, 10
  etc.

## 🤝 Contributing

This is a proprietary commercial project. Contributions are currently limited to invited collaborators only.

## 📝 License

**Proprietary Software** - All rights reserved.

This software is proprietary and confidential. Unauthorized copying, distribution, or use of this software is strictly prohibited. Contact info(at)scrumdeck.io for licensing inquiries.

## 🆘 Support

### Documentation

- **User Guide** - (TBD) Available at [scrumdeck.io/docs](https://scrumdeck.io/docs)

### Contact

- **Email**: info(at)scrumdeck.io
- **Website**: [scrumdeck.io](https://scrumdeck.io)
- **Support**: Available for premium subscribers

### Reporting Issues

For bug reports or feature requests, please contact our support team with:

- Detailed description of the issue
- Steps to reproduce
- Browser and operating system information
- Screenshots if applicable

---

**Built with ❤️ for Agile Teams**

_ScrumDeck.io - Making story point estimation collaborative, efficient, and enjoyable._
