# README

## Starship Setup

### 1. Download HackNerdFont
Font : https://www.nerdfonts.com/
-> Hack Nerd Font

### 2. Installation über WinGet
```powershell
winget install --id Starship.Starship
```

### 3. In Start Schreiben / Terminal neustarten
```
echo "Invoke-Expression (&starship init powershell)" > $PROFILE
cat $PROFILE
exit
```

### 4. Konfig anlegen
```
mkdir -p ~/.config
echo " " > ~/.config/starship.toml
```
