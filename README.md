# meeting-operations-assistant
AI-assisted workflow for drafting meeting agendas, minutes, and action items with human review.
# Meeting Operations Assistant

An independently built portfolio prototype demonstrating how AI can support repetitive meeting operations while preserving human review.

**Live Demo:** https://meeting-operations-assistant-ligsolnf9flgt6v6332zde.streamlit.app/

## 1. Problem

Meeting administration can involve repetitive work, including structuring agendas, drafting minutes, extracting action items, and identifying missing information.

This prototype explores how AI-assisted workflows can reduce drafting and formatting effort while making information gaps easier to identify.

## 2. Approach

The application supports three workflows:

- **Agenda preparation:** turns meeting objectives and background information into a time-boxed agenda.
- **Meeting minutes:** creates a structured summary, decisions, action items, and open questions from supplied notes.
- **Action-item extraction:** organizes tasks, owners, deadlines, and supporting evidence into a readable table.

The workflow prompts the model not to invent missing details and asks it to flag information that requires confirmation. Users remain responsible for checking the outputs before use.

## 3. Technology

- Python
- Streamlit
- Google Gen AI Python SDK and Gemini API
- GitHub for version control and project documentation
- Streamlit Community Cloud for deployment

## 4. Outcome and evaluation

The result is a working prototype for generating structured meeting drafts from synthetic inputs.

The prototype is evaluated through test scenarios covering output completeness, unsupported assumptions, missing owners or deadlines, and usability.

Actual testing results should be recorded here after the tests are completed. No production-level time savings or accuracy improvements are claimed for this prototype.

## 5. Quality controls

- Missing owners and deadlines should be flagged for confirmation.
- Meeting decisions should not be invented.
- Generated drafts require human review.
- The application does not send emails or update external systems.

## 6. Limitations

- AI-generated content may be incomplete or incorrect.
- The project is a prototype, not a production-ready enterprise workflow.
- It is not connected to any employer's calendar, email, meeting platform, or internal systems.
- All demonstration inputs should be synthetic.

## 7. Privacy and independence

This project was independently recreated using synthetic information. It does not contain company documents, private meeting records, credentials, or proprietary templates and is not presented as an internal employer system.

## 8. Future improvements

- Export action items to CSV.
- Add repeatable quality-assurance test cases.
- Measure drafting time against a manual baseline.
- Explore structured output validation and additional workflow integrations.
