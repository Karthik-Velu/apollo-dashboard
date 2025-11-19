# Apollo Dashboard

A standalone compliance and reporting dashboard for Apollo Agriculture transaction monitoring.

## Overview

This dashboard provides comprehensive reporting capabilities including:
- **Compliance & Dynamic Reporting** - Interactive charts and visualizations
- **PMA (Portfolio Monitoring Agent) Reports** - Monthly monitoring letters with collection efficiency metrics and shortfall bucket distributions
- **Cash Manager Reports** - Investor reports with cash flow analysis, waterfall structures, and performance metrics

## Features

- Collection Efficiency tracking (Current Month and Cumulative)
- Shortfall Bucket Distribution analysis
- Interactive charts and visualizations
- PDF report generation for PMA and Cash Manager reports
- Real-time data updates

## Usage

Simply open `index.html` in a web browser. The dashboard will load directly to the Reports page.

All dependencies are loaded from CDNs, so no local installation is required.

## Reports Included

1. **PMA Report** - Portfolio Monitoring Agent Letter with:
   - Collection Efficiency metrics
   - Shortfall Bucket Distribution
   - Concentration limits validation
   - Collections reconciliation

2. **Cash Manager Report** - Investor Report with:
   - Cash flow summaries
   - Priority of payments waterfall
   - Credit enhancement tracking
   - Covenant compliance tests
   - Collection Efficiency and Shortfall metrics

## Technical Details

- Built with vanilla JavaScript
- Chart.js for visualizations
- Tailwind CSS for styling
- jsPDF for PDF generation
- All dependencies loaded via CDN

