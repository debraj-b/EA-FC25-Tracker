# 🏆 EA FC25 Player Auction Tracker

A comprehensive web-based tool for tracking player auctions in EA FC25 (FIFA 25). Manage player ownership, track auction bids, monitor credits, and export detailed auction results.

## 🚀 Live Demo

**[View Live Demo](https://debraj-b.github.io/EA-FC25-Tracker/auction_tracker.html)**

## ✨ Features

### 🎯 Player Management
- **Complete Player Database**: Pre-loaded with top EA FC25 players including ratings and positions
- **Real-time Search & Filtering**: Filter by player name, position, or auction status
- **Status Tracking**: Track players as Available, Bidding, or Sold

### 💰 Credit System
- **Individual Player Credits**: Each auction participant gets their own credit tracker
- **Automatic Credit Management**: Credits are automatically deducted/refunded when players are bought/sold
- **Spending Controls**: Input validation prevents overspending
- **Real-time Balance Updates**: See available credits update instantly

### 📊 Analytics & Export
- **Live Statistics**: Total players, available count, sold count, and total auction value
- **Detailed Export Options**: 
  - Export all player data
  - Generate comprehensive auction results report
- **Owner Summary**: See who owns which players and their spending patterns

### 🎨 User Experience
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Intuitive Interface**: Clean, modern design with easy-to-use controls
- **Persistent Data**: Uses local storage to maintain state between sessions
- **Batch Operations**: Reset all players or individual transactions

## 🛠️ Technical Features

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **CSV Data Integration**: Loads player data from CSV files
- **Local Storage**: Automatic data persistence
- **Responsive Grid Layout**: Adapts to different screen sizes
- **Modern UI**: Gradient backgrounds, smooth animations, and professional styling

## 📁 Project Structure

```
EA-FC25-Tracker/
├── auction_tracker.html      # Main application file
├── ea_fc25_top_players.csv  # Player database
└── README.md                # This file
```

## 🚀 Getting Started

### Option 1: Use the Live Version
Simply visit: https://debraj-b.github.io/EA-FC25-Tracker/auction_tracker.html

### Option 2: Run Locally
1. Clone or download this repository
2. Open `auction_tracker.html` in any modern web browser
3. The CSV file will be automatically loaded

## 🎮 How to Use

### Setting Up Players
1. **Add Player Names**: Click on the credit cards to customize player names
2. **Set Starting Credits**: Default is 100 credits per player (adjustable)

### Managing Auctions
1. **Search Players**: Use the search bar to find specific players
2. **Filter by Position**: Select position from dropdown (GK, CB, ST, etc.)
3. **Set Ownership**: Select owner from dropdown for each player
4. **Add Purchase Price**: Enter the auction price
5. **Track Status**: Status automatically updates (Available → Sold)

### Credit Management
- **Spend Credits**: Enter amount and click "Spend"
- **Add Credits**: Enter amount and click "Add" 
- **Reset Credits**: Reset individual player credits to 100
- **Automatic Deduction**: Credits automatically deducted when players are purchased

### Exporting Results
- **Export All Data**: Download complete player database with current state
- **Export Auction Results**: Generate detailed auction report with:
  - Owner summary with spending and remaining credits
  - Detailed player ownership breakdown
  - Top purchases ranking

## 🔧 Customization

### Adding More Players
Edit `ea_fc25_top_players.csv` with the format:
```csv
Player Name,Rating,Position,Owner,Purchase Price,Status
Kylian Mbappe,91,ST,,,Available
```

### Changing Default Credits
Modify the `auctionPlayers` array in the JavaScript code:
```javascript
let auctionPlayers = [
    { id: 1, name: 'Player 1', credits: 200 }, // Change 100 to desired amount
    // ... more players
];
```

## 📱 Mobile Support

The application is fully responsive and works great on:
- 📱 Mobile phones (iOS/Android)
- 📱 Tablets (iPad, Android tablets)
- 💻 Desktop computers
- 🖥️ Large screens

## 🔒 Data Privacy

- All data is stored locally in your browser
- No personal information is collected or transmitted
- Works completely offline after initial load

## 🤝 Contributing

Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Share improvements

## 📄 License

This project is open source and available under the MIT License.

---

**Created for EA FC25 auction enthusiasts** 🎮⚽
