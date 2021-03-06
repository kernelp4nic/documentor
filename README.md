Documentor
==========

Documentation generation tool for Python.
Documentor scan all the source code of your project and generate a documentation 
site with the collected information of your project using Nikola.

### Documentation site for Documentor generated with Documentor:
-  [Source Code Documentation](http://diegosarmentero.github.io/documentor-docs)

## Contact

-   [Homepage](https://github.com/diegosarmentero/documentor) at github.com/diegosarmentero/documentor
-   [@diegosarmentero](https://twitter.com/diegosarmentero) at Twitter
-   [#ninja-ide](irc://freenode.net/ninja-ide) at Freenode.net (I'm always here :P)

## Dependencies

Both of these:

-   [Python](http://python.org/) >= 2.7 (Not Python3 yet)
-   [Nikola](http://nikola.ralsina.com.ar/)


## Cloning and Running

(You need to install NIKOLA first!)
You can clone this repo and simply execute:

    git clone https://github.com/diegosarmentero/documentor.git
    cd documentor
    python documentor.py -p path/to/project -o /output/path

Piece of cake, uh?
(Soon the setup.py will be ready to be able to execute this even more easily)

### Optional Arguments:

*usage:*
```bash
documentor.py [-h] [-p project] [-o Output Folder]
              [--projectname projectname] 
              [--email email]
              [--serve False/True: default False]

$documentor -p project_path -o output_path [--projectname name, 
            --email address --serve=True/False]

- "serve" can take "output" as the project which need to be served as documentation

- "deploy" take the project in nikola site generated from "output" and deploy it to Github Pages


optional arguments:
  -h, --help            show this help message and exit
  
  -p project, --project project
                        Create documentation for this project
  
  -o Output Folder, --output Output Folder
                        Place to locate the outpur result
  
  --projectname projectname
                        Project Name, if not provided the name is
                        generatedusing: documentor_PATHBASENAME
  
  --email email         email address of the project
  
  --serve False/True: default False
                        Serve Documentation site
  
  -d git-repository, --deploy git-repository
                        Git Repository to deploy content

```

## Video Demonstration

- Basic example: http://youtu.be/z9CAKfst66A
- Using Github Pages Deploy: http://youtu.be/GIJwfn5VrNE

## License

-   GPL v3
