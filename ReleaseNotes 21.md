
<div align="center"><b>Release Notes from 06 February 2026</b></div>
<div align="center"><b>Release Version: 2026 version 3</b></div>

This communication is for notifying users of NAV AI about the enhancements made to the application.

**Features Released**
- Generative Interactive Tables
	- LLM-generated tables now render consistently with a normalized structure and preserve original data while enabling search, sorting, pagination, column visibility, copy, and CSV export. Skeleton loaders improve streaming feedback, malformed tables surface clear errors, and interactivity respects row/col spans; visual styling is allowed within fixed layout guidelines for reliable behavior.

**Additional Enhancements**
- Share worksheets via secure public links.
	- Create and copy shareable links from the Actions menu, retrieve previous shares, and rely on ownership checks and deletion safeguards for controlled access.
- Organize worksheets with tags for faster filtering and search.
	- You can add and remove tags on any worksheet you can access
- Delete worksheets from the worksheet details view or from the Worksheet action buttons
- Deletion removes the worksheet from the system and clears all references, so it no longer appears in related conversations or UI elements.
- Detach worksheets from conversations
	- Remove a worksheet’s association with the current conversation
- Tabs are now visually differentiated for quicker navigation.
	- Current Session and Worksheet tabs feature distinct icons and styling to make entity types immediately recognizable.
- Icons in chat input needed to be changed as export icon was confused with worksheet icon
	- The export and worksheet icons have been updated to clearly differentiate them.
- More repeatable workflows with natural-language agent selection.
	- Super Agents now perform handoffs by human-readable agent names instead of database IDs, improving stability and reuse.
- Clear delivery status for emails sent from agents.
	- When sending emails via the function tool, conversations reflect success/failure state, so users know the outcome of their request.
- Dataset name validation prevents chat errors.
	- UI and API validations enforce safe name lengths for datasets attached to agents, avoiding Bad Request errors and surfacing clear messages.
- Inline previews for text and markdown attachments.
	- Text files attached in chat display a content preview instead of a generic icon for faster verification of the right file.
	
**Bugs Fixed**
- Error Loading Dataset: Internal Server Error is coming to the History section when want to edit attach file to the conversation
	- Resolved history errors when editing attached files and fixed update failures after removing agent or super agent images; added missing validation messages when updating datasets, system prompts, visualizations, or starter prompts without selections to prevent silent failures and improve clarity.
- Import API skips selected Nav.AI Tools during agent import
	- Import now reliably includes all selected tools during agent import.
- Users could add deleted tags under 'Tag' section of the agent
	- Deleted tags can no longer be re-added; tag integrity is maintained.
- Super Agent Conversation History showed NA in Date Created column
	- Date Created now displays correctly in conversation history.
- Super Agent conversation history DELETION was giving 500 error
	- Deleting conversation history no longer triggers server errors.
- Attach image on chat section resulted with 500 error code
	- Resolved a failure that caused image attachments in chat to return a 500 error and display an “Unknown error” message.
