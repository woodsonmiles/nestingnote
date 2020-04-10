### Installation
- Windows
    1. [Download](https://www.python.org/downloads/release/python-382/) and Install Python3
    1. Install pip for Python3
    1. Install nestingnote<br>
        `pip install nestingnote`

- Linux (varies per distro)
    1. Install Python3<br>
        `sudo apt install python3`
    1. Install pip for Python3
    1. install nestingnote<br>
        `python3 -m pip install nestingnote`
### Execution
    `python3 -m nestingnote \path\to\my\notes`
### Controls
Most controls are intuitive, e.g., all printable keys insert that character, arrow keys, home, end, page up, and page down all move the cursor appropriately. However, there are a few special controls introduced by nestingnote:
- **Tab**: at the beginning of a line will indent the line, starting an inner nested list. Within the line, tab will split the line into fields similar to columns in a matrix.
- **Ctrl+k**: toggles whether the current item in the nested list is collapsed, meaning that all items nested beneath it are hidden.
- **Ctrl+w**: save the edits
