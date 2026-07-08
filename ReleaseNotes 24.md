# Release Notes 1.24

### Governance and observability

NavAI Governance provides a framework to monitor, assess, and manage AI compliance across Workspaces, Agents, Workflows, and Data Sources. Rather than a static snapshot, it continuously measures compliance, surfaces risks early, and supports human decision-making while scaling to enterprise AI adoption.

> **Note:** NavAI automates observations, not governance decisions. Automated observables flag potential issues and the affected controls, but whether a control is compliant or non-compliant is always decided through human oversight.

**This release includes:**
- Workspace-level governance 
- Policy Management 
- Observable Framework 
- PII Detection 
- Quality Monitoring 
- Governance Studio integration and deep links between NavAI and Governance Studio 
- Compliance dashboards 
- A cryptographically secure audit log of governance and compliance events 

---

### Activity log

A centralized, chronological view of all actions performed within a workspace, giving visibility into user and agent activity. It tracks create, update, and delete activities, permission changes, and users added to or removed from the workspace, so every modification is traceable and reviewable. Access it via the Activity Log link in the Manage card on the workspace homepage. Not available in the Personal Workspace.

---

### Admin announcement banner

Admins can now run multiple banner notifications at once, letting them prepare future messages, reuse past banners, or manage parallel communications. Inactive banners stay available for future reuse or reactivation. When more than one banner is active, the end-user interface displays them in a carousel, showing each message individually for a set duration to avoid clutter.

---

### General Improvements

- **Branding and PWA:** Each environment (e.g. Strategy Q, Demo, UKI) can have its own branding, logos, and icons. The app is now an installable PWA with a headless browser experience and custom desktop icons per environment, giving users clearer, environment-specific branding. 
- **Default workspace logic:** A new toggle lets users set their default workspace directly from the workspace view. Admins can set a global default for all users, which individuals can override. On login or when clicking the logo, users land in their default workspace (or the admin global default if none is set). A star icon marks the default in the dropdown, and admins can set or change a user's default from the admin panel. 
- **Workspace personalization:** Users can rearrange panes on the workspace homepage. New "Workflows" and "Agents" panes are now front and center, and a bug causing panes to start collapsed is fixed—they now start expanded for better discoverability. 
- **Collaborate toggle default:** The Collaborate feature is now off by default for new workspaces (which have no agents or workflows yet), reducing confusion. It can be enabled when needed. 
- **Workflows and agent handoff:** Handoffs now use agent names and descriptions for more explicit logic. When all possible agent connections are made, the lines are replaced with a "connect to all" icon, reducing visual clutter and indicating an agent can hand off to any other. 
- **Attachments, conversation storage, and RAG:** Users can drag and drop files directly into chat. Attachments are sent to the model and available for a set number of interactions (sliding context window), while conversation storage keeps files available for the whole conversation. Files can be re-added via drag and drop or the upload button. A new cog lets users change the RAG embedding model (e.g. if one is deprecated), and improved error handling guides users toward conversation storage instead of RAG when uploading spreadsheets. 
- **Admin features:** Admins can set a user's default workspace from the admin panel. Only admins can see or change other users' default workspaces, so leadership can ensure users land in the right workspace while regular users can't alter others' settings. 

---

### Highlighted Bugfixes

- **CSV and Excel drag & drop:** Previously, the LLM's "Select Supported Inputs" setting controlled which file types the chat window accepted, so CSV and Excel files could only be added when the "TEXT" input was enabled—and that setting also let through other file types the backend silently ignored, giving the impression the model was hallucinating. Drag & drop of CSV and Excel files is now always allowed, independent of the "Select Supported Inputs" setting. 
- **RAG file usage:** Fixed a bug where an agent failed to use files uploaded as RAG when asked about them in chat.
