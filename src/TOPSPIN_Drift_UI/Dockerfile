FROM microsoft/aspnetcore:1.0.1
ARG source
WORKDIR /app
EXPOSE 80
COPY ${source:-bin/Release/PublishOutput} .
ENTRYPOINT ["dotnet", "TOPSPIN_Drift_UI.dll"]
