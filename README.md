# Running ASP.NET Core in Docker 

Basic usage
-----------

Building image:

    docker build -t akoken/aspnetcore .

Running container:

    docker run -d --name web -p 8080:5000 akoken/aspnetcore
