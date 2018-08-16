# Settingcode

## VS Code settings
```js
{
    // 工作台
    "workbench.startupEditor": "none",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.editor.closeEmptyGroups": true,
    "breadcrumbs.enabled": true,

    // Editor
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.snippetSuggestions": "top",
    "editor.formatOnPaste": true,
    "editor.mouseWheelZoom": true,
    "editor.wordWrap": "on",
    "editor.fontFamily": "Consolas, 'Courier New', monospace, 'Microsoft JhengHei'",
    "editor.tabSize": 2,
    "window.zoomLevel": 1,
    "editor.fontSize": 14,

    // Terminal (Commend line)
    "terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe",
    "terminal.integrated.rendererType": "dom",

    // 擴充功能
    "extensions.ignoreRecommendations": true,

    // Css
    "css.remoteStyleSheets": [
        "https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/css/bootstrap.min.css",
        "https://use.fontawesome.com/releases/v5.2.0/css/all.css"
    ],

    // Sass
    "files.associations": {
        "*.sass": "sass"
    },

    // Emmet
    "emmet.triggerExpansionOnTab": true,
    "emmet.includeLanguages": {
        "blade": "html"
    },

    // PHP
    "php.validate.executablePath": "C:/xampp/php/php.exe",
    "php.executablePath": "C:/xampp/php/php.exe",
    "php.suggest.basic": false,
    "php.validate.enable": false,

    // Vue
    "vetur.validation.template": false,

    // Markdown
    "markdown.preview.fontFamily": "-apple-system, BlinkMacSystemFont, 'Segoe WPC', 'Segoe UI', 'HelveticaNeue-Light', 'Ubuntu', 'Droid Sans', sans-serif, 'Microsoft JhengHei'"
}
```

## Git Alias (ycs)

* alias.cf=config
* alias.cfl=config --list
* alias.s=status
* alias.a=add .
* alias.l=log
* alias.lo=log --oneline --graph
* alias.last=log -1 HEAD
* alias.c=commit -m
* alias.ca=commit --amend -m
* alias.can=commit --amend --no-edit
* alias.co=checkout
* alias.b=branch
* alias.m=merge
* alias.mnf=merge --no-ff
* alias.rs=reset
* alias.rsp=reset HEAD~1
* alias.rsh=reset HEAD --hard
* alias.rb=rebase -i
* alias.rbc=rebase --continue
* alias.rba=rebase --abort
* alias.p=push
* alias.r=remote -v
* alias.ra=remote add
* alias.rr=remote remove
* alias.f=flow
* alias.ffs=flow feature start
* alias.fff=flow feature finish
* alias.frs=flow release start
* alias.frf=flow release finish
* alias.fhs=flow hotfix start
* alias.fhf=flow hotfix finish
* alias.fbs=flow bugfix start
* alias.fbf=flow bugfix finish

### Set Git Alias
    git config --global alias.cf "config"
    git config --global alias.cfl "config --list"
    git config --global alias.s "status"
    git config --global alias.a "add ."
    git config --global alias.l "log"
    git config --global alias.lo "log --oneline --graph"
    git config --global alias.last "log -1 HEAD"
    git config --global alias.c "commit -m"
    git config --global alias.ca "commit --amend -m"
    git config --global alias.can "commit --amend --no-edit"
    git config --global alias.co "checkout"
    git config --global alias.b "branch"
    git config --global alias.m "merge"
    git config --global alias.mnf "merge --no-ff"
    git config --global alias.rs "reset"
    git config --global alias.rsp "reset HEAD~1"
    git config --global alias.rsh "reset HEAD --hard"
    git config --global alias.rb "rebase -i"
    git config --global alias.rbc "rebase --continue"
    git config --global alias.rba "rebase --abort"
    git config --global alias.p "push"
    git config --global alias.r "remote -v"
    git config --global alias.ra "remote add"
    git config --global alias.rr "remote remove"
    git config --global alias.f "flow"
    git config --global alias.ffs "flow feature start"
    git config --global alias.fff "flow feature finish"
    git config --global alias.frs "flow release start"
    git config --global alias.frf "flow release finish"
    git config --global alias.fhs "flow hotfix start"
    git config --global alias.fhf "flow hotfix finish"
    git config --global alias.fbs "flow bugfix start"
    git config --global alias.fbf "flow bugfix finish"
