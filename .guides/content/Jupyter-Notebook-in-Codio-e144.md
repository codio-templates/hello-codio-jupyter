##

### Creating a Jupyter assignment

General instructions for creating projects/assignments in Codio may be found [here](https://docs.codio.com/develop/develop/projects/create-import-project.html#create-or-import-a-project). 

You can use the **Jupyter Starting Point**, the included technology [stack](https://docs.codio.com/develop/develop/stacks/stacks.html#stacks) contains the software you need for Jupyter labs.

![In the dialog for creating an assignment you will click on the tab that says Jupyter Starting point and type the name of the lab file in the name field](.guides/img/jupyterstart.png)

To inform Codio that you will be using nbgrader you must have a file name `.codio-jupyter` in your file tree, more information [here](https://docs.codio.com/instructors/teaching/grading/nbgrader.html#auto-grade-with-nbgrader). When a student marks their work as complete the Jupyter Notebook is sent to nbgrader for autograding. As you will see in the setup on the next page, it is prudent to tell students to **Save and Checkpoint** their work before they mark as complete to prevent timing issues that can occur when accessing the Jupyter Notebook server.


### Auto-opening the Jupyter Notebook

You can use Codio guides to auto-open Jupyter Lab. The next page is an example lesson that is set up as below. There is also some "teacher only" information on the page. To see that information you need to [view it as a teacher](https://docs.codio.com/instructors/setupcourses/preview-course.html#preview-assignment-as-teacher).

1. Select **Layout**.
1. Create a **2 Panels** layout.
1. In the tabs field you select the JupyterLab type and enter your file name.
1. Click **Save and Close Settings**.

![The layout to select has two panels and in the tab section you select the Jupyter lab type and enter the file name.](.guides/img/jupyterlab.png)


### Collapsing the Guide on open

If you prefer for the guide page to be collapsed when the student opens the assignment to provide more screen space for the Notebook, these are the steps:
1. Select **Settings**
1. Toggle **Collapsed on Start**
1. Click **Save and Close Settings**

![The settings button is in the upper right corner of the display to the right of the Layout button. The Collapsed on Start button is the third button down in the right section of the dialog. The Save and Close Settings button is in the lower left corner, to the right of the cancel button.](.guides/img/collapse.png)

### Manually grading Jupyter Notebooks
If you want to manually grade a Jupyter Notebook you can turn on Teacher grading in [Grade Weights](https://docs.codio.com/instructors/setupcourses/assignment-settings/grade-weights.html#grade-weights) and then open student projects to [view their work](https://docs.codio.com/instructors/teaching/viewstudentwork.html#viewing-student-work).


### Viewing Solutions and Hidden tests

When you are editing your Jupyter assignment you can see solutions and hidden tests (first image) but when your students open the assignment, they will not see those things (second image).

## Teacher view of a Jupyter Notebook
![The teacher view of a Jupyter Notebook shows the solution along with all the tests including the hidden ones.](.guides/img/jupyterteacher.png)


## Student view of a Jupyter Notebook
![In the student view of a Jupyter assignment the solution is replaced with text that reads "Your Code Here". The student can only see the visible tests.](.guides/img/jupyterstudent.png)