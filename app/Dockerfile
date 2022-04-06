FROM mcr.microsoft.com/windows/servercore:ltsc2022
ADD https://www.python.org/ftp/python/3.10.4/python-3.10.4-amd64.exe .
RUN python-3.10.4-amd64.exe /quiet InstallAllUsers=1 PrependPath=1 Include_test=0
ENTRYPOINT python -m http.server
