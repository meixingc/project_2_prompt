## SEI 1003


# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: React

Let's kick it up a notch and build a modular and modern front end application using React!

Like with project one, the Unit 2 project is a chance to build a project that you can share with  future prospective employers to demonstrate your skills and evolution as a software engineer. 

You will be working individually for this project, but we will offer office hours and support via the issue queue throughout the project.

For this project, you **must** submit your idea to your squad leader in the form of a [project proposal](#pre-project-deliverable-required) by **Thursday November 3rd 9am** and the Final Product is due **Thursday November 10th 9am** at which time each student will present their project for ~10 minutes.

## Requirements

We'll be evaluating your projects against the following **hard** requirements:

1. Your app must be a working, interactive, React application.
2. It must include data from a third-party API.
3. It must use at least 4 separate components.
4. It must be deployed to the Web.
5. Your project repository must adequately document your project and feature prominently a link to the deployed app.
6. You have used git for version control throughout the project.
7. At least 2 routes and links using the React Router.
8. Use flexbox or CSS grid for layout and not floats.  

### Requirements Criteria

We will determine whether or not you've met the requirements using the following criteria.  The term **may** refers to optional criteria, while **must** or **must not** are not optional.

#### Your app must:
- [ ] **Be a working, interactive, React application.**
  - It must only use React for DOM manipulation.
  - It must not produce errors or console logs when used.
  - It must include at least two interactive features (_e.g._, the user can switch views to see more detail).
  - It should be free from extraneous `create-react-app` files or code.  Specifically, you should remove the preloaded logo.svg and unused App.css style declarations.
- [ ] **Include data from a third-party API.**
  - It must contain at least one request to an API.
  - You must use an environment variable to store any API keys if keys are required to make requests to the API you choose.  (_see_ [Storing API Keys Outside of Github](project-setup-and-deployment-guide.md#storing-api-keys-outside-of-github))
  - Your API requests **must be made over https**.  Not all APIs support https (most do). Make sure that the API you use has a url that begins with **`https://` not `http://`**. Read about [why](https://www.cloudflare.com/learning/ssl/why-is-http-not-secure/)
  - Each request must handle errors by displaying a message to the user and must not log the error to the console.
  - The data returned from the API must be used in the application.
  
  - *DO NOT PAY FOR AN API KEY FOR THIS CLASS, ONLY USE FREE ONES WHILE ENROLLED IN THIS CLASS UNLESS OTHERWISE NOTED*
  
- [ ] **Have at least 4 separate components.**
  - App.js is considered a component
- [ ] **Be deployed to the Web.**
  - It must be accessible as an application on the Web on Heroku or Surge. (_see_ [Deploying React Apps on Heroku](project-setup-and-deployment-guide.md#deploying-react-apps-on-heroku))
  - It must separately have a public **GitHub** repository containing your code.
  - You must not commit your API keys to Github. (_see_ [Storing API Keys Outside of Github](project-setup-and-deployment-guide.md#storing-api-keys-outside-of-github))
- [ ] **Use Flexbox or CSS Grid for layouts.**
  - It must not use floats for layout or depend solely upon positioning elements with fixed or absolute position.
  - It may incorporate a component library or styling framework.
- [ ] **Be adequately documented on Github.**
  - Your Github repository must contain a brief description and link to the deployed application in the "website" section at the top of the Code tab.
  - Your Github repository must contain a README.md file for documentation that is properly formatted using [Github flavored markdown](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).
  - Your Github repository  README.md must include the following sections:
    - [ ] **Description:** Describe at a high level what your project is and the motivation for the project (_i.e._, what problem(s) your projects solves) and includes a **screenshot** of the application in the browser.
    - [ ] **Technologies Used:** A list of the languages, libraries and frameworks used in your application.
    - [ ] **Getting Started/Installation Instructions:** This would likely describe how to use the application and the steps to fork, clone and run the application.
    - [ ] **Contribution Guidelines:** This section should offer guidance on where and how users can contribute to your code, identify bugs, and propose improvements.
- [ ] **Use git for version control.**
  - Your project must contain frequent, cohesive commits dating back to the **first day** of the project week.
- [ ] **Use React Router for navigation (_as needed_).**
    - If your app has navigation features, it must use React Router for the navigation.
    - It should not depend solely on the browser's navigation buttons.

> ### :triangular_flag_on_post: IMPORTANT:
> To be clear,  **your app should be built in your own Github repository**. That means that you must create a new repo on your Github account. DO NOT build your app in this repository.

## Pre-Project Deliverable (Required) 

You must make a proposal and submit it to your squad leader by Tuesday 8/17 at 9 am ET via [Github Issue](../../issues/new/choose).  Your squad leader will review and approve your proposal or meet with you to refine the scope.  Your proposal **must** include:

- A **description of the project** you'll be building with the objective described in non-technical language.
- Digitally created **wireframes** outlining the key views within your app.
- A collection of **user stories representing project MVP**.  You may include additional information about post-MVP plans for your application.
- A link to the **API** you plan to use and an **example of the data response** you will use.
- You must show your squad leader a successful API call through Postman or your Browser in order to have your project accepted!
- A **visual of your component hierarchy**. Think of the the critical states of your project and identify the data that each component will need. Optionally, indicate which components need state and which components will recieve props.
- If you plan on incorporating a component library, include a link in your proposal.

> ### :triangular_flag_on_post: IMPORTANT:
> **YOU ARE REQUIRED TO SHOW THAT YOU CAN RECEIVE THE DATA NEEDED TO SUPPORT YOUR PROPOSAL**. Try out your API in the browser or using [Postman](https://www.getpostman.com/) before you get too emotionally invested in your idea to make sure the API works the way you think it does.

Use the **[Project Worksheet](/project-worksheet.md)** in this repository to prepare your proposal.  For additional guidance in completing the worksheet, refer to the [Project Proposal Example](project-proposal-example.md).

## APIs

Below are some collections of APIs you may consider.  None of these is a comprehensive list of all APIs that are available.  Also bear in mind that some APIs on these lists may no longer be available and others **may not be suitable** for this project because they are only available via http.

While you must incorporate data from an API, you are **not required** to use any of the listed APIs.  They are provided solely as examples.

- [Public APIs | toddmotto](https://github.com/toddmotto/public-apis)
- [Public APIs | abhishekbanthia](https://github.com/abhishekbanthia/Public-APIs)
- [Public APIs | n0shake](https://github.com/n0shake/Public-APIs)
- [Public APIs | public-apis](https://github.com/public-apis/public-apis)

## Getting Unstuck

- If you don’t know a good way, try a bad way. Don't hesitate to write messy code to solve short-term problems &mdash; ***refactor later***.
- **Read the docs**. Documentation often includes tutorials or code snippets that can help you get started, and learning to read documentation is crucial to your success as a developer.
- Try explaining your problem to your [**rubber duck**](https://rubberduckdebugging.com/).  There's a lot of psychology behind talking out a problem to find a solution.  In rubber duck debugging, the idea is that when you have to explain your code your are forced to examine your code with a different part of your brain.
- Give yourself a time limit.  Generally speaking, if you haven't found a solution on your own within an hour or two, it's time to ask for help.
- Take a break.  Sometimes the best thing you can do is walk away from the computer.  Get yourself a coffee, take the dog for a walk, anything that will give you time to reset for 10 minutes.  Then when you return to the problem, reread any code or pseudocode you've already written.

## Asking For Help 

#### Instructor Support

The purpose of this project is for you to show us and future employers what you're capable of, so we want as much of the project to be your own, independent work as possible. 

Therefore, each student will be given 6 (six) tokens to ask for help. Each token will give you 20 minutes of one-on-one consultation time with an instructor. 

Tokens are redeemable during office hours or as determined by your Squad Lead outside of those hours. Tokens cannot be transferred between students - there is no black market for tokens.

**You should use this time to ask for constructive feedback or recommendations on an approach you're taking in your code or application's architecture.  Come prepared with specific questions.**

An instructor will be assigned to each engineer and will check in with you briefly every morning (whether via Slack or on Zoom). The purpose of these check-ins is NOT to discuss technical questions, but to answer questions about workflow and get a status checkin.

#### Github Issues

We strongly encourage you to file a Github issue in this repository prior to using your tokens. **Learning to communicate effectively about issues in your code essential skill as a developer.**

[Open an Issue](../../issues/new?assignees=&labels=bug&template=project-troubleshooting-request.md&title=YOUR+NAME%2C+DESCRIPTION+OF+ISSUE) by clicking the Issues tab in this repository, and then click the green `New issue` button.  Give your issue a descriptive title, answer the questions in the issue body as best as you can, then click `Submit new issue`.

Once you've submitted your issue, an instructor may:

- Ask for further clarification about the issue or what you've tried on your own.
- Provide you with links to a probable solution for you to try.
- Provide you with example code.
- Give you guidance on solving your issue.
- Recommend that you meet for a one on one to resolve your issue in person.

Once your issue has been resolved, make sure you Close the issue.

## Approach

#### 1. Plan
Spend a dedicated block of time to planning with ***wireframes*** and ***user stories*** so that your project time remains focused on producing the things that are necessary to satisfy the project requirements, and so you avoid [scope creep](https://en.wikipedia.org/wiki/Scope_creep).  Write out your [user stories](https://www.mountaingoatsoftware.com/agile/user-stories), keeping in mind that this is not a todo list but rather what specific users will want or need to do with your app. Next, critically review and pare them back to the absolute minimum necessary to satisfy the project requirements, always focusing on [Minimum Viable Product](https://www.youtube.com/watch?v=1FoCbbbcYT8).

#### 2. Follow the Thinking in React model

Once you have a solid plan for your features, follow the [Thinking in React](https://reactjs.org/docs/thinking-in-react.html) model beginning by deconstructing your wireframes into components.

#### 3. Pseudocode

Write pseudocode before you write actual code. Think through the logic step by step, breaking down the big problem into smaller, easier to solve ones.

#### 4. Review and Pivot

Review your progress daily.  Make sure to take time at the end of each day to review your progress against the list of requirements.  This will help you to better manage your time throughout the project week.


## Tips

- **Commit early, commit often.**  Don't be afraid to break something because you can always go back in time to a previous version.
- **Focus on code not design.**  You must satisfy all of the project requirements.  There are no exceptions made for really good looking projects that don't work or fulfill the project requirements.  You will have plenty of time to enhance and style your project at the conclusion of the program.
- **Don't over extend yourself.**  You have grand ideas and we want you to push yourself, but one very important skill as a developer is to never take on more work than you can complete in the allotted time. You will not get credit for great ideas.  Execution and fulfillment of the project requirements is what you will be measured on both here and in your future professional lives.

## A Note on Plagiarism

Take a moment to re-familiarize yourself with the [plagiarism policy](https://git.generalassemb.ly/sei-712/administrative/blob/master/plagiarism.md), specifically on using work you find online and on work you do with other students.
