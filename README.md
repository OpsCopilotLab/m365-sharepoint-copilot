# M365 SharePoint Copilot

Enterprise knowledge assistant that queries SharePoint libraries with page-level citations.

## Status: Not Started - Planned for Week 4

This project will start after completing the Fire Department RAG system.

## Planned Architecture

SharePoint Libraries → Microsoft Graph API → Azure OpenAI Embeddings
↓
PostgreSQL + pgvector
↓
FastAPI + Entra ID Auth
↓
Teams App Interface

## Planned Stack
- **Auth:** Microsoft Entra ID (OAuth 2.0)
- **APIs:** Microsoft Graph, SharePoint REST API
- **Embeddings:** Azure OpenAI
- **Vector DB:** PostgreSQL + pgvector
- **Platform:** Azure OpenAI + Teams SDK
- **Integration:** Power Automate, Planner, To Do

## Planned Features
- Policy/SOP search across SharePoint
- Page-level citations from Word/PDF
- Meeting notes → action items
- Incident summaries
- Teams app interface

## Timeline
- Starts: Week 4 (after Fire Dept RAG ships)
- Duration: 4 weeks

## Why This Project
Testing enterprise M365 integration patterns for internal knowledge automation.

---

## Contact
Arnaldo Sepulveda  
https://linkedin.com/in/arnaldo-sepulveda
