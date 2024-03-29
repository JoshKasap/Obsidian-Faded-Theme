# Obsidian-Faded-Theme
Faded Theme For Obsidian By Josh Kasap![](Images/Faded.png)

## IMPORTANT
- This theme uses custom modified css to enable sliding panes. Due to this use of the ***Sliding Panes Plugin*** https://github.com/deathau/sliding-panes-obsidian will cause some undesirable glitches.
- This theme makes use of the ***Style Settings Plugin*** https://github.com/mgmeyers/obsidian-style-settings It's encuraged to install this plugin in order to gain access various customizable options for this theme.
## Features 
### Advanced Sliding Panes
Faded uses advanced CSS to further improve sliding/stacked panes/tabs in obsidian. With the release of Obsidian 1.0 we now have native support for unstacked and stacked tabs. This is great but what if you could have unstacked tab panes that also stacked like sliding panes? Well that's what this theme does! ![](Images/AdvancedSlidingPanesLayouts.png)
### Highlight And Indent/Depress Active Note
![](Images/ActivePage.png)
### Tables
![](Images/Table.png)
### Headers (Header Icons Optional With Style Settings Plugin)
![](Images/Headers.png)
### Headers Can Also Contain Links To Other Notes Or Tags
![](Images/HeaderTags&Links.png)
### Bullet Lists, Numbered Lists, And Checkboxes
![](Images/ListsAndCheckboxes.png)
### Obsidian Admonition/Callouts:
![](Images/Admonition.png)
### File Tree:
![](Images/FileTree.png)
### Outliner:
![](Images/Outliner.png)
### Better Popovers
![](Images/Popovers.png)
### Support For efemkay's MCL Multi Column Css Snippet
This is god teir css snippet allows for multi column layouts in your obsidian vault. It also can be customized using the style settings plugin. Documentation on how to use these layouts can be found here: https://efemkay.github.io/obsidian-modular-css-layout/multi-column/02-using-callout/
![](Images/MCLMultiColumn.png)
### Custom HTML Snippets
Faded ATM supports HTML snippets to help spice up your notes. 
- `<div class="pageTitle">Your Text Here</div>` 
![](Images/pageTitle.png)
- Use of an h1 tag for a page title adds clutter usually results in the rest of the page being restricted to h2-h6. Use of this snippet makes page titles stand out while avoiding waste of a good h1 tag. It can also be used to center and underline any word you want. 
- Add the class small to get small text to display in the snippet instead of the default large EX: `<div class="pageTitle small">Your Text Here</div>` Useful for fancy Admonitions (requires Admonitions Plugin)
## Style Settings Options
- Changes to these options usually work instantly but sometimes you need obsidian to restart obsidian for changes to work properly
![](Images/StyleSettings.png)
- You can chose to make panes not stack, This gives you more screen space when many panes are open.
-  You can modify the minimum page/pane width. This can be useful for people using obsidian at lower or higher resolutions. The default setting is made with 1440p screen in mind
-  You can enable bullet point gradient lines. This is off by default because it can make it hard to tell when a bullet begins and ends. But some may prefer the style. 
-  You can make it so checking items off a checklist won't cause the checked items text to be dimmed and crossed out. (This feature is Broken ATM)
## Supported Plugins
Faded currently supports full or partial styling of the following plugins. 
- **Style Settings Plugin: **https://github.com/mgmeyers/obsidian-style-settings
- **Calendar Plugin: **https://github.com/liamcain/obsidian-calendar-plugin

![](Images/Calendar.png)
- **Ozan's File Tree Alternative Plugin: ** https://github.com/ozntel/file-tree-alternative
	- Styles for this plugin are not throughly tested on every combanation of settings availble for the plugin. 

![](Images/OzanFileTree.png)

- Basic Style Support For Database Folder Plugin.
## Plugins Planned For Support
- **CodeMirror Options: **https://github.com/nothingislost/obsidian-codemirror-options
	- Support for this plugin is unavalible for now but planned in the future. 
- **DB Folder**:
	- Support for this plugin is activly being worked on  

## Todo List (As of 11-19-2022)
![](Images/TodoList.png)
# Kudos
- **SlRvb** and there ***ITS-Theme*** https://github.com/SlRvb/Obsidian--ITS-Theme It was a great reference and especially helped with getting the folder, page, and bullet point icons. It also was very helpful in getting the nested lines which can be seen in bullet points lists, the file navigation pane, and the outline pane. 
- **caro401** and there ***Royal Velvet Theme*** https://github.com/caro401/royal-velvet It was a great insperation/guide for my the gradiant headers and table header styles.
- Andy for his initial sliding panes CSS
- **efemkay** and there ***MCL Multi Column Css Snippets*** https://github.com/efemkay/obsidian-modular-css-layout
