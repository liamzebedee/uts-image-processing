Interactive education for the UTS 32547 Image Processing subject.

 1. Install notebook environment https://github.com/jupyter/docker-stacks/tree/master/scipy-notebook
 2. Generate a password `from IPython.lib import passwd; passwd('xyz')`
 3. Allow access to notes `chmod 777 notes`
 4. Run it `docker run -v /home/liam/notes:/home/jovyan/work -p 8888:8888 jupyter/scipy-notebook start-notebook.sh --NotebookApp.password='`
 5. Have fun!
