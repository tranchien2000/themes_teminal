1. Setting post-git and oh-my-posh (use PowerShell with Administrator )

```
Set-ExecutionPolicy RemoteSigned
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
```

2. Create $PROFILE powershell

```
notepad $PROFILE
```

- Import Module

```
  Import-Module posh-git
  Import-Module oh-my-posh
```

-set themes(Use can find themes in [ Themes | Oh My Posh ] (https://ohmyposh.dev/docs/themes) and change `them.omp.json` )

```
oh-my-posh init powershell --config 'https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/main/themes/honukai.omp.json' | Invoke-Expression
```
