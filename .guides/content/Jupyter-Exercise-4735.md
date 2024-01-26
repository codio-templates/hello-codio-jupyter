## Instructions

- Complete the exercises in the Jupyter Notebook.
- You can collapse this window using the collapse button in the upper left corner of this pane.
- Once you are done, click the **Mark as Complete** button at the bottom of this panel, or select **Education->Mark as Complete** from the menu.
- If you need to revisit your work, select **Education->Mark as Uncompleted"**.



|||guidance
## Allowing students to toggle Mark as Complete

In the instructions above it tells students how to "Mark as Uncompleted", instructors need to enable this feature for students, it's not available by default. More information may be found in the "[Visibility on Completed](https://docs.codio.com/instructors/setupcourses/assignment-settings/visibility-completed.html#visibility-on-completed)" section. 
|||

|||important
## Save your work

Before marking your work as complete - Save and checkpoint
![Students can save their work by clicking on the icon that looks like a disk. It is the left most icon in the icon bar, underneath the file menu.](.guides/img/checkpoint.png)

|||

|||guidance

<details>
  <summary>Solution</summary>
  
  ```python
def squares(n):
    """Calculates and returns a list of squares from 1 to n"""
    answer= []
    for i in range(1, n+1):
        answer.append(i ** 2)
    return answer

print(squares(5))
  ```
</details>

|||