FROM mcr.microsoft.com/dotnet/aspnet:6.0 AS base
WORKDIR /backend
EXPOSE 80

FROM mcr.microsoft.com/dotnet/sdk:6.0 AS build
WORKDIR /src
COPY . .
RUN dotnet restore
RUN dotnet publish -c Release -o /backend/publish

FROM base AS final
WORKDIR /backend
COPY --from=build /backend/publish .
ENTRYPOINT ["dotnet", "TaskManager.dll"]
