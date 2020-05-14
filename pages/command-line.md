# Working with the Command Line

If you're working with Python scripts or with Jupyter Notebooks, you'll have to do some work with the command line. While this retro-looking interface make seem scary at first, hoepfully this short guide will help you become more comfortable with it.

[Placeholder for Video]()

## Common Commands Reference

### Navigation

- `cd {path or folder name}` - Change current position to specified path or folder
- `cd ..` - Go up a directory (E.g. `~/Documents/Projects` -> `~/Documents/`)
- `ls` - List visible components in a directory (files and folders)
- `ls -a` List all components in a directory (including hidden files)

### File/Folder Creation and Deletion

- `cp {file-to-copy} {new-file-name}` - Crates a copy of `file-to-copy` named `new-file-name`
- `mv {file} {new-location}` - Moves `file` to new location, `new-location`

- `mkdir {directory}` - Creates a folder named `directory`
- `touch {file}` - Creates a blank file named `file`

- `rm {file}` - Deletes `file` (skips the trash)
- `rm -r {folder}` - Removes `folder`, requires confirmation for each file within it
- `rm -rf {folder}` - Removes `folder`, but skips confirmation for each file within it
- `rmdir {folder}` - Removes `folder` **only if empty**

---
[Return Home](https://anthony-agbay.github.io/python-resource-guide)
