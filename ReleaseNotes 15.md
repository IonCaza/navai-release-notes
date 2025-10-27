<div align="center">Upcoming Release Notes for <b>27 October 2025</b></div>
<div align="center">Release Version: <b>15</b></div>

This communication is to notify users of NAV AI of enhancements made to the application on a biweekly basis. For questions please contact (deliverer@accenture.com) Deliverer.  
_Please reference the attachment for additional photos of the features and enhancements._

**Additional Enhancements**
- The chat response pane now automatically scrolls to the latest question and response, ensuring users can immediately view new content. A button has been added to allow users to jump directly to the bottom of the page for convenience.
- A dynamic button has been introduced to allow users to quickly scroll to the bottom of the chat when navigating through previous messages.
- Exported Word and PowerPoint documents now include an automatic footer with branding and metadata, excluding Excel files.
- Export buttons for Word, PowerPoint, and Excel have been relocated to a dropdown menu to optimize conversation space.
- Agent action buttons have been relocated to a dropdown menu to reduce clutter in the chat interface. These changes are deployed alongside the export button relocation.
- The "Reference Data" section has been renamed to "Data Marketplace," and related labels have been updated for consistency.
- The Agent Configuration page has been reorganized to improve usability by renaming and reordering interface buttons. Key features are now grouped under a new "Agent Customization" section.
- EQTY-related elements are now hidden in the interface when the EQTY feature is disabled.
- A configuration option has been added to enable or disable the Release Notes menu item based on an environment variable.
- Predefined system prompts in the chat now include a pop-up option, allowing users to view all prompts at once for easier selection.
- Users can now edit or view information about system prompts directly within the Edit Agent window, streamlining the agent customization process.
- The Release Notes feature now supports a standardized markdown format that adapts to light and dark themes for consistent display across environments.
- A deep linking feature has been added to allow users to navigate directly to specific conversation histories from external applications or links.
- The @react-pdf library has been replaced with alternative solutions to avoid licensing issues while maintaining core PDF rendering functionality.
- Security vulnerabilities in the Mermaid and tmp libraries have been resolved to enhance application security.

**Bugs Fixed**
- Resolved an issue where deleting a file triggered multiple unnecessary calls.
- Fixed inconsistent error messages in the frontend interface.
- Addressed an issue where deleted datasets were not refreshing correctly in the interface.
- Removed the "Import" button from the Edit Agent page.
- Fixed a bug where the agent chat box size was not rendering correctly.
- Resolved an issue where agent background images were not being displayed.
- Disabled the model selection dropdown in the chat interface after a standalone conversation is created.
- Fixed a glitch causing the collapse functionality for datasets to behave incorrectly.
- Resolved an issue where file upload text was displayed in the wrong window.