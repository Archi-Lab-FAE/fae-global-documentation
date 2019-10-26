# fae-global-documentation
The repository contains all global, open, guiding decisions and all glossary entries.

## Usage
To create a new decision or glossary entry you have to create a new markdown file. This filename must equal a spefici pattern, that is described in the following:

```
Filename: YYYY-MM-DD-[Glossary|Decision]-TITLE.md
Example 1: 2019-09-13-Glossary-Aggregate.md
Example 2: 2019-10-26-Decision-Java-as-Standard-Language.md
```
Each filename title must be unique!
Afterward, you can edit your decision. On top you have to privde some metadata for the Jekyll server.
The metadata must be as the following template: 

### Metadata
```
---
layout: post
title: title of your decision //must not be the same as your filename!
author: the athorsname //optional
categories: global //Further valid options are shown in the following list!
---
```


### Nutzbare Kategorien
 - global <-- global decisions
 - open <-- open decisions
 - guide <-- guiding decisions
 - glossary <-- glossary

Please choose the category carefully and based on your task!
Next to these metadata you can finally add your decision text.
