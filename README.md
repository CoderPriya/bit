 <a href="https://opensource.org/licenses/Apache-2.0"><img alt="apache" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"></a>
 <a href="https://github.com/teambit/bit/blob/master/CONTRIBUTING.md"><img alt="prs" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
 [![Gitter chat](https://badgen.now.sh/badge/chat/on%20gitter/cyan)](https://gitter.im/bit-src/Bit)
 [![Discourse status](https://img.shields.io/discourse/https/meta.discourse.org/status.svg)](https://discourse.bit.dev/)
 <a href="https://ci.appveyor.com/project/TeamBit/bit-wikt3/branch/master"><img alt="Appveyor Status" src="https://ci.appveyor.com/api/projects/status/vg7wvfvku12kkxkc?svg=true"></a>
 <a href="https://circleci.com/gh/teambit/bit/tree/master"><img alt="Circle Status" src="https://circleci.com/gh/teambit/bit/tree/master.svg?style=shield&circle-token=d9fc5b19b90fb7e0655d941a5d7f21b61174c4e7">
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Share%20code%20components%20as%20a%20team%20@bitdev_&url=https://bit.dev&hashtags=opensource,javascript,programming,reactjs,webdev,vuejs,angularjs)

# Bit is the shortest way to reuse atomic components between projects

![Bit Workflow](https://storage.googleapis.com/static.bit.dev/docs/images/quick_start.png)

[Documentation](https://docs.bit.dev) • [Tutorials](https://docs.bit.dev/docs/tutorials/bit-react-tutorial) • [Quick start guide ](https://docs.bit.dev/quick-start) • [Workflows](https://docs.bit.dev/docs/workflows/workflows) • [bit.dev components cloud](https://bit.dev) • [Video demo](https://www.youtube.com/watch?v=E5lgoz6-nfs) • [Gitter](https://gitter.im/bit-src/Bit) • [Twitter](https://twitter.com/bitdev_)

## What is Bit? 🤔

Bit is an [open-source](https://github.com/teambit/bit) cli tool for sharing components across projects and repositories. 
Use Bit to turn a component inside an application into a standalone reusable package.  
Increase the project's resilience by consuming only the components the application needs.
You can set up your own server for sharing components or you can use the [bit.dev](https://bit.dev) cloud hosting for private and public components sharing with advanced features such as components CI and components showcase.

## Why Bit? 🎖️

Bit simplifies the process of collaborating on UI components. Team members can share, maintain, and synchronize components from different projects.
This allows teams to:

- Increase code reusability
- Increase design and development efficiency
- Increase project's resilience to changes
- Retain UI and UX consistency
- A stepping stone for establishing a [micro frontends architecture](https://martinfowler.com/articles/micro-frontends.html)

## Key Features 🔑

- Extract a component for sharing directly from an existing project.
- Validate the component's independence by building and testing each component separately from the rest of the application.
- Change the source code of shared components from any project that utilizes it.
- Get published changes in components on top of local modifications.
- Contribute back changes made to components directly from your project.
- Let Bit auto-generate npm package for each component.
- Distribute small atomic components instead of a bloated package.
- Automate component versioning according to changes in its dependencies.
- Use with leading frameworks and tools: React, Vue, Angular, Mocha, Jest.  
- Works alongside Git, NPM, and Yarn.

Bit is working with Javascript and Javascript frameworks: 

<img src="https://storage.googleapis.com/static.bit.dev/docs/images/js_logos.png">

## Installation 🚪

Using npm: 

```bash
npm install bit-bin --global
```

Using yarn: 
```bash
yarn global add bit-bin  
```

Bit cli requires node 8.12 and above. Check other [installation](https://docs.bit.dev/docs/installation) methods.

## bit.dev cloud 🌩️

Use [bit.dev](https://bit.dev) cloud hosting solution as a shared server and playground for your components.
<p align="center">
 <a href="https://bit.dev"><img src="https://storage.googleapis.com/bit-docs/component-discovery-bit-react-gif.gif"></a>
</p>

## Contributing 🎗️

Contributions are always welcome, no matter how large or small. Before contributing, please read the [code of conduct](CODE_OF_CONDUCT.md).

See [Contributing](CONTRIBUTING.md).

## License 💮

Apache License, Version 2.0
