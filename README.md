# Nightwatch.js



[![npm](https://camo.githubusercontent.com/3b3f9a16e872d8bdba0f5ba9d59e6adcf5edbad70430ee1cd8cf80d329455991/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f6e6967687477617463682e737667)](https://www.npmjs.com/package/nightwatch) [![Node.js CI](https://github.com/nightwatchjs/nightwatch/actions/workflows/build-node.yaml/badge.svg?branch=main)](https://github.com/nightwatchjs/nightwatch/actions/workflows/build-node.yaml) [![codecov](https://camo.githubusercontent.com/2a892b6c4365404b211d0adb58dda8df1d865e74f0e78db658974b672a1b443b/68747470733a2f2f636f6465636f762e696f2f67682f6e6967687477617463686a732f6e6967687477617463682f6272616e63682f6d61696e2f67726170682f62616467652e7376673f746f6b656e3d4d534f62796645434568)](https://codecov.io/gh/nightwatchjs/nightwatch) [![Discord](https://camo.githubusercontent.com/9c63bc6b5ddfb8fc4e47187a055fe58473bb8ebdff1881c8c83765c29a9029a2/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f3631383339393633313033383231383234302e7376673f636f6c6f723d373338394438266c6162656c436f6c6f723d364137454332266c6f676f3d646973636f7264266c6f676f436f6c6f723d666666666666267374796c653d666c61742d737175617265266c6162656c3d646973636f7264)](https://discord.gg/SN8Da2X)

[![Nightwatch.js Logo](https://raw.githubusercontent.com/nightwatchjs/nightwatch/main/.github/assets/nightwatch-logo.png)](https://raw.githubusercontent.com/nightwatchjs/nightwatch/main/.github/assets/nightwatch-logo.png)

#### [Homepage](https://nightwatchjs.org/) • [Developer Guide](https://nightwatchjs.org/guide) • [API Reference](https://nightwatchjs.org/api) • [About](https://nightwatchjs.org/about) • [Blog](https://nightwatchjs.org/blog)



Nightwatch is an integrated testing framework powered by Node.js and using the [W3C Webdriver API](https://www.w3.org/TR/webdriver/). It is a complete testing solution developed at [BrowserStack](https://www.browserstack.com/) and which can be used for:

☑️ end-to-end testing of web applications and websites

☑️ component testing in isolation (React / Vue / Storybook / Angular)

☑️ Node.js unit, visual regression testing, accessibility testing & API testing

☑️ Native mobile app testing on Android & iOS

## 🚀 Nightwatch v3



[What's New](https://nightwatchjs.org/guide/overview/whats-new-in-v3.html) | [Release Notes](https://github.com/nightwatchjs/nightwatch/releases/tag/v3.0.1) | [Discussions](https://github.com/nightwatchjs/nightwatch/discussions)

Nightwatch v3 is an all new generation that has been built around these three pillars:

- **Developer Experience** : The entire experience from getting started, to writing and debugging tests, has been redesigned for speed, stability, and consistent non-flaky results.
- **Mobile first**: Test your web or native, iOS and Android, mobile applications on simulators, real mobile devices or a cloud grid like BrowserStack.
- **One test automation framework**: Run all types of tests from unit, component, and E2E to API, visual, and accessibility with a single framework.

The [Nightwatch v3](https://github.com/nightwatchjs/nightwatch/releases/tag/v3.0.1) is not just a new version, it’s the result of months of engineering effort to reimagine test automation for the future. Try it out in 60 seconds and see it in action.

## ⚙️ Get started in 60 seconds



#### 1. Install Nightwatch from NPM



From your existing project's root dir:

```
npm init nightwatch@latest
```



or, if you want to initialize a new project:

```
npm init nightwatch@latest ./path/to/new/project
```



[![nightwatch-cli-gif](https://user-images.githubusercontent.com/39924567/174841680-59664ff6-da2d-44a3-a1df-52d22c69b1e2.gif)](https://user-images.githubusercontent.com/39924567/174841680-59664ff6-da2d-44a3-a1df-52d22c69b1e2.gif)

#### 2. Answer a few questions about your preferred setup:



- What is your Language - Test Runner setup?
- Where do you want to run your e2e tests?
- Where you'll be testing on?
- Where do you plan to keep your end-to-end tests?
- What is the base_url of your project?

Nightwatch will do the entire setup for you based on your answers.

#### 3. Run a Demo Test:



Nightwatch comes with a few examples, which are automatically copied to your Nightwatch project during the setup and can also be used as boilerplate to write your own tests on top of them.

You can follow the instructions given at the end of the setup to run your first test with Nightwatch.

[![image](https://user-images.githubusercontent.com/39924567/174763723-aff4d501-6320-402c-81cc-de75fbb5e8f0.png)](https://user-images.githubusercontent.com/39924567/174763723-aff4d501-6320-402c-81cc-de75fbb5e8f0.png)

------

## Nightwatch mobile app testing



Nightwatch enables automation testing of native mobile applications via Appium. It combines the robustness of Appium with the enhanced developer experience provided by Nightwatch. It enables end-to-end functional testing of native mobile apps on Android and iOS devices. Try it now

## Go beyond E2E



### [Component testing](https://nightwatchjs.org/guide/component-testing/introduction.html)



With Nightwatch you can test components in isolation by mounting them in the browser. Nightwatch 2 added support for component testing for popular web frameworks such as

1. [React](https://nightwatchjs.org/guide/component-testing/testing-react-components.html)
2. [VueJS](https://nightwatchjs.org/guide/component-testing/vite-plugin.html)
3. [Angular](https://nightwatchjs.org/guide/component-testing/angular-component-testing.html)
4. [Storybook](https://nightwatchjs.org/guide/component-testing/storybook-component-testing.html)

### Nightwatch unit tests



The tests for Nightwatch are written using Mocha.

1. **Clone the project**

   ```
   git clone https://github.com/nightwatchjs/nightwatch.git
   
   # change directory
   cd nightwatch
   
   # install the dependencies
   npm install
   ```

   

2. **Run tests**

   To run the complete test suite:

   ```
   npm test
   ```

   

   To check test coverage, run the command:

   ```
   npm run mocha-coverage
   ```

   

   and then open the generated coverage/index.html file in your browser.

See [Unit testing guide](https://nightwatchjs.org/guide/writing-tests/write-nodejs-unit-integration-tests.html) for more details.

### Other types of testing



#### [Visual Regression Testing](https://nightwatchjs.org/guide/writing-tests/visual-regression-testing.html)



Nightwatch v3 introduces visual regression testing as an in-house plugin. The plugin takes care of

1. Capturing screenshots
2. Comparison with baseline to highlight visual differences
3. Report to review the differences
4. Approve the changes

VRT can be done on real desktop & mobile browsers. Also, VRT can be run on components as part of component testing as well.

#### [API Testing](https://nightwatchjs.org/guide/writing-tests/api-testing.html)



API testing is now available with Nightwatch v3. The following functionality can be achieved with API testing

1. Request assertions
2. Response assertions
3. Viewing API tests in the HTML report
4. Mock server
5. This project is tested with BrowserStack

#### [Accessibility Testing](https://nightwatchjs.org/guide/using-nightwatch/accessibility-testing.html)



Nightwatch v3 packages the aXe-core package developed by Deque Systems as a plugin. It enables 90 different types of accessibility tests for WCAG compliance.

## 🦉 About Nightwatch



Nightwatch was initially built by [@pineviewlabs](https://github.com/pineviewlabs/) - an independent software consultancy based in Oslo, Norway, with help from [contributors](https://github.com/nightwatchjs/nightwatch/graphs/contributors). In mid 2021, Nightwatch has become a part of the [@BrowserStack](https://github.com/browserstack) family and it is being developed further at the BrowserStack Open-source Program Office. Read more on [our blog](https://nightwatchjs.org/blog/nightwatch-has-joined-the-browserstack-family.html).

## Contributing



We welcome any and all contributions from the community which can help improve Nightwatch. Please check out [CONTRIBUTING.md](https://github.com/nightwatchjs/nightwatch/blob/main/CONTRIBUTING.md) for more extensive contributing guidelines.
This project is tested with BrowserStack
## Licence



[MIT](https://github.com/nightwatchjs/nightwatch/blob/main/LICENSE.md)
