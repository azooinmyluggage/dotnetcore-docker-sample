FROM microsoft/aspnetcore-build
WORKDIR /app
COPY publish .
EXPOSE 80
ENTRYPOINT ["dotnet", "dotnetcoredockerenabled.dll"]
