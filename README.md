# Getting Started As A Software Engineer

## Dev Environment Recommendations

> Learning to read documentation is a skill that will serve you well. If you are trying to learn about how to connect to an API, use a library, or syntax for a specific language reading the documentation is the best place to start. If you hit an error that you're not familiar with or just aren't sure how to do something then StackOverflow can be a good resource.

**Code editor:** VS Code

-   This is what you'll typically use to edit code. VS Code is the most popular code editor out there but others exist

*   Prettier is a useful extension. You can set up prettier to automatically format on save. I would also suggest enabling the bracket pair colorization setting to help you spot mismatching brackets.

**Shell:** Bash or ZSH (not Windows PowerShell)

-   The shell is the program that runs in the terminal. I prefer ZSH because it has more useful completion. If you go with ZSH I would install [oh-my-zsh](https://ohmyz.sh/) with the [powerlevel10k theme](https://github.com/romkatv/powerlevel10k), but that is just my preference. The powerlevel10k theme gives some helpful visual indicators for git branching.
-   Bash shells will be likely be used in the vast majority of servers that you use. Being familiar with bash shells is a must. ZSH & bash are similar enough that if you're familiar with ZSH you will be good on bash shells as well

## Concepts to Learn

**Language:** I recommend learning Javascript for your first language. A lot of people may make jokes about Javascript and there is truth to them, but according to Stack Overflow's 2022 Developer Survey it was the most used language for 10 years in a row. There are a lot of jobs for Javascript & the compensation is good with the right tech company. JavaScript is commonly used in both the front end & back end.

-   Free Resources:
    - [This Reddit thread](https://www.reddit.com/r/learnjavascript/comments/w4tlz7/whats_the_best_website_to_learn_js_on_for_free/) has a list of free resources  
    - [Was Bos's Javascript 30](https://javascript30.com/) is a Javascript course that goes over interacting with the web page & assumes you have Javascript experience.
    - MDN - MDN has _great_ docs & should be utilized over Medium & other websites if you have a questions about a Javascript specific thing. If you don't understand it after reading MDN then reading Stack Overflow can sometimes help
    - Stack Overflow - If you have a more generic question or you hit an error in your code that you don't know how to solve, google it! Stack Overflow will likely be the site that has the most helpful answer. Try to understand the answer & not just copy & paste it.
    - You can always just start with an idea of something to code & use MDN to learn. Some useful items to google:
      - To make a website - "How to make a beginner React and Express website" (this will use Node on the back end)
      - To make some sort of automation that doesn't have a UI - "How to write a Node program for beginners"
-   Good paid courses
    -   [Beginner Javascript](https://beginnerjavascript.com/) - I haven't taken this class, but I have taken other classes from Wes & thought they were good. Use code JAVASCRIPT30 for $10 off
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

**Databases:** The more familiar you are with them the better. I would focus first on learning SQL because it is used in many databases. There are two categories of databases: SQL & NoSQL. NoSQL databases are easier to learn in my opinion, but SQL is an integral component of being a full stack engineer. Here are the most popular ones:
-   MongoDB: NoSQL
-   Postgres: SQL

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

*   I found [Clean Code by Robert Martin](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) helpful as a guide on how to write clean code, but it requires an understanding of Java

**Other Notes:** The Stack Overflow Developer Survey is a great reference to determine what languages you want to learn, what you can expect for compensation, and many other items.
