# Cursor IDE Context Menu Integration

This repository provides `.reg` files that integrate the **Cursor IDE** into the Windows context menu, similar to how VS Code works. You can add options like "Edit with Cursor" and "Open Folder as Cursor Project" to the right-click menu when working with files and folders.

## Features

- **Edit with Cursor**: Adds an option to right-click any file and open it with Cursor.
- **Open Folder as Cursor Project**: Adds an option to right-click any folder or background space within a folder to open it as a project in Cursor.

## Installation

1. Download the `.reg` file(s) from this repository.
2. Double-click the file to add it to your registry.
3. **Optional**: To enable "Edit with Cursor," uncomment the relevant lines in the `.reg` file.

## Removal

To remove the context menu entries, run the provided `remove_cursor_ide_from_context_menu.reg` file.

## Files

- `add_cursor_context_menu_with_optional_edit.reg`: Adds "Open Folder as Cursor Project" and optionally "Edit with Cursor."
- `remove_cursor_ide_from_context_menu.reg`: Removes all added entries from the context menu.

## Usage

1. **Right-click on any file**: Choose "Edit with Cursor" (if enabled).
2. **Right-click on a folder or inside a folder**: Choose "Open Folder as Cursor Project."

## License

This project is licensed under the MIT License.
