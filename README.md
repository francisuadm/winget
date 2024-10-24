# winget




### Allow to use winget command

````
REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\AppInstaller" /v EnableExperimentalFeatures /t REG_DWORD /d 1 /f
REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\AppInstaller" /v EnableAppInstaller /t REG_DWORD /d 1 /f
REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\AppInstaller" /v EnableHashOverride /t REG_DWORD /d 1 /f
REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\AppInstaller" /v EnableMSAppInstallerProtocol /t REG_DWORD /d 1 /f
````

#### Dell Coomand | update

````
winget install Dell.CommandUpdate  --scope machine --disable-interactivity --force -h
````



#### Alternative to Snagit

````
winget install Greenshot.Greenshot --scope machine
````


#### DisplayLink

````
winget install DisplayLink.GraphicsDriver --scope machine --force
````

#### CPUID

````
winget install --id CPUID.CPU-Z --scope machine --disable-interactivity --force -h
````

#### OBS Studio

````
winget install --id OBSProject.OBSStudio --scope machine --disable-interactivity --force -h
````


