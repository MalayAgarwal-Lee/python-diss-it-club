## Exercises for IT Club's Python Discussions

This repository contains Python exercises to try in order to advance your knowledge of Python and get some hands-on experience in writing code in Python.

To work with this repository you need to have Git installed on your PC. To install it, navigate to the official [Git website](https://git-scm.com/) and follow the directions. 

The exercises are implemented in Jupyter Notebooks. There are some direct benefits of this approach:
* It makes you comfortable in working with Jupyter Notebook, which is a fundamental tool used in many areas such as data science.
* You get to see the output of your code right where you type it and there is no additional requirement of running the code manually.
* You become more familiar with Python's **interpreted** nature directly through practice.
* You can easily trace back your steps by re-running previous cells.

### Workflow

This how you are supposed to submit your exercises for review:

(In case this seems overly technical, we'd be happy to help you out in understanding the workflow. Moreover, there will be a demonstration the first time we do this)

* Clone the repository onto your PC. To do this, open Git Bash and type this in your current working directory:

    ```console
    $ git clone https://github.com/MalayAgarwal-Lee/python-diss-it-club.git
    ```

* Create a new branch in the Git repository. To do this:

    ```console
    $ git branch <branch-name>
    ```

    For the branch name, use your first name, specify your course and your semester in `name-course-sem` format. Do not add the prefixes like 'B.TECH', if they are present in the course title, and specify the semester as only a number. For example, someone named John Doe studying B.Tech - CSE and in the second semester would type:

    ```console
    $ git branch john-cse-2
    ```

* Checkout the branch so that changes are made only in this branch. To do this, you'd type:

    ```console
    $ git checkout <branch-name>
    ```

    The branch name will be the name you gave your branch above.

* Solve the exercise in the Jupyter Notebooks.

* Add your changes. To do this:

    ```console
    $ git add <complete-file-path>
    ```

    For example, to add a file named `test.ipynb` located in your `C:` drive inside the folder, `test`, you'd type this:

    ```console
    $ git add C:/test/test.ipynb
    ```

* Commit your changes. To do this:

    ```console
    $ git commit -m <commit-message>
    ```

    The commit message is written inside inverted commas. Here, you do not need to be technical and descriptive about your changes. Selecting a commit message of your choice and using it throughout for all your commits works fine. As an example, to commit something with the commit message, `test`, you'd type this:

    ```console
    $ git commit -m 'test'
    ```

* Push your changes to GitHub. To do this:

    ```console
    $ git push origin <branch-name>
    ```

    The branch name will be the same as the name you gave to your branch when you created it. **Never push a change to the `master` branch and always make sure that you're pushing to the correct branch.**

Feel free to do the add, commit and push cycle as many times as you want to. There is no limit on this whatsoever.

Once you're completely done with your exercise and have done your final add, commit and push cycle, direct message me (Malay Agarwal) on Slack informing the same and I'll review your exercise. I'll give you pointers and suggest better ways of doing the same thing over there. There may be instances when other admins of the IT Club may review your exercise. If they do, they'll contact you through direct messages instead of me.

### Important things to know
* None of the exercises are compulsory and I do not expect you to complete all of them. It is completely your choice. They exist as an _opportunity_ and not as a compulsion.
* The review process (cloning, branching, changing, adding, commiting, pushing and pinging me) is not mandatory. You can simply clone the repository and work on the exercises, relying on things like Stack Overflow to self-check your solutions. The benefit of following the review process is that you'll get custom pointers and tips. 
* There is no grading system (of course).
* You can use Stack Overflow and other resources for your solutions. There are no constraints on that. If you do, what I suggest is searching the _concepts_ involved in the solution rather than the solution itself. This will help you develop self-learning skills and give you an incentive to explore.

### Additional notes:
* Don't hesitate to ask questions (about the exercises and the workflow, both). We are not your teachers and are your peers.
* In case you want to completely skip the technical things, you can approach me and I'll provide you the exercises in a flash drive. But, this is a good opportunity for you to get familiar with Git and GitHub, two of the most important things in many software development processes. Here's an article on the [popularity of Git and GitHub](https://www.wired.com/2015/03/github-conquered-google-microsoft-everyone-else/) to get you motivated (old, but still relevant).
* Due to lack of time, we will not be able to cover Git and GitHub. The demonstration will be limited to just getting to know this workflow, though we might decide to cover the topic in the future. In case you want to learn this skill _now_, here's a free course from Udacity, [Intro to Git and GitHub](https://in.udacity.com/course/how-to-use-git-and-github--ud775) and another one from DataCamp, [Introduction to Git for Data Science](https://www.datacamp.com/courses/introduction-to-git-for-data-science).


Thanks!

Malay Agarwal

Student Administrator, IT Club
