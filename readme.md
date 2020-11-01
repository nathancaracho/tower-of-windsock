
# The Tower of Windsock

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nathancaracho/tower-of-windsock/HEAD)

## What is this

That is a space when I`ll make some **☣ - Experiences** or create little articles, talking about things I love like **λ - Functional programming**.

## The Stack

### Development languages

As development languages I'll use basically [C#](https://docs.microsoft.com/dotnet/csharp/) and [F#](https://docs.microsoft.com/dotnet/fsharp/). **C#** or **CSharp** is a current Microsoft main language, easy to learn basic  concepts c# is an elegant object oriented language, most used in corporative softwares but is so versatile can use in another many cases like game development with [Unit Engine](https://unity.com/). Now **F#** or **FSharp** is a beauty Functional first language, in another words **F#** not only Functional like Haskell it can used as Object Oriented too that mean is possible have interoperability between **C#** and **F#**. Different than **C#**, **F#** not is use on big scale softwares **yet**, **F#** is versatile can be used in a big variance of softwares like [Jet.com](https://en.wikipedia.org/wiki/Jet.com) used in own Marketplace or in Data science with [SciSharp](https://scisharp.github.io/SciSharp/).

### Environment

Obviously I'll use .NET framework but with a new feature [Microsoft Interact](https://github.com/dotnet/interactive). The [Microsoft Interact](https://github.com/dotnet/interactive) is basically a bunch of tools to give for .NET Framework a interactive power with [REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop) or interactive notebooks, including F# and C# jupyter Kernels. So that way is possible combine .NET Framework with Jupyter Notebooks and share it without code compilation or local environment necessity.  

Other important environment is the [Jupyter project](https://jupyter.org/). This is open source project to allows create and share interactive document, mixing live coding, charts and markdowns. Use [Jupyter kernels](https://jupyter.readthedocs.io/en/latest/projects/kernels.html) to interpreting different languages and [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/) as a incredible and customized, by extensions, web based UI.  

Now to support all those environments the [Docker](https://www.docker.com/). Basically [Docker](https://www.docker.com/) is a open source platform to admin and create isolate environment using [Linux Containers](https://linuxcontainers.org/pt_br/) and a **container** is a isolated packing software with yours dependencies. With [Docker](https://www.docker.com/) is easy to create a isolated environment and share it, because you only need share the **"configuration files"** or use some cool cloud service like [My Binder](https://mybinder.org/) to host your notebooks with your environment, in another words you just share the cookbook not the food.

## Why use this stack?

Once upon a time a magic software builder called Microsoft created a magic artifact called [Microsoft interact VS Code](https://devblogs.microsoft.com/dotnet/net-interactive-preview-3-vs-code-insiders-and-polyglot-notebooks/). The artifact holder have a big power of... make same stuff than jupyter notebook with little advantages like the communication between different languages in same notebook and VS Code facilities, but I preferred use some magic artifacts already works, [Jupyter lab](https://jupyterlab.readthedocs.io/en/stable/#), than use another is on preview version and not works so well. Ok.. That is not full truth, I'm yet using [Microsoft Interact](https://github.com/dotnet/interactive) but without VS Code Insiders, but using **F#** and **C#** Kernel.
But we has the environment problem yet, so to resolve that problem I used another magic artifact, the [Docker](https://www.docker.com/). That way is easy to share the environment by a **cookbook** and build it locally or use a cool service like [My Binder](https://mybinder.org/) to host the notebooks.  

## How to use ##

To read the articles you have three possibilities, first  you can click on [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nathancaracho/tower-of-windsock/HEAD) in this doc head, this button will redirect you one folder with all **jupyter notebooks** files, just chose one and have fun.  Other way is click on [Notebooks Links](#Notebooks-Links), this links will redirect you to  specific notebook My Binder Page.  
The last way is using **Docker**, just fallow the instructions below:
1. On project directory root run the command `docker-compose up`.

***And just that...*** 
Now a link you be generated after image build, click on link and enjoy it. 


### Notebooks Links ###

**The experiences ☣**

* [Different ways to make a query on mongoDB with C#](https://github.com/nathancaracho/tower-of-windsock/blob/master/experiences/MongoDbQueries.ipynb) ⚙ **WIP**

**λ - Lambda Saga**

* [Currying](https://mybinder.org/v2/gh/nathancaracho/tower-of-windsock/HEAD?filepath=experiences%2Flambda-saga%2Fcurrying.ipynb) ⚙ **WIP**
