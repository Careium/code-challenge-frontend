Frontend challenge
====

![](https://images.unsplash.com/photo-1573588028698-f4759befb09a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2690&q=80)

Unsplash is the internet’s premium source of freely-usable images. 
Create a nice-looking application that allows browsing of curated images from Unsplash.

# Requirements

- [ ] Use the Unsplash API - docs here to set up a developer account: https://unsplash.com/documentation.

- [ ] We want to see a grid overview, use the GET /photos/photos endpoint from the Unsplash API to get a set of images.
- [ ] The application should be responsive and work both in portrait and landscape modes, on both desktop and mobile.
- [ ] The application should support infinite scrolling using a lazy-load to fetch new images as the user scrolls.
- [ ] The user can click on a grid element to get a full-width representation of the image with additional meta data.
- [ ] The user can navigate to previous or next full-width representation without having to close that view.

# Tech requirements
- React
- Tests (we like [Jest](https://jestjs.io))
- Linter (we like [Prettier](https://prettier.io))
- CSSinJS is a plus, but not a requirement ([JSS](https://cssinjs.org/react-jss/), [styled-components](https://www.styled-components.com))


# Your challenge
- Create a React app that satisfies all the requirements listed above. If you have ideas for nice-to-have features you are encouraged to add them. Surprise us! 
- You can use any boilerplate and tools that you want to (NextJS, CRA etc) but we advice you to keep it simple. A clean, robust react app is what we're looking for, and we're usually in favor of using all available tools and tricks to get things done.
- Modern browsers, no weird legacy
- You can deploy your app on whatever cloud provider you wish (zeit, heroku, gcp etc)

# Instructions

- Fork this repo
- Build a clean and robust React app
- Publish the app on your chosen cloud provider
- Let us know that you've completed the challenge


# When we talk

We expect you talk talk about
-----------------------------

- Description of solution.
- Reasoning behind your technical choices, including architectural. 
- Trade-offs you might have made, anything you left out, or what you might do differently if you were to spend additional time on the project.
- Link to to the hosted application where applicable.

How we review
-------------

Your application will be reviewed by our engineers. We do take into consideration your experience level.

* **Architecture**: how clean is the separation of controls and data?
* **Clarity**: does the README clearly and concisely explain the problem and solution? Are technical tradeoffs explained?
* **Correctness**: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
* **Code quality**: is the code simple, easy to understand, and maintainable?  Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
* **Security**: are there any obvious vulnerability?
* **Testing**: how thorough are the automated tests? Will they be difficult to change if the requirements of the application were to change? Are there some unit and some integration tests?
	* We're not looking for full coverage (given time constraint) but just trying to get a feel for your testing skills.
* **UX**: is the web interface understandable and pleasing to use? Is the API intuitive?
* **Technical choices**: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?




# License

This project is licensed under MIT. Feel free to use it anyway you see fit.
