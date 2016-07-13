# Running ASP.NET Core Application in Docker 

Basic usage
-----------

Building image:

    docker build -t akoken/aspnetcore:1.0 .

Running container:

    docker run -d --name web -p 8080:5000 akoken/aspnetcore:1.0
