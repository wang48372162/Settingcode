# Setting code (Lucas Yang)

## VS Code settings
```js
{
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "none",
  "workbench.editor.closeEmptyGroups": true,
  "workbench.editor.restoreViewState": false,
  "workbench.editor.scrollToSwitchTabs": true,
  "workbench.editor.enablePreview": true,
  "workbench.activityBar.visible": true,
  "workbench.statusBar.visible": true,
  "workbench.editor.untitled.hint": "hidden",

  // 視窗
  "window.zoomLevel": 1,
  "window.titleBarStyle": "custom",
  "editor.snippetSuggestions": "top",
  "editor.mouseWheelZoom": false,
  "editor.wordWrap": "on",
  "editor.fontFamily": "Consolas",
  "editor.fontLigatures": true,
  "editor.tabSize": 2,
  "editor.fontSize": 14,
  "editor.tabCompletion": "onlySnippets",
  "editor.suggest.localityBonus": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "explorer.openEditors.visible": 0,
  "diffEditor.ignoreTrimWhitespace": false,
  "diffEditor.renderSideBySide": false,

  // Terminal (Commend line)
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.profiles.windows": {
    "Git Bash": {
      "path": "C:\\Program Files\\Git\\bin\\bash.exe",
      "args": ["--login", "-i"]
    },
    "CMD": {
      "path": "C:\\Windows\\system32\\cmd.exe"
    }
  },
  "terminal.integrated.windowsEnableConpty": false,

  // Git
  "git.enableCommitSigning": true,

  // 擴充功能
  "extensions.ignoreRecommendations": true,
  "extensions.autoUpdate": false,

  "files.associations": {
    "*.sass": "sass"
  },

  // HTML
  "html.format.enable": false,

  // CSS
  "css.remoteStyleSheets": [
    "https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.3.1/css/bootstrap.min.css",
    "https://use.fontawesome.com/releases/v5.11.2/css/all.css"
  ],
  "tailwindCSS.emmetCompletions": true,
  "stylelint.config": {
    "rules": {
      "at-rule-no-unknown": [true, {
        "ignoreAtRules": [
          "tailwind",
          "apply",
          "layer",
          "variants",
          "responsive",
          "screen"
        ]
      }],
      "declaration-block-trailing-semicolon": null,
      "no-descending-specificity": null
    }
  },

  // Javascript
  "javascript.updateImportsOnFileMove.enabled": "always",

  // PHP
  "php.suggest.basic": false,
  "php.validate.executablePath": "C:/xampp/php/php.exe",
  "namespaceResolver.sortAlphabetically": true,

  // Vue
  "vetur.validation.template": false,

  // Emmet
  "emmet.triggerExpansionOnTab": true
}
```

## Git Config
```ini
[user]
	email = yangchenshin77@gmail.com
	name = Lucas Yang
[core]
	autocrlf = true
	pager = less -r
[alias]
	cf = config
	cfl = config --list
	s = status
	a = add .
	l = log
	lo = log --oneline --graph
	last = log -1 HEAD
	c = commit
	cm = commit -m
	ca = commit --amend -m
	can = commit --amend --no-edit
	co = checkout
	cp = cherry-pick
	b = branch
	m = merge
	mnf = merge --no-ff
	rs = reset
	rs0h = reset HEAD --hard
	rs1 = reset HEAD~1
	rs1h = reset HEAD~1 --hard
	rb = rebase
	rbi = rebase -i
	rbc = rebase --continue
	rba = rebase --abort
	rm = remote
	r = remote -v
	ra = remote add
	rr = remote remove
	p = push
	pl = pull
	f = flow
	ffs = flow feature start
	fff = flow feature finish
	frs = flow release start
	frf = flow release finish
	fhs = flow hotfix start
	fhf = flow hotfix finish
	fbs = flow bugfix start
	fbf = flow bugfix finish
[init]
	defaultBranch = main
[gpg]
	program = C:\\Program Files (x86)\\GnuPG\\bin\\gpg.exe
[commit]
	gpgSign = false
[tag]
	gpgSign = false
```

## Set Git Alias
```bash
git config --global alias.cf "config"
git config --global alias.cfl "config --list"
git config --global alias.s "status"
git config --global alias.a "add ."
git config --global alias.l "log"
git config --global alias.lo "log --oneline --graph"
git config --global alias.last "log -1 HEAD"
git config --global alias.c "commit"
git config --global alias.cm "commit -m"
git config --global alias.ca "commit --amend -m"
git config --global alias.can "commit --amend --no-edit"
git config --global alias.co "checkout"
git config --global alias.cp "cherry-pick"
git config --global alias.b "branch"
git config --global alias.m "merge"
git config --global alias.mnf "merge --no-ff"
git config --global alias.rs "reset"
git config --global alias.rs0h "reset HEAD --hard"
git config --global alias.rs1 "reset HEAD~1"
git config --global alias.rs1h "reset HEAD~1 --hard"
git config --global alias.rb "rebase"
git config --global alias.rbi "rebase -i"
git config --global alias.rbc "rebase --continue"
git config --global alias.rba "rebase --abort"
git config --global alias.rm "remote"
git config --global alias.r "remote -v"
git config --global alias.ra "remote add"
git config --global alias.rr "remote remove"
git config --global alias.p "push"
git config --global alias.pl "pull"
git config --global alias.f "flow"
git config --global alias.ffs "flow feature start"
git config --global alias.fff "flow feature finish"
git config --global alias.frs "flow release start"
git config --global alias.frf "flow release finish"
git config --global alias.fhs "flow hotfix start"
git config --global alias.fhf "flow hotfix finish"
git config --global alias.fbs "flow bugfix start"
git config --global alias.fbf "flow bugfix finish"
```

## Install Global Yarn Packages

```
yarn global add @vue/cli
yarn global add eslint
yarn global add npm-check-updates
```
