# Text Project Template

## What is it

A template for swift writing texts (novels, stories, miniatures, articles, etc).

## Why is it

The template uses a general method of organizing things when writing source code for software. This makes it easier to use git for version control and backups. Also it makes writing much more interesting and structured like a good software engineering project. And the complete story (article) can be easily built with the [Storybuilder app](https://github.com/medotkato/storybuilder).

## How to use it

1. Clone the repository
2. Rename tpt folder as you like
3. Write scenes and fill in the outline.md file using URLs to scenes' files.

## What is here and how to use it

### The outline and scenes

- [/tpt/outline.md](tpt/outline.md) = outline of your text's scenes, the most important file for the project.

The outline.md file is used to write a structured outline for your text using necessary headers and list of parts (scenes). When some scene text is more or less ready, write an url to it's file instead of a scene's name.

Scenes (parts of your text) are located in the /scenes folder:

- [/tpt/scenes/opening.md](tpt/scenes/opening.md) = opening scene (template)
- [/tpt/scenes/closing.md](tpt/scenes/closing.md) = closing scene (template)
- /tpt/scenes/XXX.md = some other scene

Each scene file has 2 sections: Sketch and Text. Put the summary of the scene and all your thoughts to the '## Sketch' section and the scene's text to the '## Text' section. It is important if you want to use the [Storybuilder app](https://github.com/medotkato/storybuilder) - it gets the scene's text from the '## Text' section and it should be the 2nd section in the .md file.

### /tpt/info = folder for supporting materials

- [/info/characters.md](tpt/info/characters.md) = list of characters
- [/info/dictionary.md](tpt/info/dictionary.md) = dictionary of specific terms used in the writing

### /tpt/meta = metadata folder (if you need it)

- [/tpt/meta/main_meta.yaml](tpt/meta/main.yaml)### /tpt/info = folder for supporting materials
 = metadata for the tetx (title, author, brief description, etc)
- [/tpt/meta/characters.yaml](tpt/meta/characters.yaml) = list of characters and their properties
- [/tpt/meta/dictionary.yaml](tpt/meta/dictionary.yaml) = dictionary of specific terms used in the text (could be automatically generated in the future)
- [/tpt/meta/scenes.yaml](tpt/meta/scenes.yaml) = structured list of scenes (could be automatically generated from outline.md in the future)
