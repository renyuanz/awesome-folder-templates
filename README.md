# Awesome Folder Templates

## Why?

__Folder Templates CLI__: a stupid way to kill your boilerplate code.

[👉 Folder templates VSCode plugin](https://marketplace.visualstudio.com/items?itemName=Huuums.vscode-fast-folder-structure&ssr=false#overview)

I'm tired of creating the same directories over and over again, but I hate over-designing with the wrong abstractions.

Opinionated frameworks come with generator CLIs that's just too opionionated.

I just want to build things explicitly with the templates I or my team chooses.

The VSCode plugin is good enough, but I want to share `.ftemplates` easily across teams and projects.

## Here is how 👇

### 0. Install `ft-cli` and read how `.fttemplates` works

```shell
$ brew install ft-cli 
```

### 1. Find a category that you are looking for, a language, a framework or a specific scenario

### 2. Pick your choice, get the template `repo_url`

### 3. Clone the template to your source code

install the templates from `repo_url` to your current working directory's `.fttemplates/[slug]` folder

```shell
$ ft clone <repo_url> <slug> 
```

### 4. Generate directories from the cloned template

Now you can create a directory to `destination` from a template `slug`

```shell
$ ft generate <slug> <destination>
```

