# Neutra Link

**Regulating Fishing Supply Chains With Blockchain Protection**

Neutra Link is a comprehensive blockchain-integrated platform designed to bring transparency, traceability, and sustainability to the global fishing supply chain. By leveraging blockchain technology, real-time monitoring, and advanced analytics, Neutra Link ensures that every catch is verifiable, compliant, and environmentally responsible.

## The Problem (inspiration)
Fishing on the high seas is fragmented, unverifiable, and dangerous to the environment

and if unregulated, fishermen commit biblical levels of greed and harm the environment

Illegal, unregulated fishing **steals $20–50 billion** per year from nationally protected ecosystems (Congress 2024)

Bottom trawler **destroys ~3.9 billion acres of seafloor** habitats every single year (F&F Lab 2021)

*an area larger than the U.S. and China combined

Bycatching **discards 38 million tons of marine** life every year (WWF 2009) 

*bycatch -> unintended non-target catch

All because ```modern fishing regulations are unverifiable```

And the root of all evil starts from the consumer perspective, trying to hunt for the cheapest high value deals on fish.

Competitive prices create difficult conditions for fishers to operate in and make up for by cheating the law

But consumers aren't exactly happy about the environment destroyed, 

they just need a way to understand how their choices affect the fishing supply chain.

Instead of relying on a global seafood traceability system is built on some magical thing called trust

we decided to build a system to verify, visualize, and improve the fishing supply chain sustainability

## The Solution

Neutra Link is a cross-platform blockchain-integrated system designed to achieve five core objectives:

- **Simplicity** - Intuitive interfaces for all stakeholders
- **Support** - Monetary and regulatory empowerment for sustainable practices
- **Traceability + Transparency** - Complete visibility across the supply chain
- **Ecocentric** - Environmental protection at the core of operations
- **Security** - Blockchain-backed immutability and verification

## How It Works

Neutra Link consists of five integrated components:

1. **Hardware Integration** - IoT devices and sensors for real-time vessel tracking and catch verification
2. **Blockchain Technology** - Transparent, verifiable, and immutable record-keeping
3. **Mobile Application** - Accessible platform for consumers, fishermen, and supply chain participants
4. **Web Dashboard** - Comprehensive monitoring and analytics for regulators and administrators
5. **AI Assistant** - Intelligent support system for all users

Together, these components create an end-to-end solution that tracks fish from ocean to consumer, ensuring compliance, sustainability, and transparency at every step.

## Technology Stack

- **Frontend**: Next.js 15, React 19, TypeScript, Tailwind CSS
- **Backend**: Python (FastAPI), Supabase
- **Blockchain**: Solana (Anchor framework)
- **Mapping**: Mapbox GL, React Globe GL
- **Authentication**: Supabase Auth with OAuth providers

## Project Structure

```
Neutra-Link/
├── frontend/          # Next.js web application
├── backend/           # FastAPI backend services
├── mobile/            # React Native mobile app
└── web3/              # Solana blockchain programs
```

## Getting Started

### Prerequisites

- Node.js 18+ and npm
- Python 3.9+
- Solana CLI tools (for blockchain development)

### Installation

1. Clone the repository
2. Install frontend dependencies: `cd frontend && npm install`
3. Install backend dependencies: `cd backend && pip install -r requirements.txt`
4. Set up environment variables (see `env.template` files)
5. Run the development server: `npm run dev`

## Challenges Overcome

During development, we faced significant learning curves with blockchain technology, including Solana program development, token operations, and smart contract deployment. Through persistence and collaboration, we successfully built and deployed a fully functional blockchain-integrated system.

## License

This project is part of a hackathon submission and is intended for demonstration purposes.
