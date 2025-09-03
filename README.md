# NBA Analytics Hub 🏀

A comprehensive, real-time NBA analytics web application that combines game statistics, sentiment analysis, highlight discovery, and AI-powered predictions into a single, modern dashboard.

![NBA Analytics Hub](https://img.shields.io/badge/NBA-Analytics%20Hub-blue?style=for-the-badge&logo=basketball)
![Poe Canvas](https://img.shields.io/badge/Poe-Canvas%20App-purple?style=for-the-badge)
![AI Powered](https://img.shields.io/badge/AI-Powered-green?style=for-the-badge)

## 🌟 Features

### 📊 **Interactive Dashboard**
- Real-time NBA statistics overview
- Quick access to all analytics features
- Live data updates and status monitoring
- Responsive design for all devices

### 🏀 **Game Analysis**
- Analyze recent NBA games with customizable date ranges
- Team-focused analysis (Lakers, Warriors, Celtics, or all teams)
- Performance trends and statistical insights
- Injury reports and roster updates
- AI-powered game predictions

### 💭 **Lakers Sentiment Analysis**
- Monitor Lakers fan sentiment across social media
- Real-time sentiment tracking from Reddit and other platforms
- Sentiment scoring and trend analysis
- Fan mood indicators and key discussion topics
- Historical sentiment comparison

### 🎥 **NBA Highlights Discovery**
- Search for NBA highlight videos with advanced filters
- Video duration and quality preferences
- AI-powered highlight analysis and ranking
- Trending moments and viral plays
- Direct video links and metadata

### 🔮 **Game Predictions**
- AI-powered game outcome predictions
- Head-to-head analysis and historical data
- Key player matchup insights
- Confidence levels and reasoning
- Statistical projections and betting insights

## 🚀 Quick Start

### Prerequisites
- Access to [Poe Canvas](https://poe.com/) environment
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation
1. Copy the HTML code from this repository
2. Paste it into a new Poe Canvas application
3. The app will automatically initialize with all features ready to use

### First Steps
1. **Explore the Dashboard**: Get an overview of all available features
2. **Analyze Games**: Click "Analyze Games" to get recent NBA statistics
3. **Check Sentiment**: Monitor Lakers fan mood with sentiment analysis
4. **Find Highlights**: Search for the best NBA highlight videos
5. **Make Predictions**: Get AI predictions for upcoming games

## 📱 Usage Guide

### Dashboard Navigation
- **Tab Interface**: Switch between Dashboard, Games, Sentiment, Highlights, and Predictions
- **Quick Actions**: Use dashboard cards for instant access to features
- **Real-time Stats**: Monitor live analytics and update times

### Game Analysis
Select date range (7, 14, or 30 days)
Choose team focus (All teams, Lakers, Warriors, Celtics)
Click "Analyze Games"
View comprehensive analysis results

### Sentiment Analysis
Select data sources (Reddit, Social Media)
Choose time period (24 hours, 7 days, 30 days)
Click "Analyze Sentiment"
Review sentiment scores and fan mood indicators
### Highlights Search
Enter search query (e.g., "NBA highlights", "Lakers dunks")
Select video duration preference
Set results limit (5-20 videos)
Click "Search Highlights"
Browse curated highlight recommendations

### Game Predictions
Enter home team name
Enter away team name
Select analysis type (Quick, Detailed, Advanced)
Click "Make Prediction"
Review AI-powered prediction results
## 🛠 Technical Details

### Built With
- **HTML5**: Semantic markup and structure
- **TailwindCSS**: Responsive styling and dark mode support
- **JavaScript**: Interactive functionality and API integration
- **Poe Embed API**: AI-powered analysis and predictions
- **Chart.js**: Data visualization (ready for integration)
- **Font Awesome**: Professional icons and UI elements

### Architecture
├── Frontend (HTML/CSS/JS)
│ ├── Responsive Design System
│ ├── Tab-based Navigation
│ ├── Real-time Updates
│ └── Dark/Light Mode
│
├── AI Integration (Poe API)
│ ├── Claude-Sonnet-4 Analysis
│ ├── Streaming Responses
│ ├── Error Handling
│ └── Context Management
│
└── Data Processing
├── Sentiment Analysis
├── Game Statistics
├── Highlight Curation
└── Prediction Algorithms
### Key Components

#### AI Analysis Engine
- **Primary Bot**: Claude-Sonnet-4 for comprehensive NBA analysis
- **Streaming**: Real-time response updates for better UX
- **Context Awareness**: Maintains conversation context across queries
- **Error Recovery**: Graceful handling of API failures

#### Responsive Design
- **Mobile-First**: Optimized for touch and small screens
- **Accessibility**: WCAG compliant design patterns
- **Performance**: Optimized loading and smooth animations
- **Cross-Browser**: Compatible with all modern browsers

## 📊 Data Sources

### NBA Statistics
- Real-time game data and scores
- Player performance metrics
- Team statistics and standings
- Historical game results

### Sentiment Data
- Reddit discussions (r/lakers, r/nba, r/basketball)
- Social media mentions and reactions
- Fan forum discussions
- News article sentiment

### Highlight Sources
- YouTube NBA channels
- Official team highlights
- Fan-created compilations
- Viral moment tracking

## 🔧 Configuration

### Customization Options
```javascript
// Modify team focus options
const TEAMS = ['lakers', 'warriors', 'celtics', 'heat', 'bulls'];

// Adjust analysis parameters
const ANALYSIS_SETTINGS = {
    defaultDateRange: 30,
    sentimentSources: ['reddit', 'twitter'],
    highlightQuality: 'high'
};

// Theme customization
const THEME_CONFIG = {
    primaryColor: '#5D5CDE',
    lakersColors: ['#fbbf24', '#7c2d12'],
    darkMode: 'auto'
};
