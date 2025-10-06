# Digital Win Room (DWR) Automation Sprint 🚀
## 1.5 Hour Business Innovation Challenge

Welcome business innovators and citizen developers! Whether you're new to automation or have built agents before, this focused 90-minute sprint challenges you to create practical DWR solutions using low-code/no-code Microsoft tools. Transform your deal review expertise into intelligent automation.

## ⚠️ Important Environment Disclaimers

### **Power Platform & Copilot Studio Limitations**
- **Premium Connectors**: Your environment may have limited access to premium connectors (MSX, custom APIs)
- **External APIs**: Some third-party integrations may be restricted by organizational policies
- **Data Sources**: Mock or sample data might be required if production systems are unavailable
- **Publishing**: Copilot agents may require admin approval for Teams/SharePoint deployment
- **Custom Connectors**: Building new connectors may not be possible in restricted environments

### **Business-Friendly Workarounds for Sprint**
- **Start with What Works**: Use SharePoint Lists, Excel, Teams - tools you know are available
- **Think Like Your Current Process**: Mirror how you manually handle deals today
- **Sample Data Strategy**: Create 3-5 realistic deal scenarios you recognize from your work
- **Business Value First**: Show the process improvement even with mock data connections
- **Agent Builders**: Leverage your experience to help teammates design natural conversations

---

## 🚀 DWR Automation Blueprint

📋 **[View Complete Technical Blueprint →](./AUTOMATION_BLUEPRINT.md)**

### The Vision: Friday-Triggered Intelligence
Create an intelligent agent that automatically:
1. **Ingests deals** from MSX/DWR every Friday *(or mock data for demo)*
2. **Pre-fills templates** in OneNote or Loop with AI assistance
3. **Nudges owners** via Teams with personalized, contextual prompts
4. **Compiles meeting views** for executive reviews
5. **Publishes updates** back to DWR with audit trails *(or SharePoint for demo)*
6. **Classifies MACC** using Power BI analytics *(or mock classification)*

### Quick Implementation Guide
- **📊 A. Deal Ingestion & Pre-Fill** - Scheduled Friday triggers and template population
- **📢 B. Owner Prompting & SLA Nudges** - Teams notifications and escalation workflows  
- **📈 C. Meeting-Day Assist** - Live compilation and note synthesis
- **🔄 D. DWR Handoff** - API publishing and audit trails
- **🤖 E. MACC Automation** - Intelligent deal classificationce the Digital Win Room experience using Microsoft's platform tools.

## 🎯 Quick Start

### The DWR Challenge
Transform the manual, time-consuming process of deal review and executive communication into an intelligent, automated workflow that:
- **Reduces manual copy/paste** from MSX/CRM to staging areas
- **Improves comment quality** through AI-assisted templates
- **Automates status mapping** and MACC classification
- **Streamlines executive reviews** with smart notifications and compiled views

### Understanding the Current Process
1. **Deal Extraction**: Teams pull deals from MSX/DWR systems
2. **Staging**: Updates staged in OneNote or Microsoft Loop
3. **Owner Engagement**: Teams prompt via Microsoft Teams for executive-ready content
4. **Review Preparation**: Weekly review meetings with compiled deal status
5. **Publishing**: Finalized notes pushed back to DWR application

### Sprint Preparation (First 10 Minutes)
- [ ] Form your team (2-3 people - mix business knowledge with builder experience)
- [ ] Confirm your Power Platform/Copilot Studio access immediately
- [ ] Pick your tool: Copilot Studio, Power Apps, or Power Automate

## 💻 Business-Friendly Development Resources

### **Power Platform for Business Users**
- **Power Apps (Low-Code Apps)**
  - [Power Apps for Business Users](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/getting-started)
  - [Canvas Apps Quick Start](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/get-started-test-drive)
  - [App Templates Gallery](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/application-insights)
  - [Power Apps Formulas for Business Logic](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/formula-reference)

- **Power Automate (No-Code Workflows)**
  - [Power Automate Getting Started](https://docs.microsoft.com/en-us/power-automate/getting-started)
  - [Template Gallery](https://make.powerautomate.com/templates/)
  - [Approval Workflows](https://docs.microsoft.com/en-us/power-automate/modern-approvals)
  - [Teams Integration Flows](https://docs.microsoft.com/en-us/power-automate/teams/overview)

- **Copilot Studio (For Agent Builders)** 🤖
  - [Copilot Studio Overview](https://docs.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio) - *Start here if new to agents*
  - [Quick Start: Build Your First Agent](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-first-bot) - *15-minute tutorial*
  - [Conversation Topics](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-create-edit-topics) - *Business logic in natural language*
  - [Agent Templates](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-template-topics) - *Pre-built scenarios to customize*
  - [Power Automate Integration](https://docs.microsoft.com/en-us/microsoft-copilot-studio/advanced-flow) - *Connect to business processes*
  - [Testing Your Agent](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-test-bot) - *Built-in testing tools*
  - [Teams Deployment](https://docs.microsoft.com/en-us/microsoft-copilot-studio/publication-add-bot-to-microsoft-teams) - *Share with your team*

- **AI Builder (Smart Features)**
  - [AI Builder for Business Users](https://docs.microsoft.com/en-us/ai-builder/overview) - *Add intelligence without coding*
  - [Text Analysis](https://docs.microsoft.com/en-us/ai-builder/prebuilt-text-recognizer) - *Extract insights from deal notes*
  - [Document Processing](https://docs.microsoft.com/en-us/ai-builder/form-processing-model-overview) - *Automate data extraction*

- **Microsoft 365 Integration**
  - [Microsoft Teams Apps](https://docs.microsoft.com/en-us/microsoftteams/platform/)
  - [Microsoft Loop API](https://docs.microsoft.com/en-us/graph/api/resources/loop)
  - [OneNote API](https://docs.microsoft.com/en-us/graph/api/resources/onenote-api-overview)
  - [SharePoint Framework (SPFx)](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/sharepoint-framework-overview)

### Cloud & Data Integration
- **Azure Services** ⭐ (Primary Platform)
  - [Azure Free Account](https://azure.microsoft.com/en-us/free/)
  - [Azure Logic Apps](https://docs.microsoft.com/en-us/azure/logic-apps/)
  - [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/)
  - [Azure Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/)
  - [Azure Service Bus](https://docs.microsoft.com/en-us/azure/service-bus-messaging/)

### Essential APIs for DWR Integration
- **Microsoft Graph API**
  - [Teams Messages & Notifications](https://docs.microsoft.com/en-us/graph/api/resources/teams-api-overview)
  - [OneNote Integration](https://docs.microsoft.com/en-us/graph/integrate-with-onenote)
  - [Loop Components](https://docs.microsoft.com/en-us/graph/api/resources/loop)
  - [SharePoint & Lists](https://docs.microsoft.com/en-us/graph/api/resources/sharepoint)

- **Data Sources**
  - [Microsoft Dataverse](https://docs.microsoft.com/en-us/powerapps/maker/data-platform/)
  - [Power BI REST API](https://docs.microsoft.com/en-us/rest/api/power-bi/)
  - [Common Data Service Web API](https://docs.microsoft.com/en-us/powerapps/developer/data-platform/webapi/overview)
  - [MSX/CRM Connectors](https://docs.microsoft.com/en-us/connectors/)

## 🛠️ Tools & Resources

### Microsoft Development Environment
- [Power Apps Studio](https://make.powerapps.com/) - Low-code app development
- [Power Automate Designer](https://make.powerautomate.com/) - Workflow automation
- [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/) - AI agent building
- [Visual Studio Code](https://code.visualstudio.com/) - Code editor with M365 extensions
- [Power Platform CLI](https://docs.microsoft.com/en-us/power-platform/developer/cli/introduction) - Command line tools

### Testing & Debugging
- [Power Apps Monitor](https://docs.microsoft.com/en-us/powerapps/maker/monitor-overview) - App performance monitoring
- [Power Automate Run History](https://docs.microsoft.com/en-us/power-automate/monitor-manage-processes) - Flow debugging
- [Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer) - API testing
- [Microsoft Graph Postman Collections](https://docs.microsoft.com/en-us/graph/use-postman) - Official API collections

### Design & Prototyping
- [Power Apps Design Templates](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/application-insights) - Pre-built layouts
- [Microsoft Fluent UI](https://developer.microsoft.com/en-us/fluentui) - Design system
- [Power BI Templates](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-templates) - Dashboard designs
- [Microsoft Design Toolkit](https://docs.microsoft.com/en-us/power-platform/guidance/creator-kit/overview) - UI components and patterns

## 📚 Microsoft Learning Resources

### Microsoft Learn Training Paths
- [Power Platform Fundamentals](https://docs.microsoft.com/en-us/learn/paths/power-plat-fundamentals/)
- [Build Power Apps](https://docs.microsoft.com/en-us/learn/paths/build-power-apps/)
- [Automate Processes with Power Automate](https://docs.microsoft.com/en-us/learn/paths/automate-process-power-automate/)
- [Microsoft Graph Fundamentals](https://docs.microsoft.com/en-us/learn/paths/m365-msgraph-fundamentals/)

### **🤖 Agent Building for Business Users**
- [Copilot Studio for Beginners](https://docs.microsoft.com/en-us/learn/paths/work-power-virtual-agents/) - *Start here if new to agents*
- [Business Process Automation](https://docs.microsoft.com/en-us/learn/modules/power-virtual-agents-bots/) - *Connect agents to your workflows*
- [Advanced Agent Features](https://docs.microsoft.com/en-us/learn/modules/advanced-power-virtual-agents/) - *For experienced builders*
- [AI Builder for Business](https://docs.microsoft.com/en-us/learn/paths/ai-builder/) - *Add intelligence to your apps*

### **📊 Business Intelligence Integration**
- [Power BI for Business Users](https://docs.microsoft.com/en-us/learn/paths/create-use-analytics-reports-power-bi/) - *Turn deal data into insights*

### Microsoft Documentation & References
- [Microsoft Learn Hub](https://docs.microsoft.com/en-us/learn/)
- [Microsoft Technical Documentation](https://docs.microsoft.com/)
- [Microsoft Developer Documentation](https://developer.microsoft.com/)
- [Microsoft 365 Developer Portal](https://developer.microsoft.com/en-us/microsoft-365/)

## 🏆 DWR Automation Challenge Categories

### Main Challenge Categories
1. **Best End-to-End Automation** - Complete DWR workflow solution
2. **Most Intelligent Agent** - AI-powered deal analysis and recommendations
3. **Best User Experience** - Intuitive interface for executives and deal owners
4. **Most Innovative Integration** - Creative use of Microsoft 365 ecosystem
5. **Best MACC Classification** - Automated deal categorization and insights

### Key Pain Points to Solve
- **Manual Copy/Paste**: Eliminate repetitive data entry between systems
- **Inconsistent Comment Quality**: AI-assisted executive summary generation
- **Status Mapping**: Automated R/Y/G status determination
- **MACC Classification**: Intelligent deal categorization using Power BI + MSX data
- **Notification Fatigue**: Smart, contextual nudging system

### Standard Executive Fields to Automate
- Account/Opportunity details
- Stage & Forecast information
- Status indicators (Red/Yellow/Green)
- Executive Summary (AI-generated)
- Next Steps recommendations
- Risks/Blockers identification
- Help Needed categorization
- Hygiene Violations detection
- Services/Unified Play/ECIF classification


## 🎉 Tips for 90-Minute Sprint Success

1. **Your Domain Knowledge Wins**: Business logic beats technical complexity every time
2. **Check Environment in First 5 Minutes**: Verify connectors immediately with mentors
3. **3 Sample Deals Max**: Create just enough data to demo the concept convincingly
4. **Demo Story First**: Plan your 2-minute demo narrative while building

## 🌟 Inspiration & Reference Solutions

### Microsoft Power Platform Examples
- [Power Apps Sample Apps](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/open-and-run-a-sample-app)
- [Power Automate Templates](https://make.powerautomate.com/templates/)
- [AI Builder Samples](https://docs.microsoft.com/en-us/ai-builder/samples)
- [Copilot Studio Templates](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-template-topics)

### DWR Automation Building Blocks

#### **🤖 Copilot Agent Development**
- **Getting Started**: [Build Your First Copilot](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-first-bot)
- **Topics & Conversations**: [Create Conversation Topics](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-create-edit-topics)
- **Actions & Skills**: [Add Actions to Your Copilot](https://docs.microsoft.com/en-us/microsoft-copilot-studio/advanced-plugin-actions)
- **Power Automate Integration**: [Connect to Flows](https://docs.microsoft.com/en-us/microsoft-copilot-studio/advanced-flow)
- **Entity Recognition**: [Use Entities in Conversations](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-entities)
- **Variables & Memory**: [Manage Bot Variables](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-variables)
- **Testing & Analytics**: [Test and Analyze Your Copilot](https://docs.microsoft.com/en-us/microsoft-copilot-studio/authoring-test-bot)

#### **Other Integrations**
- **Power Apps Integration**: [Canvas App Tutorial](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/get-started-test-drive)
- **Teams Integration**: [Teams App Development](https://docs.microsoft.com/en-us/microsoftteams/platform/get-started/get-started-overview)
- **Graph API Usage**: [Microsoft Graph Quick Start](https://developer.microsoft.com/en-us/graph/quick-start)

---

## � DWR Automation Blueprint

### The Vision: Friday-Triggered Intelligence
Create an intelligent agent that automatically:
1. **Ingests deals** from MSX/DWR every Friday
2. **Pre-fills templates** in OneNote or Loop with AI assistance
3. **Nudges owners** via Teams with personalized, contextual prompts
4. **Compiles meeting views** for executive reviews
5. **Publishes updates** back to DWR with audit trails
6. **Classifies MACC** using MSX data + Power BI analytics

### Sprint Success Criteria
- **🎯 Clear Demo**: Working prototype that solves a specific DWR problem
- **� Innovation**: Creative use of Microsoft platform capabilities
- **📱 User Focus**: Solution that executives or deal owners would actually use
- **� Feasibility**: Realistic path from prototype to production

---

**Ready to revolutionize deal reviews? Let's build the future of DWR! 🚀**

*Questions about DWR processes, Microsoft Graph APIs, or Power Platform development? Our expert mentors are here to help!*