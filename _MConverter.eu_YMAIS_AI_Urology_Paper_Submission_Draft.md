---
title: "Y-MAIS: A Physician-Designed Multi-Agent Artificial Intelligence System for Clinical Workflow Support in Urology"
---

# Abstract

Artificial intelligence (AI) is increasingly integrated into healthcare, particularly in diagnostic imaging, predictive analytics, and clinical decision support. However, many AI tools function as isolated analytical systems rather than integrated assistants within real clinical workflows. Healthcare delivery is inherently collaborative, involving physicians, nurses, case managers, and medical information specialists.

This study proposes a physician-designed multi-agent artificial intelligence architecture termed Y-MAIS (Yeh Medical Artificial Intelligence System). The system simulates the functional structure of a healthcare team using multiple specialized AI agents coordinated by a central orchestration agent. The architecture consists of four layers: interface, orchestration, AI agent, and data & knowledge layers.

Y-MAIS aims to improve clinical efficiency, support evidence-based medical decision-making, and enhance longitudinal patient monitoring. The proposed architecture illustrates how multi-agent AI systems may provide a practical pathway for integrating AI into everyday clinical practice.

# Keywords

Artificial intelligence; multi-agent systems; clinical decision support; healthcare workflow automation; urology; medical informatics

# 1. Introduction {#introduction}

Artificial intelligence has rapidly expanded in healthcare, demonstrating strong performance in medical imaging, predictive analytics, and decision support. Despite these advances, many systems remain task-specific tools that do not integrate well into daily clinical workflows.

Healthcare delivery is team-based. Physicians collaborate with nurses, case managers, pharmacists, and medical information specialists. Clinical decisions arise from multiple information sources rather than a single analytical tool.

To bridge this gap, we propose Y-MAIS, a multi-agent AI architecture designed to simulate a healthcare team environment. The system integrates several specialized agents coordinated by a central orchestration agent to support clinical workflow, knowledge retrieval, case management, and decision support.

# 2. System Architecture {#system-architecture}

The Y-MAIS system is organized into four primary layers: Interface Layer, Orchestration Layer, AI Agent Layer, and Data & Knowledge Layer. This layered architecture enables modular development and scalability while maintaining clear separation of system responsibilities.

# 2.1 Interface Layer {#interface-layer}

The interface layer provides interaction channels between clinicians and the AI system. Possible platforms include messaging applications (e.g., Telegram or LINE), web dashboards, mobile applications, and hospital information systems.

Clinicians may submit natural language queries or structured clinical data. The system interprets the input and activates relevant AI agents automatically.

# 2.2 Orchestration Layer {#orchestration-layer}

The orchestration layer is coordinated by the Clio agent, which acts as the central AI orchestrator. Clio interprets clinician queries, selects appropriate agents, coordinates tasks, aggregates results, and returns unified responses to the user.

# 3. AI Agent Design {#ai-agent-design}

The AI agent layer contains several specialized agents representing functional roles within healthcare teams.

# Florence --- Clinical Workflow Agent {#florence-clinical-workflow-agent}

Supports ward management, clinical reminders, patient monitoring, and workflow coordination.

# Hygieia --- Medical Knowledge Agent {#hygieia-medical-knowledge-agent}

Retrieves medical literature, summarizes clinical guidelines, and supports evidence-based practice.

# Trota --- Case Management Agent {#trota-case-management-agent}

Tracks longitudinal patient data such as PSA trends and follow-up schedules.

# Asclepius --- Clinical Decision Support Agent {#asclepius-clinical-decision-support-agent}

Performs clinical calculations, risk stratification, and decision-support analysis.

# Hermes --- Medical Data Analytics Agent {#hermes-medical-data-analytics-agent}

Analyzes clinical datasets, departmental statistics, and healthcare trends.

# 4. Clinical Use Case Example {#clinical-use-case-example}

Example query:  
PSA = 7.2  
Prostate volume = 40 cc

The system calculates PSA density, retrieves guideline recommendations, checks patient history, and produces a consolidated clinical suggestion.

# 5. Discussion {#discussion}

The Y-MAIS architecture introduces role-based specialization and central orchestration. By simulating the collaborative structure of healthcare teams, the system may reduce cognitive workload and improve clinical efficiency. The modular design also allows future expansion to other medical specialties.

# 6. Limitations {#limitations}

This study presents a conceptual architecture rather than a fully implemented clinical platform. Future research should evaluate integration with electronic health records, regulatory compliance, and real-world clinical performance.

# 7. Conclusion {#conclusion}

Y-MAIS demonstrates a conceptual framework for integrating artificial intelligence into clinical medicine using a multi-agent system. By modeling the collaborative structure of healthcare teams, the architecture provides a promising pathway toward AI-assisted clinical practice.
