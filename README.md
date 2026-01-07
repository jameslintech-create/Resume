# Resume with AI Assistant

A professional, responsive resume website with integrated AI assistant capabilities for resume optimization and career advice.

## Features

### 📄 Resume Display
- Clean, modern, and professional design
- Fully responsive layout (desktop, tablet, mobile)
- Beautiful gradient backgrounds and animations
- Optimized for all screen sizes

### 📥 PDF Generation
- One-click PDF generation
- High-quality, print-ready output
- Compact layout with proper formatting
- Clickable hyperlinks for email and LinkedIn
- Automatic text wrapping and page breaks

### 🤖 AI Assistant
- **Resume Optimization**: Get AI-powered suggestions to improve your resume
- **Content Rewriting**: Help rewrite and enhance job descriptions
- **Q&A Support**: Ask questions about your resume and career
- **Smart Analysis**: Receive personalized recommendations based on your resume content

## Getting Started

### Basic Usage

1. **View Resume**: Simply open `index.html` in your web browser
2. **Generate PDF**: Click the "📄 Generate PDF" button to download a PDF version
3. **Use AI Assistant**: Click the "🤖 AI Assistant" button to access AI features

### AI Assistant Setup

#### Step 1: Get OpenAI API Key

1. Visit [OpenAI Platform](https://platform.openai.com/api-keys)
2. Sign up or log in to your OpenAI account
3. Navigate to API Keys section
4. Click "Create new secret key"
5. Copy your API key (starts with `sk-`)

#### Step 2: Configure API Key

1. Open the resume website
2. Click the "🤖 AI Assistant" button
3. Click "Configure API Key" at the bottom of the chat
4. Paste your OpenAI API key
5. Click "Save API Key"

**Note**: Your API key is stored locally in your browser and never sent to any server except OpenAI's API.

#### Step 3: Start Using AI Assistant

Once configured, you can ask questions like:

- "How can I improve my resume?"
- "Rewrite my job description for the Indeed position"
- "What skills should I highlight?"
- "Suggest improvements for my summary section"
- "Help me optimize my experience descriptions"

## Technical Details

### Technologies Used

- **HTML5/CSS3**: Modern web standards
- **JavaScript**: Vanilla JS for interactivity
- **jsPDF**: PDF generation library
- **OpenAI API**: GPT-3.5-turbo for AI features

### Browser Compatibility

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

### Privacy & Security

- **Local Storage**: API keys are stored only in your browser's local storage
- **No Server**: All processing happens client-side
- **Direct API Calls**: AI requests go directly from your browser to OpenAI
- **No Data Collection**: Your resume data is never sent to any third-party servers

## File Structure

```
Resume/
├── index.html          # Main resume file (single file application)
└── README.md           # This file
```

## Customization

### Updating Resume Content

Edit the HTML content in `index.html`:

- **Personal Information**: Update name, location, and contact details
- **Summary**: Modify the summary section
- **Experience**: Add or update work experience
- **Education**: Update education details
- **Skills**: Modify tech stack and skills

### Styling

All styles are embedded in the `<style>` section of `index.html`. You can customize:

- Colors and gradients
- Fonts and typography
- Spacing and layout
- Responsive breakpoints

### AI Assistant Customization

The AI assistant uses GPT-3.5-turbo model. You can modify:

- **Model**: Change to `gpt-4` in the JavaScript code (requires GPT-4 access)
- **Temperature**: Adjust creativity level (0.7 is default)
- **Max Tokens**: Change response length (500 is default)
- **System Prompt**: Customize the AI's behavior

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main`)
4. Your resume will be available at `https://yourusername.github.io/Resume/`

### Other Hosting Options

- **Netlify**: Drag and drop the `index.html` file
- **Vercel**: Connect your GitHub repository
- **Any Static Hosting**: Upload `index.html` to any web server

## Troubleshooting

### PDF Generation Issues

- **Slow Generation**: Try using a modern browser with good performance
- **Missing Content**: Ensure all content is visible before generating PDF
- **Formatting Issues**: Check browser console for errors

### AI Assistant Issues

- **API Key Not Working**: 
  - Verify your API key is correct
  - Check if you have credits in your OpenAI account
  - Ensure the API key has proper permissions
  
- **No Response**:
  - Check browser console for errors
  - Verify internet connection
  - Check OpenAI API status

- **Rate Limits**:
  - OpenAI has rate limits based on your account tier
  - Wait a moment and try again
  - Consider upgrading your OpenAI plan

## Cost Information

### OpenAI API Pricing

- **GPT-3.5-turbo**: ~$0.002 per 1K tokens (very affordable)
- **Typical Query**: 500-1000 tokens per interaction
- **Estimated Cost**: $0.001-0.002 per question

**Note**: You only pay for what you use. No subscription required.

## License

This project is open source and available for personal and commercial use.

## Support

For issues or questions:
- Check the troubleshooting section above
- Review OpenAI API documentation
- Open an issue on GitHub (if applicable)

## Contributing

Feel free to fork this project and customize it for your own use. If you make improvements that could benefit others, consider sharing them!

---

**Made with ❤️ for better resumes and career growth**

