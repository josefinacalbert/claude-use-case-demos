# Claude Use Case Demo Templates

Interactive HTML demos showcasing Claude's capabilities across different use cases. These templates are designed to be easily customizable for creating new use case guides.

## 🎯 Purpose

These demos help users understand Claude's capabilities through interactive, simulated conversations that showcase real outputs and workflows.

## 📁 Project Structure

```
claude-use-case-demos/
├── templates/           # Base templates for different use case types
│   └── writing-style-guide.html
├── demos/              # Completed demos ready for deployment
├── assets/             # Shared assets (future use)
│   ├── css/
│   └── js/
└── README.md
```

## 🚀 Quick Start

### Using a Template

1. Copy a template from `templates/` directory
2. Modify the following key sections:
   - **Header Content**: Title, description, and value props
   - **Preview Carousel**: Update the 3 slides with relevant outputs
   - **Chat Messages**: Customize user prompts and Claude responses
   - **Artifacts**: Replace with use-case-specific outputs
   - **Suggestion Pills**: Tailor to your use case flow

### Template Structure

Each template includes:

- **Header Section**: Hero area with use case title and preview
- **Progress Indicator**: Visual journey through the demo
- **Chat Interface**: Simulated conversation with Claude
- **Artifacts**: Embedded, scrollable output displays
- **Interactive Elements**: Suggestion pills, retry buttons, file attachments

## 🎨 Design System

### Colors
- Primary: `#bf7358` (Warm terracotta)
- Text: `#3d3d40` (Warm gray)
- Background: `#faf9f8` (Off-white)
- Secondary: `#6b6b6f` (Muted gray)

### Typography
- Headers: Georgia, serif
- Body: -apple-system, BlinkMacSystemFont, system-ui

### Components
- **Buttons**: Rounded pills (100px border-radius)
- **Cards**: Subtle borders with minimal shadows
- **Inputs**: Clean, minimal styling

## 📝 Creating New Use Cases

### Step 1: Choose Your Use Case
Select a specific, valuable use case that demonstrates Claude's capabilities.

### Step 2: Plan the Flow
1. **Initial Prompt**: What the user asks Claude
2. **Analysis/Processing**: Show Claude working (tool use, analysis)
3. **Main Output**: The primary deliverable (style guide, code, analysis)
4. **Follow-up Options**: 1-2 next steps

### Step 3: Customize Content

```html
<!-- Update header title -->
<h1 class="header-title">Your Use Case Title</h1>

<!-- Modify preview carousel slides -->
<div class="carousel-slide">
    <!-- Your custom preview content -->
</div>

<!-- Update chat messages -->
<div class="message-text">
    Your custom user prompt
</div>

<!-- Customize artifacts -->
<div class="artifact-container">
    <!-- Your main output content -->
</div>
```

### Step 4: Test Interactivity
- Ensure suggestion pills work correctly
- Verify progress indicators update
- Test all buttons and hover states

## 🔧 Customization Tips

### For Different Industries
- Update terminology and examples
- Adjust color scheme if needed
- Modify attachment types

### For Different Outputs
- Code: Use monospace fonts and syntax highlighting
- Data: Include charts and tables
- Creative: Add visual examples

### For Different Audiences
- Technical: Include more detail and specifications
- Executive: Focus on outcomes and ROI
- General: Keep language accessible

## 📋 Checklist for New Demos

- [ ] Clear use case title and description
- [ ] 3 compelling preview slides
- [ ] Realistic user prompt with attachments
- [ ] Detailed Claude response with analysis
- [ ] Beautiful, functional main artifact
- [ ] 1-2 relevant follow-up suggestions
- [ ] Smooth animations and transitions
- [ ] Mobile-responsive design
- [ ] Tested all interactive elements

## 🚢 Deployment

Demos can be deployed as static HTML files to:
- GitHub Pages
- Netlify/Vercel
- Company websites
- Documentation portals

Simply upload the HTML file - no build process required!

## 📄 License

Internal use for Claude demonstrations and marketing materials.

## 🤝 Contributing

To add new templates:
1. Create your demo based on existing templates
2. Test thoroughly
3. Add to `templates/` directory
4. Update this README with any new patterns

---

**Template Version**: 1.0  
**Last Updated**: September 2025  
**Maintained By**: Claude Team