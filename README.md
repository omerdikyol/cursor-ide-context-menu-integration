<h1 align="center">Cursor IDE Context Menu Integration</h1>

<p align="center">
  <img alt="platform: Windows" src="https://img.shields.io/badge/platform-Windows-0078D6">
  <img alt="type: registry files" src="https://img.shields.io/badge/type-registry%20files-lightgrey">
  <img alt="license: MIT" src="https://img.shields.io/badge/license-MIT-green">
</p>

This repository provides `.reg` files that integrate the **Cursor IDE** into the Windows context menu, similar to how VS Code works. You can add options like "Edit with Cursor" and "Open Folder as Cursor Project" to the right-click menu when working with files and folders.

## Features

- **Edit with Cursor**: Adds an option to right-click any file and open it with Cursor.
- **Open Folder as Cursor Project**: Adds an option to right-click any folder or background space within a folder to open it as a project in Cursor.

## Installation

1. Download the `.reg` file(s) from this repository.
2. Change "your_name" with your user name in `add_cursor_ide_to_context_menu.reg`.
3. Check the Cursor installation path in the file.
4. Double-click the file to add it to your registry.
5. **Optional**: To enable "Edit with Cursor," uncomment the relevant lines in the `.reg` file.

## Removal

To remove the context menu entries, run the provided `remove_cursor_ide_from_context_menu.reg` file.

## Files

| File | Effect |
| --- | --- |
| [`add_cursor_ide_to_context_menu.reg`](add_cursor_ide_to_context_menu.reg) | Adds "Open Folder as Cursor Project" and optionally "Edit with Cursor" |
| [`remove_cursor_ide_from_context_menu.reg`](remove_cursor_ide_from_context_menu.reg) | Removes the added entries. Cursor itself stays installed |

## Usage

1. **Right-click on any file**: Choose "Edit with Cursor" (if enabled).
2. **Right-click on a folder or inside a folder**: Choose "Open Folder as Cursor Project."

## License

This project is licensed under the MIT License.
