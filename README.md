# Text Project Template

## What is it

A template for swift writing fictional texts (novels, stories, miniatures, etc).

## Why is it

The template uses a general method of organizing things when writing source code for software. This makes it easier to use git for version control and backups. Also it makes writing much more interesting and structured like a good software engineering project.

## What is here

### Folders

- / = folder for readme.md and main.md files only
- /img = folder for images used in the text
- /lib = folder for supporting materials (library)
- /lib/scenes = folder for scenes’ files
- /meta = folder for metadata files

### Files

- [/main.md](main.md) = main file, comlete text with section headers
- [/README.md](README.md) = the file you are reading now, it explains what lies here and why

- [/lib/characters.md](lib/characters.md) = list of characters
- [/lib/dictionary.md](lib/dictionary.md) = dictionary of specific terms used in the writing
- [/lib/scenes.md](lib/scenes.md) = list of writing's scenes
- [/lib/scenes/scene_opening.md](lib/scenes/scene_opening.md) = opening scene (template)
- [/lib/scenes/scene_closing.md](lib/scenes/scene_closing.md) = closing scene (template)
- /lib/scenes/scene_XXX.md = some other scene

- [/meta/main_meta.json](meta/main_meta.json) = metadata for the the (title, author, brief description, worcount, starting idea, etc)
- [/meta/characters.json](meta/characters.json) = list of characters and their properties
- [/meta/dictionary.json](meta/dictionary.json) = dictionary of specific terms used in the text (could be automatically generated in the future)
- [/meta/outline.json](meta/outline.json) = outline for text.md (could be automatically generated in the future)
- [/meta/scenes.json](meta/scenes.json) = structured list of scenes (could be automatically generated from scenes.md in the future)
