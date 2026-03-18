# energy-calculatorv3
Free Industrial Energy Inflation Calculator - 24-month cost projections for commercial operations
# Free Industrial Energy Inflation Calculator

🔥 **Live Demo:** https://id34mining.github.io/energy-calculator/

A free, open-source tool that shows commercial and industrial businesses exactly how energy inflation will impact their costs over the next 24 months.

## 🎯 What It Does

- **24-Month Cost Projections** - See what you'll actually pay as rates keep rising
- **Electric, Gas, or Both** - Analyze electricity, natural gas, or combined energy costs
- **Real Market Data** - Based on actual 2026 commercial energy trends
- **Instant Calculations** - No signup required, results in seconds
- **Lead Generation** - Connects qualified prospects with energy specialists

## 💡 Who It's For

- **Commercial operations** (retail, hospitality, multi-location businesses)
- **Industrial facilities** (manufacturing, data centers, warehouses)
- **Franchise operations** (restaurants, service chains)
- **High-usage clients** (any business with significant energy consumption)

## 🚀 Features

- ✅ All 50 US states
- ✅ Real-time calculations
- ✅ Interactive charts (Chart.js)
- ✅ Mobile responsive
- ✅ Single HTML file (easy deployment)
- ✅ No backend required
- ✅ 100% free forever

## 📊 Technology Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Charts:** Chart.js 4.4.0
- **Email:** Web3Forms API (unlimited free tier)
- **Hosting:** GitHub Pages (free)
- **Fonts:** Google Fonts (Work Sans, JetBrains Mono)

## 🔧 Setup & Deployment

### Quick Deploy to GitHub Pages:

1. Fork this repository
2. Go to Settings → Pages
3. Set Source to "main" branch
4. Your calculator will be live at `https://yourusername.github.io/energy-calculator/`

### Local Development:

```bash
# Clone the repository
git clone https://github.com/id34mining/energy-calculator.git

# Open in browser
open index.html
```

No build process needed - it's a single HTML file!

## 📧 Email Configuration

The calculator uses Web3Forms for email notifications. To configure:

1. Get your access key at https://web3forms.com
2. Find line 759 in `index.html`
3. Replace the access key with yours
4. Update `RECIPIENT_EMAIL` to your email

```javascript
const WEB3FORMS_ACCESS_KEY = 'your-access-key-here';
const RECIPIENT_EMAIL = 'your-email@example.com';
```

## 🎨 Customization

### Update Calculation Rate:
```javascript
// Line 780 - Adjust monthly inflation rate
const monthlyInflation = 0.0117; // 15% annual
```

### Modify Qualification Thresholds:
```javascript
// Line 762-772 - Set minimum usage for qualified leads
const QUALIFICATION = {
    electric: {
        minMonthlyKwh: 165000,  // ~2MW annual
        minAnnualSpend: 100000
    },
    gas: {
        minMonthlyTherms: 10000,
        minAnnualSpend: 50000
    }
};
```

### Change Colors:
```css
/* Line 17-26 - CSS variables */
:root {
    --accent-danger: #ef4444;   /* Red alerts */
    --accent-success: #10b981;  /* Green savings */
    --accent-info: #3b82f6;     /* Blue accents */
}
```

## 📈 How It Works

1. User enters their energy usage and current rates
2. Calculator projects costs over 24 months (15% annual inflation)
3. Shows locked rate vs. projected costs
4. Generates detailed breakdown table
5. Qualifies lead based on usage thresholds
6. Sends email notification with all data

## 🔒 Privacy & Data

- No cookies or tracking
- All calculations happen in browser
- No data stored on servers
- Email only sent if user submits contact form
- Fully GDPR compliant

## 📱 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ❌ IE11 (not supported)

## 🤝 Contributing

This is an open-source project. Contributions welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 💼 Business Use

This calculator is designed to:
- Educate businesses about energy cost trends
- Generate qualified leads for energy consultants
- Provide data-driven cost projections
- Connect high-usage clients with energy specialists

Built for commercial energy brokers, consultants, and businesses serious about managing energy costs.

## 🌟 Key Differentiators

- **Educational First** - No sales pitch, just data
- **White Paper Tone** - Professional analysis, not marketing
- **No Login Required** - Instant access to calculations
- **Complete Transparency** - Open source, see exactly how it works
- **Truly Free** - No hidden costs, no upgrades, no limits

## 📞 Contact

For questions about this calculator or energy consulting services:
- Email: id34mining@gmail.com
- Calculator: https://id34mining.github.io/energy-calculator/

---

**Built with AI-powered analysis | Designed for commercial & industrial energy management**

*Projections based on current market trends. Actual costs may vary. For estimation purposes only.*
