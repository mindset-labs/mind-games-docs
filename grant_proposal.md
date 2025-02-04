# MindGames: Grant Proposal <img src="https://pbs.twimg.com/profile_images/1867370407772168192/3T8R922l_400x400.jpg" align="right" width="100">

## 2. Applicant Information
- **Organization/Individual Name**: Mindset Labs  
- **Founders**: Faisal Al Tameemi, Helwan Mandé  
- **Website**: [MindGames](https://mindset-labs.github.io/tg-mindgames/)  
- **Email**: dao@mindsetlabs.io  
- **X (Twitter)**: [@MindsetLabsDAO](https://x.com/mindsetlabsDAO)  

## 3. Executive Summary
MindGames is a decentralized game-theory platform designed to innovate fair gaming and community engagement. The platform ensures fairness, transparency, and strategic gameplay while leveraging blockchain for secure transactions.

> Inspired by [Jackbox](https://www.jackboxgames.com/) and their success. MindGames aims to be a blockchain-based party game tool similar to Jackbox with academic research potential for fields of game-theory / decision-theory and behavioural economics.

## 4. Problem Statement
Current game-theory education and research tools often lack engagement, interactivity, and real-world applicability, leading to limited understanding and retention of game-theory concepts. Additionally, existing game-theory games platforms are typically centralized, opaque, and vulnerable to manipulation, which can undermine the integrity of research and academic applications.

## 5. Proposed Solution
The proposed blockchain-based platform aims to address these challenges by providing a secure, transparent, and decentralized environment for game-theory education and research, **while also promoting fun and interactive social interactions**. By leveraging blockchain technology, the platform can ensure the integrity and immutability of game data, enable secure and transparent multiplayer interactions, and provide a unique tool for researchers, educators, and students to explore and learn about strategic decision-making.

### Key Features
* **Multi-platform accessibility**: MindGames can be accessed across various platforms (mobile + web) by using embedded smart accounts on Xion.
* **Transparency & Fairness**: On-chain validation ensures provable fairness, guaranteeing that game outcomes are tamper-proof and transparent.
* **Tokenized Incentives**: Players can earn and stake tokens to unlock gameplay enhancements, adding a new level of engagement and excitement to the gaming experience.
* **Commit-reveal game structure**: Players make private moves, which are only revealed during the verification phase, ensuring a secure and trustworthy experience.
* **```GameLifecycle```**: A modular and extensible method for writing (game-theory) game logic, allowing for seamless integration and customization of games.

### Bonus
We plan to launch an NFT collection (free mint) as part of the MindGames platform launch where players can earn the NFTs simply by playing MindGames with friends. The art for the collection is ready to go but we want to create a valid launch plan and use it as an incentive for players to onboard. Art previews can be seen in [this X account](https://x.com/XionSenshi) and some details can be found in the [associated Gitbook](https://senshi.mindsetlabs.io).


## 6. Project Goals and Objectives
Design and develop a blockchain-based game-theory games platform that combines the engagement and entertainment of Jackbox-style games with the academic rigor of game theory, providing a unique tool for researchers, educators, and students to explore and learn about strategic decision-making, while also promoting fun and interactive social interactions.

### High-level Goals

- **Goal 1**: Improve current smart contracts (developed during Believathon) to be more generalized to different types of game-theory games (currently only rounds-based) as well as improve overall state machine of games within contracts. Minor UX improvements to ensure smooth onboarding for alpha/beta users.
- **Goal 2**: Market and onboard an initial user base for early access on Testnet.
- **Goal 3**: UI/UX enhancement for a smoother gaming experience and Xion mainnet deployment.
- **Goal 4**: Build an academia-focused dashboard for professors / instructors to use in classrooms.

## 7. Deliverables and Milestones
| Milestone | Description | Estimated Completion |
|-----------|------------|----------------------|
| UX Improvements | Improve game mechanics and user journey | March 2025 |
| UI Improvements | Create a new brand identity and user interface | March 2025 |
| Smart Contracts and Backend Updates | Improve existing game smart contracts and add events indexer | March 2025 |
| Game Expansion | Introduce additional games and integrate new mechanics | April 2025 |
| Mainnet Deployment | Full deployment of MindGames on the Xion mainnet | April 2025 |

## 8. Technical Implementation
We plan to use the same architecture and technology developed during the Xion Hackathon (Believathon), which provides a strong and modular foundation. 

- [View Docs](https://mindset-labs.github.io/tg-mindgames/)
- [View Deck](https://coreum-labs.up.railway.app/api/public/dl/_Jh6JUxj?inline=true)

### **Key Components:**
- **Smart Contracts**: Rust-based game framework optimized for Xion.  
- **Backend**: Websockets API + Indexer with SubQuery to provide real-time feedback. To be used primarily for frontend and UX support, however, the main game logic and functionality will be entirely on-chain.
- **Frontend**: Interactive UI, built as a React PWA (to replace Telegram Mini Apps) and browser support.
- **Xion Network Features**: Smart Accounts, Fee Grants, and underlying blockchain infrastructure.

## 9. Team
- **Faisal Al Tameemi** - Co-Founder, Smart Contract & Fintech Engineer  
- **Helwan Mandé** - Co-Founder, Full-Stack Developer & Game Designer
- **Additional Contributors** - TBD (primarily looking to add a UI/UX Designer for game art)

## 10. Budget Breakdown
| Item | Cost | Justification |
|------|------|--------------|
| Smart Contract Development | $7,000 | Finalizing and productionizing contracts |
| UI/UX Design | $3,000 | Improving user experience, game visuals and mechanics |
| Marketing & Community Growth | $5,000 | Onboarding new players and running incentives |
| Frontend Development | $7,000 | PWA Implementation |
| Technical Infrastructure | $3,000 | Hosting and maintenance costs |
| **Total Requested** | **$25,000** | - |

## 11. Impact and Metrics for Success
We will measure success using the following key performance indicators (KPIs):
- **User adoption**: Number of players onboarded (target: 5,000 active users by Q3 2025).  
- **Game interactions**: Number of games played and transactions recorded.
- **Revenue generation**: Growth in transaction fees and microtransactions.
- **Community engagement**: Telegram and X (Twitter) activity and growth.

## 12. Sustainability Plan
MindGames is designed for long-term sustainability through three primary revenue streams:
1. **Transaction fees**: A small fee per game transaction ensures a sustainable revenue model.
2. **Microtransactions**: Players can purchase in-game add-ons and special features.
3. **Premium game modes**: Exclusive games and staking mechanics for advanced users.

By leveraging a fair and transparent blockchain-powered gaming model, we aim to create an engaging and sustainable ecosystem for both social engagement and academic research.

---

### **Signature**  
Helwan Mandé  
Faisal Al Tameeni  
Tuesday, 4 February 2025
