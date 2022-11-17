# Getting Started As A Software Engineer

## Dev Environment Recommendations

> Learning to read documentation is a skill that will serve you well. I recommend trying to read documentation before going to Stack Overflow, Medium, etc. You can easily find the documentation for pretty much anything by googling it.

**Code editor:** VS Code

-   This is what you'll typically use to edit code. VS Code is the most popular code editor out there but others exist

*   Prettier is a useful extension. You can set up prettier to automatically format on save. I would also suggest enabling the bracket pair colorization setting to help you spot mismatching brackets.

**Shell:** Bash or ZSH

-   The shell is the program that runs in the terminal. I prefer ZSH because it has more useful completion. If you go with ZSH I would install [oh-my-zsh](https://ohmyz.sh/) with the [powerlevel10k theme](https://github.com/romkatv/powerlevel10k), but that is just my preference. The powerlevel10k theme gives some helpful visual indicators for git branching.
-   Bash shells will be likely be used in the vast majority of servers that you use. Being familiar with bash shells is a must. ZSH & bash are similar enough that if you're familiar with ZSH you will be good on bash shells as well

## Concepts to Learn

**Language:** I recommend learning Javascript for your first language. A lot of people may make jokes about Javascript and there is truth to them, but according to Stack Overflow's 2022 Developer Survey it was the most used language for 10 years in a row. There are a lot of jobs for Javascript & the compensation is good with the right tech company.

-   Good courses
    -   [Beginner Javascript](https://beginnerjavascript.com/) - I haven't taken this class, but I have taken other classes from Wes & thought they were good.
    -   [Javascript: The Hard Parts, V2](https://frontendmasters.com/courses/javascript-hard-parts-v2/) - This course goes into concepts that are easy to miss when learning Javascript.
-   Add on JS tech
    -   Node - Javascript was written for browsers. Node provides a run time environment that allows Javascript to run outside of a brower. It is used for most JS servers.
    -   Express - This is a framework that allows you to handle requests to your server.
    -   React/Vue/Angular - These are frameworks that make it easier to create a UI. These are useful, just make sure that you know Javascript in depth & not just the front end framework.

**Git:** Git, like most things, is typically best learned by doing. Git allows developers to collaborate on code in a controlled manner.

-   Resources
    -   [Learn git branching](https://learngitbranching.js.org/)
    -   [Atlassian's git tutorial](https://www.atlassian.com/git/tutorials) - You can ignore the parts specific to SVN, Perforce, & Bitbucket Cloud
    -   [Git documentation](https://git-scm.com/book/en/v2) - Git's documentation is hard to understand, so using some other websites may be helpful.

**Databases:** The more familiar you are with them the better. I would focus first on learning SQL because it is used in many databases.

**Shell:** The following commands are essential commands to know for bash or ZSH shells:

-   grep
-   vim
-   cat
-   less
-   cd
-   mkdir

**Writing Clean Code:**

-   Writing clean code is an essential skill for a developer. Opinions vary widely on what is "good" code. The general goal is for your code to be easy to understand, easy to maintain, and efficient. With that in mind there are a couple general concepts:

    -   Keep your functions small. A large function is hard to understand. If you break that function into multiple functions it's easier to understand.
    -   Functions should do one thing. Function names should generally start with a verb. `get`, `set`, `transform`, `process` are common verbs.
    -   Your code should be self documenting. You can make it self documenting by using good variable & function names
    -   [Write comments only when they are useful](https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/)

*   I found [Clean Code by Robert Martin](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) to give a helpful guide on how to write clean code

**Other Notes:** The Stack Overflow Developer Survey is a great reference to determine what languages you want to learn, what you can expect for compensation, and many other items.
