# IBM Cloud Garage Learning Standards

## Computer Setup (Before Class)

In order to complete the course, you need several pieces of software installed.

**Mac is better than Windows for Cloud Garage Development**

If you have the choice, get a Mac. It will greatly simplify your life. It should take about 30m to install everything on your Mac.

If you have Windows, you must use WSL. It will take several hours to install WSL plus the required libraries on your Windows machine.

Please plan for this and set up your machines _before_ class.

### Windows Users

- [Windows Setup Guide](computer-setup/windows.md)

### Mac Users

- [Mac Setup Guide](computer-setup/mac.md)

## Prerequisites

Before joining class you should already be able to do the following things:

- Personal Computing Skills
  - Make windows full-width / full-height but not full screen with a key command
  - Recover from making windows full-screen
  - Split windows left and right (half screen)
  - Install applications
  - Switch between windows and applications with keyboard
- Command Line
  - Change directories (up, down)
  - Describe how PATH works
  - Change PATH in .zshrc
  - Determine if an executable is in path with which
  - Print the working directory
  - List the contents of a directory
  - Move and copy files
  - Navigate history using arrow keys and history command
  - Clear the screen using both `clear` and `CMD+K`
  - Create and edit a file at the command line using touch and vim

## Learning Standards

By the end of this course you should be able to demonstrate the following skills:

- Basics
  - VSCode
    - LiveShare - both host and guest
    - Create files in the correct directory / move files
  - Git
    - [Clone a Gogs repo](./gogs-authentication.md)
      - Add / commit / pull / push changes
      - Resolve merge conflicts visually in VSCode
      - Restore files you don't want to commit
      - Create branches, make commits on branches and push code to branches
      - Create pull requests and merge pull requests
      - Explain the add/commit/push flow including untracked files
- Building Applications
  - HTML/CSS
    - Build HTML forms with labels attached to inputs
    - [Link CSS files](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link)
  - JavaScript
    - Write code with functions, including ES6 functions
    - [Solve basic algorithms with loops, variables, data types, conditional statements](https://education.launchcode.org/intro-to-professional-web-dev/chapters/loops/accumulator-pattern.html)
    - [Parse](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse) and [generate](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify) JSON
    - Use browser APIs such as [localStorage](https://www.htmldog.com/guides/javascript/advanced/localstorage/)
  - React
    - Build components with correct casing of files / component names / import / export syntax
    - Write valid JSX including className, htmlFor, expressions in interpolation
    - Create and render lists of elements
    - Conditionally render elements
    - Write components that have state, form fields and events that update state
    - Use an efficient developer workflow (run and watch tests, run the app)
    - Create new React applications
    - Describe how single-page applications work
  - Testing in JavaScript
    - Describe the 3 parts of a test (SEA / PRE)
    - Write valid test / describe / it (at least "test") blocks
    - Use expect along with Jest matchers to write assertions
    - Describe what to test (using ZOMBIES?)
  - Testing in React
    - [Use testing library methods to fill in fields, click buttons, assert](./react/testing.md)
    - Run and watch tests with npm test
- Devops
  - Docker
    - Explain images and containers
    - [Create a Dockerfile containing nginx and build it](./react/docker.md)
    - Run a container in the foreground, mapping ports
    - List images and containers
    - Show running containers
    - Pull and push images
  - Kubernetes
    - Explain and diagram common K8s object including
    - Describe K8s including things like etcd and the control plane
    - Use the command line to debug an application using get, describe, logs...
  - OpenShift
    - Explain the relationship between OpenShift and Kubernetes
    - [Login to oc locally using the UI to get the token](./openshift/cheatsheet.md)
    - Describe projects and how they relate to kubernetes
  - Helm
    - Create a basic Helm chart
    - Modify a default helm chart to work on the class's OpenShift cluster
  - CI
    - [Write a sequence diagram of CI](./ci-cd/continuous-integration.md)
    - Setup a Tekton pipeline and make it pass for a React application
  - CD
    - Sequence diagram CD with Gitops
    - [Setup an Argo project manually in the UI](./ci-cd/argo.md)
- Process
  - Design Thinking
    - Explain what design thinking is and how it fits into the flow
  - XP
    - Describe inceptions, including when they happen, and what happens in them
    - Describe an IPM, including when it happens, and what happens in them
    - Describe standups, including when they happen, and what happens in them
    - Describe retros, including when they happen, and what happens in them
    - Explain what a backlog is and how it's managed including who mostly write stories
    - Diagram the flow of a story (branches, story statuses, pipelines, QA environments...)
    - Write user stories that follow INVEST including good bug formats
    - Explain the differences in lifecycle between bugs / chores / features
    - Pair Program using a variety of techniques
  - TDD
    - Describe red-green-refactor and rules for TDD
