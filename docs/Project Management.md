# 2. Project Management


## The Assignment
&nbsp;


- Build a personal website describing you and your final project.
- Work through a git tutorial.

&nbsp;

## Building the Website 
&nbsp;

To build my personal website for the final project documentation, I needed to learn a few tools and plataforms to make it possible. As my work team are also taking the Fab Academy course, we agreed to create a pattern for the projects documentation. And to do it, we researched and indentified the following needed tools to build the website:

- **Git**: An open-source version control system used for creating a history of changes in the source code of software's development project.
- **GitHub**: A remote repository hosting service workins as an online Git.
- **Markdown**: A "text-to-HTML conversion tool for web writers" according to Jon Gruber, its creator. It is a tool that allows writing using plain text, converting it to a valid XHTML structure..
- **Mkdocs**: A static website generator for building project documention. Its source files are written in Markdown and set in a single YAML configuration file.

Both Git and Github I already used a few times before. I learned a little about version control with Git and Github in a course on [Alura](https://www.alura.com.br/curso-online-git-github-controle-de-versao), a online courses platform. But I never used Markdown and Mkdocs before, despite having already heard about them. During the website building process I learned how to use them, discovering and testing about the functions, tools, etc.

Following are the steps I took to create the documentation website for my Fab Academy projects.

### Installing Python, Git and Mkdocs

1. Download the most recent version of [Python](https://www.python.org/downloads/).
2. Install it. The instalation process is straight foward.
3. Repeat the same process with [Git](https://git-scm.com/downloads)
4. With Git installed, it will be able to access a terminal called **Git Bash**.
5. Open it and type the following command:

    ``` 

    $ python --version

    ```
    
6. If the installation process worked you should see the Python version installed, as shown bellow:

    ``` 

    $ python --version
    Python 3.8.2

    ```

7. Check if the [Pip](https://pypi.org/project/pip/) command is avaiable by typing the following:

    ``` 

    $ pip --version

    ```

8. If you have it, the terminal will return the following information:

    ``` 

    $ pip --version
    pip 21.1.2 from c:\program files\python39\lib\site-packages\pip (python 3.9)

    ```
    
     Usually Pip is installed during Python installation process.