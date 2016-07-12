FROM microsoft/dotnet:latest

MAINTAINER Abdurrahman Köken

RUN mkdir /app

COPY /app /app

WORKDIR /app

RUN ["dotnet","restore"]

RUN ["dotnet","build"]

EXPOSE 5000/tcp

ENTRYPOINT ["dotnet","run"] 