<div align="center">Upcoming Release Notes for <b>31 December 2025</b></div>
<div align="center">Release Version: <b>Release version 20</b></div>

This communication is to notify users of NAV AI of enhancements made to the application on a biweekly basis.
_Please reference the attachment for additional photos of the features and enhancements._

**Features Released**
- Agents with Functional Tools
  - Agents now include built-in function tools under a single Agents tab, consolidating Assistants and Utility Agents into one streamlined experience; existing utility agents remain usable with limited capabilities.
- Agent Chat Worksheet
  - Users can capture and organize AI-generated content into persistent, interactive worksheets that survive beyond the original conversation or agent, with full create, read, update, and delete capabilities to support collaboration and continuity.
- User Legal Notices
  - Legal disclaimers now appear during NAV AI registration for internal users, and the Accenture Privacy Statement link is available in the customizable NAV AI footer.
- User Communication Banner 
  - Administrators can create and manage a global banner visible across screens; users can dismiss viewed messages, and new or multiple messages are presented with a mechanism to review all content.

**Additional Enhancements**
- Improve Llama 4 model consistency across agents for predictable interactions.
  - Aligns Llama 4 behavior with prior model expectations to deliver a seamless, reliable agent experience.

**Bugs Fixed**
- Preview section disappears when user tries to Download/Update/Delete a dataset
  - Ensured the dataset preview remains visible during download, update, and delete actions.
- Sharing data source pop up text overlaps with 'X'.
  - Corrected layout so pop-up text no longer overlaps the close button.
- 'X' button in workspace creation in tags moves lower when tags are added
  - Fixed close button alignment when tags are added during workspace creation.
- Share workspace - inconsistency in naming
  - Standardized naming across Share Workspace dialogs and prompts.
- Uploading a tall image as Agent logo blocks buttons
  - Enforced logo sizing to prevent UI buttons from being blocked by tall images.
- Share Workspace: wrong dialog title
  - Corrected the Share Workspace dialog title.
- EQTY shield flashes red before green
  - Stabilized the EQTY shield to prevent erroneous red flashes before showing green.
- The agent details icon from chat box can be disabled in case of standalone chat.
  - Prevented unintended disabling of the agent details icon in standalone chat.
- Dataset details hidden
  - Restored visibility for dataset details.
- Document added to chat agent via Add-data-to this conversation is not being displayed in the chat window
  - Ensured documents added to a conversation display properly in the chat window.
- Data Source API Returns Empty ingestedFiles After Upload
  - Fixed the API to return ingestedFiles correctly after uploads.
- Add tool required fields
  - Clearly indicated and enforced required fields in the Add Tool flow.
- Nav.AI Template my template size issue
  - Resolved sizing issues for the “My Template” view.
- After deleting Nav.AI Template the details are not cleared
  - Cleared template details immediately after deletion.
- Roles table doesn't have people's e-mail address
  - Added email addresses to the Roles table.
- Governance disabled when created new agent
  - Ensured governance remains enabled when creating new agents.
- File import fails from demo2 env to dev
  - Resolved file import failures between demo2 and dev environments.
- Something went wrong message is coming when click on SuperAgent for the second time
  - Prevented erroneous error messages when opening a SuperAgent a second time.
- UI issue on existing Agent Detail page
  - Fixed layout and visual defects on the Agent Detail page.
- Major chat message formatting
  - Restored consistent Markdown rendering with system-defined styles for clearer, more readable chat messages.
- Upload and Process button gets disabled on upload a file to a new super agent conversation
  - Ensured the Upload and Process button remains available after file upload in new SuperAgent conversations.
- The custom greeting and default greeting are shown together on a single line without spacing or line break.
  - Corrected greeting formatting to include proper spacing and line breaks.
- Super-agent conversation not working after worksheet changes
  - Restored SuperAgent conversation functionality following worksheet updates.