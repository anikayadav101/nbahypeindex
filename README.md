# NBA Hype Index Leaderboard

A comprehensive analysis tool that measures the relationship between social media hype and on-court performance for NBA players.

## 🏀 About

This website compares NBA players' **Hype Index** (based on Reddit sentiment analysis) against their **Performance Index** (based on on-court statistics) to identify who is overrated or underrated.

## 📊 Features

- **Interactive Table**: Sort and search through 5,095+ NBA players
- **Hype vs Performance**: Visual comparison bars for each player
- **Expandable Player Cards**: Click any row to see detailed stats
- **Real Data**: Based on actual Reddit sentiment analysis and NBA statistics

## 🔗 Live Website

Visit the live site: [Your GitHub Pages URL will appear here after deployment]

## 📈 Methodology

### Performance Index
- Based on PTS, REB, AST, STL, BLK
- Normalized using MinMaxScaler (0-1 scale)
- Career averages for all players

### Hype Index
- Reddit sentiment analysis using BERT-based multilingual model
- Real Reddit posts, comments, and engagement
- Based on actual Reddit discussions (r/nba, r/basketball, etc.)

### Hype Gap
- **Overrated**: Hype > Performance (positive gap)
- **Underrated**: Performance > Hype (negative gap)
- **Balanced**: Hype ≈ Performance (near zero gap)

## 🛠️ Technical Details

- **Frontend**: HTML, CSS (Tailwind), JavaScript
- **Data**: JSON file with 5,095+ players
- **Hosting**: GitHub Pages

## 📝 Data Sources

- 5,095 total NBA players
- 97.9% real NBA statistics
- Reddit API - Real posts and sentiment analysis

---

Built with ❤️ for NBA fans
