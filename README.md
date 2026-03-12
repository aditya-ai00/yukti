# AdminAI — Leadership Intelligence Platform

AdminAI is an AI-powered governance assistant designed to support public leaders, administrators, and policy teams in managing information, decisions, and communication efficiently.

The platform integrates document intelligence, issue tracking, task management, speech generation, and data insights into a unified dashboard to help administrators respond faster to civic challenges.

---

## Overview

Public leaders handle large volumes of information every day including policy documents, meeting notes, citizen complaints, and operational reports. Processing this information manually slows decision-making.

AdminAI provides an intelligent digital workspace that uses AI to summarize information, generate communication drafts, track issues, and provide data insights to support better governance.

---

## Key Features

### AI Document Intelligence
Automatically summarizes long reports, policy documents, emails, or notes into clear executive summaries, bullet points, or action items.

### Meeting Intelligence
Extracts key decisions, responsibilities, and follow-ups from meeting notes or transcripts.

### Speech & Communication Assistant
Generates speeches, official responses, statements, and press releases based on context and tone.

### Constituency Issue Tracker
Tracks civic issues such as infrastructure complaints, funding gaps, or public service problems and prioritizes them for administrators.

### Task & Schedule Management
Helps leaders manage meetings, tasks, and priorities with an AI assistant that suggests what to focus on.

### Data Insights Dashboard
Analyzes civic data such as budgets, projects, and public sentiment to highlight trends and risks.

### AI Insight Engine
Allows leaders to ask questions about data, reports, or issues and receive structured insights and recommendations.

---

## Dashboard Modules

The platform includes several modules accessible from the sidebar:

- **Dashboard** – Overview of statistics, tasks, issues, and quick AI assistant  
- **Summarizer** – Summarizes documents, meeting notes, or email threads  
- **Speech Writer** – Creates speeches, responses, or official communication  
- **Issue Tracker** – Manages community issues and allows AI analysis  
- **Schedule & Tasks** – Tracks meetings and pending tasks  
- **Data Insights** – Visualizes budget usage and public sentiment  

---

## Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript

**AI Integration**
- Anthropic Claude API

**Design**
- Custom dashboard UI
- Responsive layout
- Dark theme interface

---

## Installation

Clone the repository:

Navigate to the project folder:

Run the project:

Simply open the `index.html` file in your browser.

---

## API Configuration

The platform uses the **Anthropic Claude API** for AI-powered features.

Update the following configuration in the JavaScript section:

```javascript
const API_URL = "https://api.anthropic.com/v1/messages";
const MODEL = "claude-sonnet-4-20250514";
```

Add your **API key securely** in the request headers when deploying the application.

---

## Example Use Cases

- Government administrators summarizing policy documents  
- Local leaders drafting official public responses  
- Teams analyzing citizen complaints  
- Officials preparing speeches or press releases  
- Administrators tracking civic issues  
- Policy teams reviewing public data insights  

---

## Future Improvements

- Real-time integration with civic platforms
- Speech-to-text meeting transcription
- Role-based access control
- Integration with government data sources
- Predictive analytics for civic issues
- Mobile application for field officers

---

## License

This project is licensed under the **MIT License**.

---

## Contributing

Contributions are welcome.

If you would like to improve this project:

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Submit a pull request

Please ensure your code follows clean coding practices and proper documentation.


## Author

Developed as part of a Civic Tech / Governance AI project to explore how artificial intelligence can assist public leaders and administrators in decision-making and communication.
