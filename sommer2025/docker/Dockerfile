FROM mcr.microsoft.com/dotnet/sdk:8.0 AS build

ENV APP_HOME /app
WORKDIR $APP_HOME

COPY . .

RUN dotnet build

EXPOSE [5050, 49670]

CMD ["dotnet", "run"]
