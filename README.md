# Text Project Template

A template for writing fictional texts (novels, stories, miniatures, etc) that  The template uses a general method of organizing things when writing source code for software. This makes it easier to use git for version control and backups. Also it makes writing much more interesting and structured like a good software engineering project.

## Files and Folders

### Folders

- / = folder for readme.md and main.md files only
- /img = folder for images used in the text
- /lib = folder for supporting materials (library)
- /meta = folder for metadata files

### Files

- /main.md = main file, comlete text with section headers
- /readme.md = the file you are reading now, it explains what lies here and why

- /lib/characters.md = list of characters
- /lib/dictionary.md = dictionary of specific terms used in the writing
- /lib/scenes.md = list of writing's scenes
- /lib/scenes = folder for scenes’ files 
- /lib/scenes/scene_opening.md = opening scene
- /lib/scenes/scene_closing.md = closing scene
- /lib/scenes/scene_XXX = some other scene

- /meta/main_meta.json = metadata for the the (title, author, brief description, worcount, starting idea, etc)
- /meta/characters.json = list of characters and their properties
- /meta/dictionary.json = dictionary of specific terms used in the text (could be automatically generated in the future)  
- /meta/outline.json = outline for text.md (could be automatically generated in the future) 
- /meta/scenes.json = structured list of scenes (could be automatically generated from scenes.md in the future) 
