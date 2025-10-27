<div align="center">Upcoming Release Notes for <b>27 October 2025</b></div>
<div align="center">Release Version: <b>14</b></div>

This communication is to notify users of NAV AI of enhancements made to the application on a biweekly basis. For questions please contact (deliverer@accenture.com) Deliverer.  
_Please reference the attachment for additional photos of the features and enhancements._

**Additional Enhancements**
- Chat response pane now auto-scrolls to the latest question and response.
   - The chat interface has been updated to automatically scroll to the latest response, ensuring users can view new messages immediately. A button has also been added to allow users to jump directly to the bottom of the page.
- A dynamic button allows users to jump to the bottom of the chat.
   - When scrolling up in a conversation, users can now use a button to quickly navigate to the bottom of the chat, improving usability.
- Exported Word and PowerPoint documents now include an automatic footer.
   - Exported files now display a footer with the text "Created using Accenture NAV AI Digital Team [Agent Name] [datetime]" for branding consistency.
- Export buttons have been relocated for better usability.
   - The Export to Word, PPT, and Excel buttons have been moved to a dropdown menu to free up space in the chat interface.
- Agent action buttons have been relocated for improved interface clarity.
   - Agent action buttons are now accessible via a dropdown menu, reducing clutter in the chat interface.
- Reference Data has been renamed to Data Marketplace.
   - The term "Reference Data" has been updated to "Data Marketplace" across the application for improved clarity and consistency.
- Agent configuration page buttons have been renamed and reordered.
   - Interface buttons on the Agent Configuration page have been renamed and reorganized for better usability, with related items grouped under a new "Agent Customization" section.
- EQTY-related elements are now hidden when disabled.
   - EQTY-related features are only displayed when the "isEqtyEnabled" variable is set to true, ensuring a cleaner interface for users without EQTY enabled.
- Release Notes visibility is now configurable.
   - Administrators can now enable or disable the Release Notes menu item based on an environment variable, allowing for tailored user experiences.
- Predefined system prompts now include a pop-up view.
   - Users can view all predefined system prompts in a pop-up window, making it easier to select prompts when there are many options.
- Error messages have been improved for clarity.
   - User-facing error messages have been rewritten in plain language to ensure they are clear, actionable, and free of technical jargon.
- Conversation history now supports deep linking.
   - Users can now navigate directly to a specific conversation via a deep link, improving accessibility and navigation.
- Release Notes markdown format has been standardized.
   - The Release Notes markdown display has been updated to ensure consistency across all environments and themes.
- @react-pdf library replaced with free alternatives.
   - The commercial @react-pdf library has been replaced with free alternatives, leveraging browser-native PDF rendering capabilities.

**Bugs Fixed**
- Deleting a file no longer triggers multiple calls.
- Inconsistent error messages in the frontend have been resolved.
- Datasets now refresh correctly after deletion.
- The Import button has been removed from the Edit Agent interface.
- The agent chat box now renders at the correct size.
- Agent background images now display as expected.
- The Model Selection dropdown is now disabled after creating a standalone conversation.
- Collapsing datasets no longer causes glitches.
- File upload text no longer appears in the wrong window.
- Resolved a vulnerability in Mermaid 11.8.1 that allowed cross-site scripting (XSS).
- Resolved a vulnerability in tmp/0.2.3 that allowed symbolic link exploitation.
- Addressed a transitive dependency issue with axios 1.9.0 by upgrading to axios 1.12.2.