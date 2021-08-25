FROM mcr.microsoft.com/dotnet/aspnet:5.0-alpine
ARG source
WORKDIR /app
COPY ${source:-obj/Docker/publish} .