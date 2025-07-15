# Use a base image with tzdata installed
FROM mcr.microsoft.com/dotnet/aspnet:8.0-jammy-chiseled-extra as base

EXPOSE 80
WORKDIR /app
COPY . .
ENTRYPOINT ["dotnet", "%%appName%%"]
