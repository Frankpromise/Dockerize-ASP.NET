FROM mcr.microsoft.com/dotnet/sdk:7.0
WORKDIR /app
COPY bin/Debug/net7.0/publish .
ENV ASPNETCORE_URLS http://+:5000
EXPOSE 5000
ENTRYPOINT ["dotnet", "app.dll"]