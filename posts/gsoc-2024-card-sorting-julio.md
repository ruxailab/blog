---
title: "GSoC 2024 Journey (Julio's project) - Implementing Card Sorting Method in RUXAILAB"
date: 2024-06-15
author: Julio Manoel
gravatar: ""
github: 'JulioManoel'
---

Excited to share my **Google Summer of Code 2024** journey implementing the **Card Sorting method** in RUXAILAB! This project expanded our UX evaluation toolkit with a powerful new user research methodology. 🃏📊

<img src="/images/GSoC-Horizontal.webp" alt="Google Summer of Code 2024 Logo" style="display: block; margin: 2rem auto; max-width: 273px;" />

---

## Project Overview

Card sorting is a fundamental UX research method used to understand how users categorize and organize information. My project focused on **integrating this method seamlessly into the RUXAILAB environment**, making it accessible to researchers and designers worldwide.

## Understanding Card Sorting

Card sorting helps researchers:
- 📋 **Understand mental models** - How users naturally group information
- 🏗️ **Design better information architecture** - Create intuitive navigation structures  
- 👥 **Gather user insights** - Learn how target audiences think about content
- 📈 **Validate design decisions** - Test organizational structures before implementation

## What We Built

### 🎯 Core Features
- **Interactive card sorting interface** with drag-and-drop functionality
- **Multiple sorting types support** (open, closed, and hybrid card sorting)
- **Real-time collaboration** allowing multiple participants
- **Comprehensive analytics dashboard** for result interpretation

### 🔧 Technical Implementation
- Built with modern web technologies for cross-platform compatibility
- Integrated seamlessly with existing RUXAILAB infrastructure
- Implemented responsive design for various screen sizes
- Added accessibility features following WCAG guidelines

### 📊 Analytics & Insights
- **Similarity matrices** showing how often cards are grouped together
- **Dendrograms** for hierarchical clustering visualization
- **Standardized category analysis** for consistent groupings
- **Export capabilities** for further analysis in external tools

## Development Process

### Phase 1: Research & Planning
- Studied existing card sorting methodologies
- Analyzed user needs and requirements
- Designed the technical architecture
- Created wireframes and user flow diagrams

### Phase 2: Core Development
- Implemented the interactive card sorting interface
- Developed the backend API for data management
- Created the analytics engine for result processing
- Integrated with RUXAILAB's authentication system

### Phase 3: Testing & Optimization
- Conducted usability tests with real researchers
- Optimized performance for large card sets
- Implemented accessibility improvements
- Added comprehensive documentation

## Technical Challenges & Solutions

### Challenge: Performance with Large Card Sets
**Solution**: Implemented virtual scrolling and optimized rendering for handling 100+ cards efficiently.

### Challenge: Real-time Collaboration
**Solution**: Used WebSocket connections for instant updates across multiple participants.

### Challenge: Data Visualization
**Solution**: Integrated D3.js for creating interactive and informative result visualizations.

## Impact on UX Research

This implementation enables researchers to:
- 🔬 **Conduct remote card sorting studies** without specialized software
- 💰 **Reduce research costs** by using free, open-source tools
- 🌍 **Reach global participants** through web-based accessibility
- 📋 **Standardize research processes** across different teams

## Mentorship Experience

Working with mentors [Marc Gonzalez Capdevila](https://github.com/marcgc21) and [Karine Pistili Rodrigues](https://github.com/) provided invaluable guidance. Their expertise in UX research methodology and technical implementation helped shape a tool that truly serves the research community.

## Code & Implementation

Explore the complete implementation in the [RUXAILAB repository](https://github.com/ruxailab/RUXAILAB/pull/534):
- React-based frontend components
- Node.js backend API
- MongoDB data persistence
- Comprehensive test suite
- Detailed documentation

## Key Features Delivered

✅ **Multiple Card Sorting Types**
- Open sorting (participants create their own categories)
- Closed sorting (predefined categories)
- Hybrid sorting (mix of both approaches)

✅ **Advanced Analytics**
- Participant agreement analysis
- Category strength measurements
- Outlier detection
- Statistical significance testing

✅ **User Experience Excellence**
- Intuitive drag-and-drop interface
- Mobile-responsive design
- Accessibility compliance
- Multi-language support

## Future Enhancements

The foundation laid during GSoC 2024 opens possibilities for:
- **AI-powered category suggestions** based on card content
- **Integration with other UX research methods** in RUXAILAB
- **Advanced statistical analysis tools** for deeper insights
- **Template library** for common card sorting scenarios

## Community Impact

This project contributes to RUXAILAB's mission of **democratizing UX research** by providing professional-grade tools at zero cost. Researchers worldwide can now conduct sophisticated card sorting studies without budget constraints.

## Get Involved

Want to contribute to UX research tools?
- 🔗 [Check out RUXAILAB on GitHub](https://github.com/ruxailab)
- 💬 [Join our community discussions](https://discord.gg/6P4C6xuqtC)
- 📝 [Report issues or suggest features](https://github.com/ruxailab/RUXAILAB/issues)

Thank you to Google Summer of Code, RUXAILAB, and my amazing mentors for this incredible opportunity! 🚀

---

*This post is part of our GSoC 2024 series. Learn about [RUXAILAB's first GSoC experience](/posts/ruxailab-gsoc-2024) and explore other contributor projects.*
