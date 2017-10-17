2017-10-06 Changes (Chicky)

Added these UI controls:
- TextPicker (TextBox + a dropdown for existing values)
  - TODO: remove the "recents_Click" event. "recentEntry_Click" has replaced it.
  - TODO: OnLoad, use the CategoryType parameter to get entries for the Recents selector.
- Separator (simple rectangle for visually separating UI elements)
- ImagePreview (shows an image and its source path; if an image is not available, "Image Needed" text is shown)
- EditableMetadata (compound UI for adjusting an entries metadata; contains TextPicker, ComboBox, and DatePicker controls; used on the new-entry dialog and the main window's edit-area.
- AddEntryDialog (popup for adding a new attack; image is optional)

- Updated the MainPage's edit-area to use the new ImagePreview, EditableMetadata controls.
- Updated the border around grid entries to make them more visible.
- Added helper functions to Definitions.cs for converting between enum MediaType <-> String

================================================

AttackNames Task List
---------------------

Completed:
- Basic UI
	- Add/view images
	- Add/edit/view metadata
- GitHub repository


In Progress:
- Create Metadata Class
- Serialize Metadata File

- Twitter Post Button (Dev only)
- Command Menu New Menu
	- Add Image
	- Add Temporary
	- Add Folder

Not Started:
- Metadata Editor
- Metadata Replace Image
- Load Metadata File
- Database Stats (Number of Files, Number of Sources, Number missing Images)
- Filter Area
- Border/Padding around image preview
- Image Names below preview