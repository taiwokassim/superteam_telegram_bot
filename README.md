# Superteam Earn Telegram Bot


A production-ready Telegram bot that keeps Superteam Earn users updated with personalized alerts whenever new bounties or projects are published.

## 🚀 Features

- **Smart Filtering**: Notifications based on USD value range, listing type (bounties/projects), and selected skills
- **Intuitive Interface**: Smart library navigation with urgency indicators and automated cleanup
- **User Menu Integration**: Seamlessly accessible from Superteam Earn's user menu
- **Personalized Notifications**: User ID context passing for tailored experiences
- **12-Hour Delay**: Notifications sent 12 hours after listing publication as specified
- **Complete Notification Format**: Includes title, sponsor, reward details, deadline, and UTM-tracked links
- **Compensation Handling**: Supports fixed amounts, variable compensation, and salary ranges
- **Production Ready**: Deployed on Railway with PostgreSQL database and webhook integration

## 📋 Requirements Met

✅ **Personalized Notifications**: Based on geography, USD value, skills, and listing type  
✅ **User Menu Integration**: Direct link from Superteam Earn (PR #1102)  
✅ **Complete Notification Content**: All required fields included  
✅ **12-Hour Trigger**: Automated notification scheduling  
✅ **TypeScript + Node.js**: Built with required tech stack  
✅ **Production Deployment**: Live on Railway with health monitoring  


### Prerequisites
- Node.js 18+
- pnpm
- PostgreSQL database
- Telegram Bot Token

### Installation
```bash
git clone https://github.com/taiwokassim/superteam_telegram_bot.git
cd superteam_telegram_bot
pnpm install
cp .env.example .env
pnpm prisma generate
pnpm prisma db push

