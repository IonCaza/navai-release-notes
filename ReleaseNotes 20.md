<div align="center">Upcoming Release Notes for <b>08 January 2026</b></div>
<div align="center">Release Version: <b>Release version 20</b></div>

This communication is to notify users of NAV AI of enhancements made to the application on a biweekly basis.
_Please reference the attachment for additional photos of the features and enhancements._

**Features Released**
- Agents can use Functional Tools
  - Create agents with built-in function tools, removing the need for separate utility agents; all new and ported agents appear under a unified Agents tab, with existing utility agents remaining usable.
- Agent Chat Worksheet
  - Pin important AI responses into persistent worksheets, create and manage them across sessions, and collaborate with teammates, preserving context beyond the originating conversation.
- Internal User Legal Notices
  - Legal disclaimers now appear during NAV AI registration and require acknowledgment; the Accenture Privacy Statement is persistently available via the customizable NAV AI footer.
- User Communication Banner 
  - Administrators can create and manage a global banner that displays across screens and surfaces new updates prominently to users.

**Bugs Fixed**
- Preview section disappears when user tries to Download/Update/Delete a dataset
  - Fixed a UI issue where the dataset preview vanished during download, update, or delete actions; the preview now remains visible.
- Sharing data source pop up text overlaps with 'X'.
  - Resolved overlapping text in the share data source dialog so the close button remains clear and clickable.
- 'X' button in workspace creation in tags moves lower when tags are added
  - Corrected layout shifting in workspace creation; the close button stays aligned when tags are added.
- Share workspace - inconsistency in naming
  - Standardized naming throughout the share workspace experience for clarity and consistency.
- Uploading a tall image as Agent logo blocks buttons
  - Constrained agent logo display so tall images no longer cover action buttons.
- Share Workspace: wrong dialog title
  - Fixed incorrect dialog titles in share workspace workflows.
- EQTY shield flashes red before green
  - Eliminated transient red flash; the EQTY shield now reflects the correct status color.
- The agent details icon from chat box can be disabled in case of standalone chat.
  - Fixed incorrect disabling of the agent details icon in standalone chat sessions.
- Dataset details hidden
  - Restored visibility of dataset details in the UI.
- Document added to chat agent via Add-data-to this conversation is not being displayed in the chat window
  - Ensured documents added to a conversation appear correctly in the chat window.
- Data Source API Returns Empty ingestedFiles After Upload
  - Corrected the API response to return populated ingestedFiles after uploads.
- Add tool required fields
  - Fixed validation and prompts for required fields when adding tools.
- Nav.AI Template my template size issue
  - Resolved sizing issues affecting My Template so content renders correctly.
- After deleting Nav.AI Template the details are not cleared
  - Cleared residual details after template deletion to prevent stale information.
- Roles table doesn't have people's e-mail address
  - Added missing email addresses to the Roles table.
- Governance disabled when created new agent
  - Corrected governance settings so new agents are created with the intended governance state.
- File import fails from demo2 env to dev
  - Resolved cross-environment file import failures from demo2 to dev.
- Something went wrong message is coming when click on SuperAgent for the second time
  - Fixed intermittent errors when opening a SuperAgent a second time.
- UI issue on existing Agent Detail page
  - Addressed layout and display issues on the Agent Detail page.
- Major chat message formatting
  - Restored consistent Markdown rendering and styling for chat messages to improve readability.
- Upload and Process button gets disabled on upload a file to a new super agent conversation
  - Prevented premature button disabling; Upload and Process remains enabled and functions after file upload.
- The custom greeting and default greeting are shown together on a single line without spacing or line break.
  - Corrected greeting formatting so messages display with proper spacing or line breaks.
- Super-agent conversation not working after worksheet changes
  - Fixed conversation failures after worksheet modifications.
- Without selecting any Worksheet from click on Select button,System is showing Black screen with Type Error
  - Prevented errors when no worksheet is selected; the system now continues without a black screen.