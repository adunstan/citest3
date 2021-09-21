# escape `

# !IMPORTANT!
# * Pass -m 2GB (or more) when building the image.
# * Configure Docker to use disks larger than the default 20 GB.
FROM cirrusci/windowsservercore:2019

SHELL ["powershell", "-NoLogo", "-NoProfile", "-Command"]

RUN setx PATH "c:\foo;\$Env:PATH" /m
