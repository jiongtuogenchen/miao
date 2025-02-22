# [React](https://react.dev/) license npm version (Runtime) Build and Test (Compiler) TypeScript PRs Welcome
React is a JavaScript library for building user interfaces.

* **Declarative:** React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
* **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
* **Learn Once, Write Anywhere:** We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using [<u>Node</u>](https://nodejs.org/en) and power mobile apps using [<u>React Native</u>](https://reactnative.dev/).

[<u>Learn how to use React in your project</u>](https://react.dev/learn).

## Installation
React has been designed for gradual adoption from the start, and **you can use as little or as much React as you need**:

* Use [<u>Quick Start</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=Use-,Quick%20Start,-to%20get%20a) to get a taste of React.
* [<u>Add React to an Existing Project</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=Add%20React%20to%20an%20Existing%20Project) to use as little or as much React as you need.
* [<u>Create a New React App</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=Create%20a%20New%20React%20App) if you're looking for a powerful JavaScript toolchain.
## Documentation
You can find the React documentation [<u>on the website</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=the%20React%20documentation-,on%20the%20website,-.).

Check out the [<u>Getting Started</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=Check%20out%20the-,Getting%20Started,-page%20for%20a) page for a quick overview.

The documentation is divided into several sections:

* [<u>Quick Start</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=into%20several%20sections%3A-,Quick%20Start,-Tutorial)
* [<u>Tutorial</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=Quick%20Start-,Tutorial,-Thinking%20in%20React)
* [<u>Thinking in React</u>](https://react.dev/learn/thinking-in-react)
* [<u>Installation</u>](https://react.dev/learn/installation)
* [<u>Describing the UI</u>](https://react.dev/learn/describing-the-ui)
* [<u>Adding Interactivity</u>](https://react.dev/learn/adding-interactivity)
* [<u>Managing State</u>](https://react.dev/learn/managing-state)
* [<u>Advanced Guides</u>](https://react.dev/learn/escape-hatches)
* [<u>API Reference</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=Advanced%20Guides-,API%20Reference,-Where%20to%20Get)
* [<u>Where to Get Support</u>](https://react.dev/community)
* [<u>Contributing Guide</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=to%20Get%20Support-,Contributing%20Guide,-You%20can%20improve)

You can improve it by sending pull requests to [<u>this repository</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=pull%20requests%20to-,this%20repository,-.).

## Examples
We have several examples [<u>on the website</u>](https://react.dev/). Here is the first one to get you started:
```
import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
This example will render "Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax; [<u>we call it JSX</u>](https://react.dev/learn#writing-markup-with-jsx). JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML.

## Contributing
The main purpose of this repository is to continue evolving React core, making it faster and easier to use. Development of React happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements. Read below to learn how you can take part in improving React.

### [Code of Conduct](https://code.fb.com/codeofconduct)
Facebook has adopted a Code of Conduct that we expect project participants to adhere to. Please read [<u>the full text</u>](https://code.fb.com/codeofconduct) so that you can understand what actions will and will not be tolerated.

### [Contributing Guide](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=not%20be%20tolerated.-,Contributing%20Guide,-Read%20our%20contributing)
Read our [<u>contributing guide</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=Read%20our-,contributing%20guide,-to%20learn%20about) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React.

### [Good First Issues](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=changes%20to%20React.-,Good%20First%20Issues,-To%20help%20you)
To help you get your feet wet and get you familiar with our contribution process, we have a list of [<u>good first issues</u>](https://github.com/facebook/react?tab=readme-ov-file#react------:~:text=not%20be%20tolerated.-,Contributing%20Guide,-Read%20our%20contributing) that contain bugs that have a relatively limited scope. This is a great place to get started.

### License
React is [<u>MIT licensed</u>](https://github.com/facebook/react/blob/main/LICENSE).