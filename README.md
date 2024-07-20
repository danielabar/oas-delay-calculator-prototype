<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [OAS Delay Calculator Prototype](#oas-delay-calculator-prototype)
  - [Overview](#overview)
  - [Features](#features)
  - [TODO Screenshots](#todo-screenshots)
  - [Current Status](#current-status)
    - [Functional Improvements](#functional-improvements)
    - [Technical Enhancements](#technical-enhancements)
    - [Future Considerations](#future-considerations)
  - [Conclusion](#conclusion)
  - [Contribution](#contribution)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# OAS Delay Calculator Prototype

## Overview

The OAS Delay Calculator is a prototype tool designed to help Canadian seniors decide whether to delay their Old Age Security (OAS) benefits. This tool calculates the breakeven age by comparing the financial benefits of taking OAS at age 65 versus delaying it up to age 70. The breakeven age is the point at which the total amount of OAS received from delaying equals the total amount received if starting at age 65.

For many people, this breakeven age is close to the average Canadian life expectancy, making it less beneficial to delay OAS. For low-income seniors eligible for the Guaranteed Income Supplement (GIS), the breakeven age can be significantly higher, sometimes reaching 90 or even 100 years. In such cases, delaying OAS can result in a financial loss.

The goal is to improve the uptake of OAS among seniors, particularly those in a low-income bracket who could also be eligible for GIS. This prototype aims to provide a clear and user-friendly interface that helps seniors understand the potential financial benefits and drawbacks of delaying their OAS payments, simplifying the decision-making process with clear visualizations and explanations.

**Note:** This is a prototype and not a finalized product. It is intended to demonstrate the concept and provide initial functionality.

## Features

- Input forms for personal details such as income range and age.
- Calculation of the potential increase in OAS benefits when delaying.
- Visualization of the impact on GIS.
- Basic styling and structure for user interaction.

## TODO Screenshots

## Current Status

The current version is a working prototype with the core functionality in place. Users can input their information and see basic calculations and visualizations. However, several features and improvements are planned to make this a comprehensive and reliable tool. To evolve this prototype into a fully functional and reliable product, the following should be considered:

### Functional Improvements

- **Messaging:** Clearly communicate that benefits don't stack with respect to waiting and having fewer than 40 years in Canada. Explain that users do not get 40/40ths by waiting.
- **Feature:** Implement a toggle for showing statistics related to life expectancy. Consider whether to ask for gender (men vs. women) or combine data for a slightly less accurate but simpler approach.
- **Messaging:** Add an "apply now" link to the government of Canada website for OAS, making it easier for users to apply. Include a `?ref=...` parameter in the URL to track applications originating from this tool.
- **Feature:** Enhance styling to emphasize the importance of the initial years of missed payments.
- **Feature:** Provide a detailed explanation of how the initial years of missed payments are calculated, including the multiplication process.
- **Messaging Disclaimer:**
  - Highlight that this tool is only one piece of information and that no one can predict their exact lifespan, which adds uncertainty.
  - Emphasize the uncertainty in predicting future earnings and work years, which can affect GIS calculations.
  - Include a disclaimer that this tool should not be considered financial advice and users should consult with a licensed or qualified practitioner.

### Technical Enhancements

- **Code Refinement:** Refactor and optimize the existing codebase for better performance and maintainability. This may include selection of a JavaScript SPA such as Svelte, together with Vite.
- **Accessibility:** Ensure the tool is accessible to all users, including those with disabilities. Chart.js in particular needs some extra work: https://www.chartjs.org/docs/latest/general/accessibility.html
- **Testing:** Implement comprehensive unit and integration tests to ensure accuracy and reliability.
- **Security:** Ensure all user data is handled securely and in compliance with relevant data protection regulations.
- **Documentation:** Provide detailed documentation for both users and developers, including setup instructions, usage guides, and contribution guidelines.

### Future Considerations

- **Localization:** Support multiple languages to cater to a broader audience.
- **Mobile Optimization:** Ensure the tool is fully functional and user-friendly on mobile devices.
- **Analytics:** Implement analytics to track user interactions and gather feedback for further improvements.

## Conclusion

The OAS Delay Calculator Prototype is an initial step towards creating a helpful tool for Canadian seniors. While the prototype demonstrates the core idea and functionality, there are several enhancements and features needed to make it a fully-fledged product. By addressing the initiatives listed above, we aim to build a reliable, user-friendly, and valuable tool for those considering their OAS options.

## Contribution

Contributions are welcome! If you have any suggestions or would like to help with development, please feel free to open an issue or submit a pull request.
