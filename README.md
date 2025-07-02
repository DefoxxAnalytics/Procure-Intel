# VSTX Analytics Dashboard

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-2.0.0-green.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![Chart.js](https://img.shields.io/badge/Chart.js-4.4.0-ff6384.svg)

A powerful, enterprise-grade procurement analytics platform that transforms raw spending data into actionable strategic insights. Built with modern web technologies, this comprehensive dashboard empowers procurement professionals to identify cost-saving opportunities, mitigate risks, and drive data-driven decision-making.

## 🚀 Live Demo

[View Live Demo](https://your-github-username.github.io/vstx-analytics-dashboard/)

## 📸 Screenshots

### Light Theme
![Dashboard Light Theme](screenshots/dashboard-light.png)

### Dark Theme
![Dashboard Dark Theme](screenshots/dashboard-dark.png)

## ✨ Key Features

### 🎯 Core Analytics Modules

1. **Executive Overview**
   - Real-time KPI dashboards
   - Spend trend visualization
   - Category performance metrics
   - Interactive charts with drill-down capabilities

2. **Category Intelligence**
   - Multi-level category analysis
   - Subcategory drill-down with modal views
   - Risk concentration assessment
   - Supplier distribution analysis

3. **Supplier Analytics**
   - Performance benchmarking
   - Spend distribution analysis
   - Top supplier identification
   - Supplier risk profiling

4. **Pareto Analysis**
   - 80/20 spend concentration insights
   - Strategic supplier identification
   - Optimization opportunity detection
   - Visual Pareto charts

5. **Spend Stratification**
   - Volume-based segmentation
   - Sourcing strategy alignment
   - Spend band analysis
   - Risk assessment by spend levels

6. **Seasonality Intelligence**
   - Pattern recognition algorithms
   - Demand forecasting capabilities
   - Budget optimization recommendations
   - Seasonal trend visualization

7. **Tail Spend Analysis**
   - Vendor consolidation opportunities
   - 15% average savings potential identification
   - Implementation roadmap generation
   - Cross-category opportunity analysis

8. **Advanced Features** (Under Review)
   - Predictive Analytics with 12-month forecasting
   - Maverick Spend & Compliance monitoring
   - Contract Optimization Intelligence

### 🎨 User Experience Features

- **🌓 Theme Toggle**: Seamless switching between light and dark modes
- **🔍 Customizable Filters**: Build your own filter pane from available data fields
- **📊 Interactive Visualizations**: Powered by Chart.js with responsive design
- **💾 Persistent Preferences**: Saves theme and filter configurations
- **📱 Mobile Responsive**: Optimized for all device sizes
- **🚀 Client-Side Processing**: Fast, secure data analysis without server uploads

## 🛠️ Technology Stack

- **Frontend**: Pure JavaScript (ES6+), HTML5, CSS3
- **Charts**: Chart.js 4.4.0
- **Data Processing**: PapaParse 5.4.1 (CSV), XLSX 0.18.5 (Excel)
- **Styling**: CSS Variables for theme management
- **Icons**: Native emoji support
- **Fonts**: Google Fonts (Inter)

## 📋 Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required
- JavaScript must be enabled

## 🚀 Getting Started

### Option 1: GitHub Pages Deployment (Recommended)

1. Fork this repository
2. Go to Settings → Pages
3. Select source: Deploy from a branch
4. Select branch: main (or master)
5. Select folder: / (root)
6. Click Save
7. Your dashboard will be available at: `https://[your-username].github.io/[repository-name]/`

### Option 2: Local Development

1. Clone the repository:
```bash
git clone https://github.com/your-username/vstx-analytics-dashboard.git
cd vstx-analytics-dashboard
```

2. Open in a local server:
   - Using Python:
     ```bash
     python -m http.server 8000
     ```
   - Using Node.js:
     ```bash
     npx http-server
     ```
   - Or simply open `vstx-etn_pro.html` in your browser

## 📊 Data Format Requirements

### CSV Format
Your CSV file should include the following columns (case-insensitive):
- **supplier** or **vendor**: Supplier/vendor name
- **category**: Primary category
- **subcategory**: Secondary category
- **amount**: Spend amount (numeric)
- **date**: Transaction date (MM/DD/YYYY or YYYY-MM-DD)
- **location**: Geographic location (optional)
- **businessUnit**: Business unit (optional)
- Additional columns will be available for custom filters

### Excel Format
Same column requirements as CSV. The dashboard reads the first sheet by default.

### Sample Data Structure
```csv
Supplier,Category,Subcategory,Amount,Date,Location,BusinessUnit
Acme Corp,IT,Software,25000,01/15/2024,New York,Operations
Global Tech,IT,Hardware,18500,01/20/2024,London,Marketing
```

## 🎮 Usage Guide

### 1. Initial Setup
- Open the dashboard in your browser
- Choose your preferred theme (light/dark) from the intro screen
- Click "Get Started" or check "Don't show this again" for future visits

### 2. Upload Data
- Click the upload area or drag and drop your file
- Supported formats: CSV, XLSX, XLS
- Wait for processing to complete

### 3. Customize Filters
- Click "⚙️ Customize Filters" button
- Select fields from available columns
- Arrange filters as needed
- Apply changes

### 4. Navigate Analytics
- Use navigation tabs to switch between different analytics views
- Click on charts for detailed information
- Use filters to refine data analysis
- Export insights as needed

### 5. Theme Management
- Click the theme toggle button (🌙/☀️) at any time
- Theme preference is saved automatically

## ⚙️ Configuration

### Default Filters
If no custom filters are configured, the dashboard uses:
- Category
- Subcategory  
- Location

### Filter Customization
- Core fields (marked) are required for dashboard functionality
- Additional fields can be added based on your data
- Configuration is saved in browser localStorage

### Theme Variables
The dashboard uses CSS custom properties for theming. Key variables include:
- `--bg-primary`: Main background color
- `--text-primary`: Main text color
- `--accent-primary`: Primary accent color
- And many more...

## 🔧 Troubleshooting

### Common Issues

1. **File Upload Fails**
   - Ensure file size is under 50MB
   - Check that required columns are present
   - Verify date format matches expected format

2. **Charts Not Displaying**
   - Ensure JavaScript is enabled
   - Check browser console for errors
   - Verify data has been processed correctly

3. **Filters Not Working**
   - Rebuild filters using the customize option
   - Check that filtered fields contain data
   - Clear browser cache if issues persist

4. **Theme Not Saving**
   - Enable localStorage in browser settings
   - Check for private/incognito mode
   - Clear site data and try again

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Maintain existing code style
- Add comments for complex logic
- Test across different browsers
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Chart.js](https://www.chartjs.org/) for powerful charting capabilities
- [PapaParse](https://www.papaparse.com/) for CSV parsing
- [SheetJS](https://sheetjs.com/) for Excel file handling
- [Google Fonts](https://fonts.google.com/) for the Inter font family

## 📞 Support

For support, please:
- Check the [Issues](https://github.com/your-username/vstx-analytics-dashboard/issues) page
- Review closed issues for solutions
- Create a new issue with detailed information

## 🗺️ Roadmap

### Version 2.1 (Planned)
- [ ] Export functionality for all charts
- [ ] Custom color schemes
- [ ] Multi-language support
- [ ] Advanced data validation

### Version 3.0 (Future)
- [ ] Real-time data connections
- [ ] Collaborative features
- [ ] Advanced ML predictions
- [ ] API integration support

---

Built with ❤️ for the procurement analytics community