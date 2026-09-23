---
tags:
  - plugin
resource_link: "https://www.redguides.com/community/resources/mq2wintitle.3347/"
support_link: "https://www.redguides.com/community/threads/mq2wintitle.97296/"
repository: "https://github.com/MMOBugs/MQ2WinTitle"
authors: "htw"
tagline: "Change your EQ window titlebar (caption) text, to display data of your choice."
---

# MQ2WinTitle

<!--desc-start-->
Change your EQ window titlebar (caption) text, to display data of your choice. The specific text that is displayed is configurable
via INI file. The plugin will also indicate, if you wish, if a tell was received in a background EQ session, by changing the
titlebar to user defined text.
<!--desc-end-->

## Getting Started

```
/plugin MQ2WinTitle
```

### Commands

MQ2WinTitle provides one command with several options:

<a href="cmd-wintitle/">
{% 
  include-markdown "projects/mq2wintitle/cmd-wintitle.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "projects/mq2wintitle/cmd-wintitle.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('projects/mq2wintitle/cmd-wintitle.md') }}

### Configuration File

There is one section: `[Settings]`

`InGame`
:   The titlebar format to use while in game (not zoning, foreground).

`Tell`
:   The titlebar format to use if you receive a tell while EQ is in the background.

`Other`
:   The titlebar format to use at other times (such as char select).

`Zoning`
:   The titlebar format to use while zoning.

`ShowHotKey`
:   Whether to append the hotkey as shown by WinEQ2 or InnerSpace, if used.

The `ShowHotKey` entry is either on or off. All other entries are parsed as macro parameters

## Authors

* **htw** - *Initial work*
