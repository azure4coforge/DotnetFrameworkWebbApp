
# Use the official Microsoft IIS base image
FROM mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-ltsc2022

# Set the working directory inside the container
WORKDIR /inetpub/wwwroot

# Copy the published application files to the container
COPY ./publish/ .

# Expose the required port
EXPOSE 80
