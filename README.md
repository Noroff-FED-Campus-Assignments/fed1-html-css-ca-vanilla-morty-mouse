[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/e-_62uB-)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16716404&assignment_repo_type=AssignmentRepo)

# FED Exam - Vanilla Front-end Website

This bootstrap template is intended to help you deliever a amazing website which delights your end-users. Feel free to change, remove or start your own project from scratch. Please replace any text which starts with an `_`. This read me should be updated with your relevant details and not just copy pasted here.

## Resources

<!-- You must replace these links -->

- [Brief]https://docs.google.com/document/d/1Y3kgttkD0sMGaSDMzgDT8HfeI7yXfWN5i_FfY8xkKII/edit?usp=sharing
- [Design](https://www.figma.com/design/T03mrrQUO73HTumxTTObKm/Ca-assignment?node-id=0-1&node-type=canvas)
- [Production deploy](https://morty-gamehub.netlify.app)
- [Deployment CI](https://app.netlify.com/sites/morty-gamehub/overview)

## Deployment

Your deployment is done via static hosting provider (Vercel is recommended).
You can update your deployment pipeling by editing the [vercel.json](https://vercel.com/docs/concepts/projects/project-configuration).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FS3ak%2Ffed1-exam-vanilla-frontend-website&env=API_TOKEN,API_SECRET&envDescription=The%20API_TOKEN%20is%20needed%20to%20access%20a%20secure%20API%20endpoint.%20This%20can%20be%20the%20Authorization%20%60Bearer%20Token%60%20header%20used%20to%20make%20queries.&envLink=https%3A%2F%2Fvitejs.dev%2Fguide%2Fenv-and-mode.html&project-name=exam-front-end&repository-name=fed1-exam-vanilla-frontend-website&skippable-integrations=1)

## Report

Writing my design in HTML and CSS has been a challenging experience, where the learning outcome has been good. The process has been both challenging and fun. Whenever I have met an obstacle it has been possible to overcome it through trial and error. However, some things have not been possible to achieve without using Javascript, and thus been outside the scope of this assignment. For example this became evident when trying to style one particular “select” element, which can be found on the store page of my design.

That being said, I do feel like I could have achieved more with the time we were given. Even though we’ve had ample time to complete this assignment, I’ve been feeling stretched for time, and I know that there are still improvements that can be made to the design. Due to some unfortunate personal events that collided with this, I’ve been more preoccupied than I would have hoped for during this week. However, that is no excuse, and I do feel like I’ve accomplished satisfactional work with the time I’ve used.

At one point I managed to delete my repository, due to a severe misunderstanding of how it really works. I wanted to switch the commit location, and thought I could just delete the repository on Github. In doing so, my whole project got deleted, and I feared the worst. Luckily I managed to retrieve the code due to sheer luck, but all the images needed to be added anew.

Key takeaways:

Media queries:
Media queries have been the building stone to create a responsive website. I started out coding my design for mobile view. Only after completing all pages on mobile did I begin to think about tablet and desktop. Looking forward, I might make each page fully responsive before moving forward to the next on future work.

Another challenge has been to decide which width to set the breaking points. Using the developer tool on chrome, I found that the Ipad mini starts at 768px width, so this became my tablet view. After that I decided to make 1280px my desktop breaking point.

Initially, all media queries were located at the bottom of my CSS as a structure. However, as time progressed and I felt short with time, I put them underneath the original class in CSS. To be honest, I’m not sure what I like the most, but I think that keeping media queries straight underneath its element in CSS makes sense.

Dry:
In future projects, I will keep the concept of DRY at the top of mind continually as it becomes more and more challenging the more lines of code I write. I’m certain that some code could be merged, specifically on this project relating to max-width on media queries.

Images:
Looking back, what I found to be the most difficult was styling images and making them responsive. I found that styling images with grid and flexbox work a little bit different, which became a source of frustration. At one point I was satisfied, only to find that every image looked wrong when I put anchor tags on it.

Additionally, some places needed images with greater size than 300kbs because it simply looked too grainy. This is typically the banner photos at the desktop view.

In summary, I’ve learned a lot about some key challenges and how to better face them in future projects. I feel confident that my work will be even better next time. Additionally, when we learn Javascript I’m looking forward to making even more complicated designs.

Sources:

The read more section has been taken from: https://codepen.io/Idered/pen/ExYROd
Some styling has been taken from: https://open-props.style/

## Getting Started

In the project directory, you can run:

- Run index html with dev server

## Minimum acceptence criteria

All of these todo's must be done to pass the asssignment.

- [x] The project has a readme with a link to the live site and a link to the figma design.
- [x] The project has an publically accessible git repository.
- [x] The project has a live site (Can be hosted on Netlify or vercel for free).
- [x] The project has a rationale document that explains the design decisions you made.
- [x] Your last commit must be before your deadline.
- [x] You may use a build tool such as Vite, Parcel but not a framework like Gatsby or Next.js.
- [x] The project has been submitted on Moodle

## Checklist

Make sure you go through this checklist before submitting your project to Moodle.

- [x] All pages have a meta description.
- [x] All pages have a valid title.
- [x] All pages import the correct css files.
- [x] All pages import the correct JS file.
- [x] Input fields have the following attributes;
- [x] All images have an alt tag;
  - [x] A name,
  - [x] A placeholder,
  - [x] A aria-describedby,
  - [x] Required
- [x] I have not copied Javascript code.
- [x] I have not used a Javascript library.
- [x] Removed all unused files.
- [x] Named all images properly.
- [x] Committed all my code to github.
- [x] My repo is publically viewable.
- [x] I've submitted/ written a report.
- [x] I've removed all todo notes in code.
- [x] I've removed all console logs in code.
- [x] Code is formatted correctly.
- [x] There are no red underlines in VSCode.
- [x] There are no error messages in the terminal when I run the project.
- [x] My code is indented correctly.
- [x] I've checked my report for grammer & spelling using grammerly or chatGPT
- [x] I've used used [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [x] I've checked off every todo in this README.

## Brief

You need to deliver a properly functioning, responsive website for the assignment brief that you chose in Design 1 (This is your Figma design).

The site needs to have every page (Scene) listed in the site architecture on your chosen brief. Certain functionality that requires JavaScript can be mimicked for now, for example a log in page could link across from the ‘Sign in’ button.

The HTML should be semantic and neat.
The CSS should follow the DRY principle and be easy to read.
The website should be responsive and look good at every screen size starting from 320px with no horizontal scrollbars. Use Flexbox and CSS Grids where appropriate. Please do not use a CSS framework like Bootstrap, we want to see that you can build responsive sites without the help of a framework.
The site should be WCAG compliant and accessibility taken into account.
Each page should have a unique meta description, title, and h1.
You should not use copied code in your submission. All code submitted must be written by you. You may use external sources to show you how to achieve specific effects, and these should be included in your report.
You are allowed to use external libraries such as animation.css or open-props, but you must include quote them in your submission.

## Help & Tutorials

- https://web.dev/learn/forms/
- https://fed-vocational-astro-course.vercel.app/en/html-css/module-2/forms

## Application stack

- [Prettier](https://prettier.io/) - An opinionated code formatter
- [Eslint](https://eslint.org/) - Find and fix problems in your JavaScript code

## Authors

- Morten Lillehaug (@Mortmeister)
- Monde Sineke (@S3ak)
