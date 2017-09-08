FROM microsoft/aspnetcore-build
WORKDIR /app
COPY publish/dotnetcoredockerenabled .
ENV ASPNETCORE_URLS=http://+:8080
EXPOSE 8080
ENTRYPOINT ["dotnet", "dotnetcoredockerenabled.dll"]
