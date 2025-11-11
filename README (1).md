# 🛍️ Amazon PPC Bulk File Editor

A powerful web-based tool for managing Amazon Sponsored Products campaigns in bulk. Edit keywords, bids, campaign settings, and more directly from your browser - no software installation required!

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
Visit the live app: **[https://magnifico2512.github.io/amazon-ppc-bulk-file-editor/](https://magnifico2512.github.io/amazon-ppc-bulk-file-editor/)**

### Option 2: Run Locally
1. Download `index.html`
2. Open it in your browser
3. That's it! No server needed.

## ✨ Features

### Core Functionality
- 📊 **Bulk Edit** - Modify multiple campaigns, ad groups, keywords, and products at once
- 📁 **CSV Import/Export** - Works with Amazon's bulksheet format
- 🔍 **Advanced Filtering** - Filter by campaign, portfolio, state, match type, and more
- 📝 **Track Changes** - See what's been modified before exporting
- 💾 **Auto-Save** - Never lose your work with automatic browser storage

### Keyword Management
- 🔑 **Keyword Search** - Search within ad groups to quickly find keywords
- ☑️ **Multi-Select** - Select multiple keywords with checkboxes
- ⚡ **Bulk Actions** - Pause or enable multiple keywords at once
- 🎯 **Target Checker** - Compare your keywords against reference lists

### Advanced Features
- 📂 **Portfolio Management** - Organize campaigns by portfolio
- 🔄 **Campaign Creation** - Create new campaigns with full structure
- 📈 **Performance Data** - View clicks, spend, sales, ACOS right in the table
- 🎨 **Visual Highlighting** - Color-coded rows show new/modified items
- 📋 **Reference Panel** - Compare current keywords against target lists

## 📖 How to Use

### Basic Workflow

1. **Upload Your Bulksheet**
   - Download your campaign data from Amazon Ads
   - Click "Upload CSV" in the app
   - Select your bulksheet file

2. **Make Your Changes**
   - Use tabs to navigate: Campaigns, Ad Groups, Keywords, etc.
   - Edit cells directly by clicking
   - Use filters to focus on specific items
   - Apply bulk actions as needed

3. **Export & Upload**
   - Click "Export Changes Only" to download modified items
   - Upload the exported file back to Amazon Ads
   - Review and apply changes in Amazon

### Keyword Search & Bulk Actions

1. **Expand an Ad Group** - Click the ▶ arrow next to any ad group
2. **Search Keywords** - Type in the search box to filter
3. **Select Keywords** - Use checkboxes to select specific keywords
4. **Apply Actions** - Click "Pause Selected" or "Enable Selected"

### Using the Target Checker

1. Open the **Reference Panel** (toggle button in toolbar)
2. Paste your target keywords list
3. Keywords in your campaigns that match will be highlighted in orange
4. See which keywords exist, which are missing, and their status

## 🎯 Use Cases

- **Bulk Bid Adjustments** - Update bids for multiple keywords at once
- **Campaign Restructuring** - Move keywords between ad groups
- **Keyword Cleanup** - Find and pause underperforming keywords
- **New Campaign Creation** - Build complete campaign structures
- **Portfolio Management** - Organize campaigns into portfolios
- **Seasonal Adjustments** - Quickly enable/pause seasonal keywords

## 🔧 Technical Details

- **No Backend Required** - Runs entirely in your browser
- **Data Privacy** - Your data never leaves your computer
- **Built With** - React, TailwindCSS, PapaParse
- **File Format** - Amazon Sponsored Products bulksheet (CSV)
- **Browser Support** - Chrome, Firefox, Safari, Edge (latest versions)

## 📋 Supported Entity Types

- ✅ Campaigns
- ✅ Ad Groups
- ✅ Keywords
- ✅ Negative Keywords (Campaign & Ad Group level)
- ✅ Product Ads
- ✅ Product Targeting
- ✅ Campaign Placement Adjustments

## 🆘 Troubleshooting

**Problem: Changes aren't saving**
- Solution: Check browser console for errors. Try clearing browser cache.

**Problem: CSV won't upload**
- Solution: Ensure it's an Amazon Sponsored Products bulksheet. Check file isn't corrupted.

**Problem: Can't find specific keywords**
- Solution: Use the search function within expanded ad groups. Check active filters.

**Problem: Export is empty**
- Solution: Make sure you've made changes. Modified rows should be highlighted in yellow.

## 🔄 Update History

### Version 3.0 (Latest)
- ✨ Added keyword search within ad groups
- ✨ Added multi-select checkboxes for keywords
- ✨ Added bulk pause/enable actions
- 🐛 Improved search filtering

### Version 2.0
- ✨ Added campaign creation workflow
- ✨ Added target checker reference panel
- ✨ Added portfolio filtering
- 🐛 Fixed bid adjustment calculations

### Version 1.0
- 🎉 Initial release
- ✨ Basic bulk editing functionality
- ✨ CSV import/export
- ✨ Change tracking

## 📝 License

MIT License - feel free to use and modify for your needs.

## 🤝 Contributing

This is a personal tool, but suggestions and bug reports are welcome! Open an issue on GitHub.

## ⚠️ Disclaimer

This tool is not affiliated with Amazon. Always review changes carefully before uploading to Amazon Ads. Test with small batches first. The author is not responsible for any issues arising from use of this tool.

## 📧 Support

For questions or issues, please open a GitHub issue or contact the repository owner.

---

**Happy Optimizing!** 🚀
