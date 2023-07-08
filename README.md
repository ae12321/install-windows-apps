# Install Windows Apps

1. Install Chocolatey

   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
   ```

1. Install Windows apps

   ```powershell
   choco install -y chocolateygui
   choco install -y powertoys
   choco install -y git
   choco install -y tortoisegit
   choco install -y node-lts
   choco install -y python3
   choco install -y jq
   choco install -y vscode
   choco install -y sublimetext3
   choco install -y sakuraeditor
   choco install -y postman
   choco install -y treesizefree
   choco install -y fiddler
   choco install -y winmerge
   choco install -y everything
   choco install -y keepass
   choco install -y winscp
   choco install -y 7zip
   choco install -y vlc
   choco install -y discord
   choco install -y slack
   choco install -y notion
   choco install -y dbeaver
   choco install -y brave
   choco install -y steam
   choco install -y wsl2 --params "/Version:2 /Retry:true"
   choco install -y wsl-ubuntu-2004 --params "/InstallRoot:true"
   choco install -y docker-desktop
   ```
