# Hypothetical Development Task

## Task
Our Equatio product takes typed Mathematical equations and converts them into images using our public API, for example:
[https://equatio-api.texthelp.com/svg/x+1](https://equatio-api.texthelp.com/svg/x+1)

We want you to create a single HTML page which allows users to type mathematical formulae into an input box and press a button to send the input to our API. The resulting image returned by the API should be displayed to the user on screen.

Assume that the user is using the latest version of one of: Edge, Firefox or Chrome.

Here are some sample Maths equations to work with:

| Input Formula  | Expected API URL                                                |
|----------------|-----------------------------------------------------------------|
| x+1            | https://equatio-api.texthelp.com/svg/x%2B1                      |
| x^2            | https://equatio-api.texthelp.com/svg/x%5E2                      |
| 15+\frac{2}{3} | https://equatio-api.texthelp.com/svg/15%2B%5Cfrac%7B2%7D%7B3%7D |

## Things to think about...
- Offline support & fallbacks
- Code Simplicity
- Javascript tooling
- Accessibility

## Purpose
The point of this task is to see if you can demonstrate some technical ability with modern Javascript technologies and tools.  Also to see if you understand the design approach to structuring a client-side NodeJS project.  We understand this isn’t a lot of information and there is a lack of user stories but please do your best.

## Deliverables
ONE HTML page, with CSS.
A usage of one or more Javascript build tools (NodeJS, Webpack, Rollup, Babel, TypeScript, etc.) or frameworks (React, Vue, Angular, etc.)
A public GitHub repository containing all of your code & changes for the project