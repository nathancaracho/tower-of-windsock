# The Tower of Windsock

## What is this

That is a space when I`ll make some **☣ - Experiences** or create little articles, talking about things I love like **λ - Functional programming**.

## How I make it

Before I need tell a little history because I chose this stack.  
Once upon a time a magic software builder called Microsoft created a magic artifact called [Microsoft interact](https://devblogs.microsoft.com/dotnet/). The artifact holder have a big power of... make same stuff than jupyter notebook with little advantages like the communication between different languages in same notebook and VS Code facilities, but I preferred use some magic artifacts already works, [Jupyter lab](https://jupyterlab.readthedocs.io/en/stable/#), than use another is on preview version and not works so well.

Microsoft Interact is a cool tool and I use it for some proof of concept or test some complex logic, because you don't need mess of folder or any fsproj/csproj just write and run, but have problems like is hard to share because .Net environment is so heavy or VS Code insiders instability, so because this problems I chose [jupyter notebook](https://jupyter.org/). 

Wait a second, but to use [jupyter notebook](https://jupyter.org/) you still need a environment, how to share the code without local environment? Using another magic artifact called [Docker](https://www.docker.com/).  
A container is a isolated packing oftware with yours dependencies and [Docker](https://www.docker.com/) is a open source platform to admin and create isolate environment using [Linux Containers](https://linuxcontainers.org/pt_br/), so with [Docker](https://www.docker.com/) container you have a isolate **SO** but sharing the same **Kernel** between **Host** and **Containers**.
With [Docker](https://www.docker.com/) is easy to create a isolate environment and share it, because you only need share the "configuration" files Dockerfile or docker-compose.yml and this is exactly what I did.


**The experiences ☣**

* [Different ways to make a query on mongoDB with C#](https://github.com/nathancaracho/tower-of-windsock/blob/master/experiences/MongoDbQueries.ipynb) ⚙ **WIP**

**λ - Lambda Saga**
* [Currying](https://github.com/nathancaracho/tower-of-windsock/blob/master/lambda-saga/currying.ipynb) ⚙ **WIP**
