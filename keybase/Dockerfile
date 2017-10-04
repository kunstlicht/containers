FROM microsoft/windowsservercore
LABEL author="Michiel Vermeir"
LABEL description="keybase" 

RUN powershell -Command Invoke-WebRequest -Uri https://prerelease.keybase.io/keybase_setup_386.exe -OutFile installer.exe -Verbose -TimeoutSec 10
RUN installer.exe /install /passive
CMD keybase --version
