<div align="center"><b>Release Notes from 04 May 2026</b></div>
<div align="center"><b>Release Version: 2026 version 1.16</b></div>

This communication is for notifying users of NAV AI about the enhancements made to the application.

**Features Released**
- Collaboration Workspace
	- The Collaboration Workspace is a flexible experience where you can organize and manage your work, whether individually or with a team. Your experience is tailored to your permissions—some users have personal workspaces, while others join shared spaces. Workspace owners can customize what members see and do, so your interface adapts to your role.
	- Switching between workspaces is seamless. Actions like creating agents or starting conversations depend on your access level, and any changes are visible to all members in real time. The workspace keeps personal and team tasks organized, supports easy management of agents and conversations, and allows owners to configure sections and manage members.
	- With Collaboration Workspaces, datasets, system prompts, function tools, and visualizations are now scoped at the workspace level. Each workspace must have its own dedicated instance of these entities to reference within that workspace. Features like Agent Clone have been updated to reflect the independent target workspace. Cloned agents will not retain references to these entities.
- Fine-Grained Access Permissions
	- Administrators can now independently restrict workspace, agent, and workflow creation at the role level. Users without creation permissions see a simplified, interaction-focused interface — hiding authoring controls they don't need.
- Structured Data Datasets
	- Upload CSV or Excel files and control exactly which columns and rows are exposed to AI queries using projections and filters. Configurations are saved and reusable across compatible files. Incompatible file replacements trigger a clear compatibility warning before overwriting.
- Linear (Deterministic) Workflows
	- Build step-by-step workflows where agents execute in a fixed, user-defined sequence. Each agent receives the output of the previous one — ensuring predictable, repeatable behavior for consistent tasks. Toggle between agentic and deterministic modes during workflow creation.
- New Chat Button
	- Enable users to start a new conversation with the currently selected agent without leaving the active chat window. This gives users a faster, more natural way to reset the conversation context while staying focused on the same agent experience, instead of navigating back to the agent list to begin again.
- Delete LLMs from the Registry
	- Administrators can now remove expired or obsolete LLM models from the Module Registry — even if they are referenced by existing agents or workflows. Affected users are prompted to select a replacement model before continuing.
- Document Parsers for RAG Ingestion
	- When uploading files to the Data Marketplace within the RAG ingestion process, users can now optionally select document parsers to improve extraction of text, tables, diagrams, and images. Two options are available: Azure Document Intelligence (paid, multilingual, available for multiple file types) and an Offline Parser (free, English only, for PDF files). Standard ingestion remains available without needing a parser. Parser availability must be configured by an administrator before regular users will be able to see and use them.