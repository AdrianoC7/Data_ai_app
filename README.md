# AskAVA AI

A modern AI-powered writing assistant specifically designed for food service analytics and restaurant data insights. This front-end application provides an intuitive interface for generating data-driven content with advanced analytics capabilities.

## 🚀 Features

### AI Writing Assistant
- **Smart Content Generation**: Generate tailored content for blogs, emails, ad copy, and social media posts
- **Multiple Writing Types**: Blog posts, email templates, advertising copy, and social media content
- **Tone Control**: Adjustable tone slider from professional to casual
- **Content Length Options**: Short, medium, and long content generation
- **Real-time Suggestions**: Context-aware writing suggestions and improvements

### DataDump Upload System
- **Multi-format Support**: Upload JSON, Excel (.xlsx, .xls), and CSV files
- **Drag & Drop Interface**: Intuitive file upload with visual feedback
- **File Management**: Add, remove, and manage multiple data files
- **Data Integration**: Import analytics data directly into content generation

### Modern Interface
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Rich Text Editor**: Full-featured editor with formatting toolbar
- **Real-time Word Count**: Live tracking of content length
- **Professional UI**: Clean, modern design with smooth animations

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with custom properties and responsive design
- **Vanilla JavaScript**: Pure JavaScript for optimal performance
- **File API**: Modern browser file handling capabilities

## 📋 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/cookfast-analytics-ai.git
   cd cookfast-analytics-ai
   ```

2. **Open the application**
   ```bash
   # Simply open the HTML file in your browser
   open index.html
   # or
   python -m http.server 8000  # For local development server
   ```

3. **Start using the application**
   - Open your browser and navigate to the file
   - Begin writing or upload data files to get started

## 💡 Usage

### Basic Content Creation
1. Select your desired **Writing Type** (Blog Post, Email, Ad Copy, Social Post)
2. Adjust the **Tone** slider based on your target audience
3. Choose your preferred **Content Length**
4. Click **"Generate Content"** to create AI-powered text
5. Use the **AI Suggestions** to enhance your content

### Data Integration
1. Click on the **DataDump** section in the right sidebar
2. Upload your data files by:
   - Dragging and dropping files onto the upload area
   - Clicking "Browse Files" to select files manually
3. Supported formats: JSON, CSV, Excel (.xlsx, .xls)
4. Click **"Import Data"** to integrate analytics into your content

### Content Editing
- Use the formatting toolbar for text styling
- Monitor word count in real-time
- Click on AI suggestions to add them to your content
- Save your work using browser functionality

## 🎯 Use Cases

### Restaurant Analytics
- Generate reports on kitchen efficiency metrics
- Create marketing content based on performance data
- Draft emails with data-driven insights
- Produce social media content highlighting analytics results

### Food Service Industry
- Inventory management reports
- Customer behavior analysis summaries
- Operational efficiency documentation
- Marketing campaigns with statistical backing

## 🔧 Customization

### Styling
The application uses CSS custom properties for easy theming:

```css
:root {
    --primary-color: #6c5ce7;
    --secondary-color: #a29bfe;
    --text-color: #2d3436;
    --light-color: #f5f6fa;
    --border-color: #dfe6e9;
    --success-color: #00b894;
    --warning-color: #fdcb6e;
}
```

### Content Templates
Modify the `aiResponses` object in the JavaScript to customize AI-generated content:

```javascript
const aiResponses = {
    blogPost: [
        "Your custom blog post templates...",
    ],
    email: [
        "Your custom email templates...",
    ],
    // Add more templates
};
```

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 🚦 Current Limitations

- **Demo Mode**: AI responses are simulated for demonstration purposes
- **Local Storage**: No persistent data storage (files are processed in memory)
- **File Processing**: Actual data analysis features require backend integration

## 🛣️ Roadmap

### Version 2.0
- [ ] Integration with real AI APIs (OpenAI, Google AI)
- [ ] Backend data processing capabilities
- [ ] User authentication and project management
- [ ] Advanced data visualization features
- [ ] Export functionality (PDF, Word, HTML)

### Version 2.1
- [ ] Collaborative editing features
- [ ] Template marketplace
- [ ] Advanced analytics dashboard
- [ ] Real-time data synchronization

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow consistent code formatting
- Add comments for complex functions
- Test across multiple browsers
- Ensure responsive design compatibility

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/your-profile)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Inspired by modern AI writing assistants
- Built with accessibility and user experience in mind
- Designed for the food service analytics industry

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/your-username/cookfast-analytics-ai/issues) page
2. Create a new issue with detailed information
3. Contact the maintainer directly

---

**⭐ Star this repository if you find it helpful!**

---

*Last updated: June 2025*
