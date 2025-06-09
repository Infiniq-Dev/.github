# This is Infiniq-Dev note

## Create SSH key

```powershell
ssh-keygen -t ed25519 -C "<name>@infiniq.co.kr"
Get-Content $env:USERPROFILE\.ssh\id_ed25519.pub | Set-Clipboard
```

Go to [Settings](https://github.com/settings/keys) -> New SSH Key
Put the key from clipboard in there.
