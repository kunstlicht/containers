FROM microsoft/nanoserver
MAINTAINER "Michiel Vermeir"
LABEL Description="keybase" Vendor="keybase"
RUN powershell -Command Invoke-WebRequest -Uri https://prerelease.keybase.io/keybase_setup_386.exe -OutFile keybase.exe
CMD ["./keybase.exe", "/install", "/passive", "/quiet"]
