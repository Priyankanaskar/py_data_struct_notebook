## Python Data Structures and Notebooks
## P2: Employ Python Data Structures, Notebooks & Engage
**Project - Python Data Structures and Notebooks**
Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

# Objectives
This exercise is used to reinforce key Python concepts including data structures, functions, and more. It's open book, open-note, and you're encouraged to see how you can use your resources to solve specific coding issues that may arise as a data analyst. It offers practice with web-enabled Jupyter notebooks and lays some important foundations for web mining. 

# Assignment Overview
Here's a short little video showing how to do the assignments. https://use.vg/f5lawN

# It shows how to:

get the starter repo into your GitHub account. The video uses GitHub classroom, some sections will just start with a template (like forking, but disconnects from the original starter repo). 
clone down your repo to your local machine,
start up Jupyter lab (or Jupyter Notebook),
make edits to Markdown cells and Python code cells
add and commit your changes using Git
push your commit up to the GitHub repo.
export your notebook as HTML (a web page) for submission using the menu

# Task 1. Get Started
Copy the base repository into your GitHub account by selecting the "Use this Template" button on GitHub and specifying yourself as the owner.  The base repository is available at: https://github.com/wmnlp-materials/python-ds-nb/blob/main/python-ds.ipynbLinks to an external site.
On your machine, clone YOUR new repo down to your machine.
Many will use VS Code for this step - or you can use Git Bash, or if Windows, TortoiseGit or other. 

 **Verify Your Repo is Public**
Your GitHub repository must be PUBLIC to be eligible for credit. Do not submit private repository links. 

# Task 2. Open Notebook and Complete Tasks 
On your machine, open the Jupyter Notebook for editing. 
Some will use VS Code for this step - some will run jupyter lab.  Your choice. 
Required: In your Markdown introduction, add a viewable, clickable link to your GitHub repo after your name. Build your brand and make your Markdown introduction clear and professional. 
Required: Use Markdown headings  (e.g. ## Question 1) to clearly show your content by each question number. 
Complete the first task.
Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
Complete the second task.
Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
Work this way until all tasks have been completed. 

**Verify You have Added Second-Level Markdown Headings to Present Your Work**
IMPORTANT: Submissions that do not include opening information or Markdown headings (e.g. second-level with two hashes and a space) to organize and present their work will not be eligible for maximum credit. 

# Task 3. Export to HTML and Finalize Repo
Notebooks are web pages and this course involves mining the web. We can export Jupyter notebooks to HTML. This process makes our notebooks accessible as web pages, allowing them to be  shared with others who may not have Jupyter installed. The HTML web pages leverage HTML (for structure), CSS (for style), and JavaScript (for behavior).

Follow any or all of the methods below to convert your notebooks. 

Export Using Jupyter Menu

Use the Jupyter Notebook or JupyterLab interface menu:

Try: File -> Save and Export As... -> HTML 

Export Using Inline Command (in a Python Cell)

Add a Python cell at the end of your notebook, enter the following Python command (change the file name as needed), and run the cell:

!jupyter nbconvert --to html python-ds.ipynb
Export Using os Package (in a Python Cell)

Use the following code in a Python cell and run the cell:

import os
os.system('jupyter nbconvert --to html python-ds.ipynb').
Export Using a Terminal Command 

Open a terminal in the project repository root folder and run:

jupyter nbconvert --to html python-ds.ipynbAfter converting them, review the HTML pages to get idea of what data looks like when we "mine the web". You should notice a lot of angle brackets. HTML is an XML vocabulary for web pages. 

# Review The HMTL files

After converting your notebooks, review the HTML pages to get idea of what data looks like when we "mine the web".

You'll notice a lot of angle brackets. HTML is an XML vocabulary for web pages. 

Recommended: It's also a good practice to include a README.md file in your repository with instructions or information about your project, including the option you used to export to HTML. 


 
## Rubric

Each question is worth one point.
