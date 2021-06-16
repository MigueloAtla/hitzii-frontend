# STYLING

[styled-components](https://styled-components.com/)

- A convenient way to separate logical and representational components.
- Make easier to compose a system design.
- More reusable components.
- Use of props and conditional styles, makes css more powerful.
- Scoped styles, like in css modules, Why is this good? -> [CSS-Modules: Why This Is the Most Significant Improvement to CSS in Years (x-team.com)](https://x-team.com/blog/css-modules-a-new-way-to-css/)

# DESIGN SYSTEM

Understanding the problem

- What is Atomic design? -> [Atomic Design Methodology | Atomic Design by Brad Frost](https://atomicdesign.bradfrost.com/chapter-2/)
- [Everything I Know About Style Guides, Design Systems, and Component Libraries – Lee Robinson](https://leerob.io/blog/style-guides-component-libraries-design-systems)
- [Component Driven User Interfaces](https://www.componentdriven.org/)

## Tools for build design systems

- Styled System [Styled System (styled-system.com)](https://styled-system.com/)
- Storybook [Storybook: UI component explorer for frontend developers](https://storybook.js.org/)

## Tools for visual testing a design system across teams

- Chromatic [Chromatic: Storybook deployment, review, and test](https://www.chromatic.com/)
- Reading -> [Introducing Chromatic — UI testing for React | by Dominic Nguyen | Medium](https://medium.com/@domyen/introducing-chromatic-ui-testing-for-react-c5cc01a79aaa)

# LAYOUT

Atomic layout -> [kettanaito/atomic-layout: Physical representation of layout composition to create declarative responsive layouts in React. (github.com)](https://github.com/kettanaito/atomic-layout)

- Why? -> [Creating layouts that last — Artem Zakharchenko - YouTube](https://www.youtube.com/watch?v=_HrXUB97xQs) 
- Resolve the problems while composing elements in a layout.
- Separates the concept of Layouts and other styling parts of the app.
- Declarative Layout, easy to maintain and understand.
- Responsive made clearer.

# STORYBOOK

[Storybook: UI component explorer for frontend developers](https://storybook.js.org/)

- Encourages you to make UI component by component, thinking first in the smaller pieces of your app, and use them to compose pages.
- Define the different states of a component, predictable behavior of the component.
- Make a page that contains the library, making easier to search a component.
- Shareable UI platform (independent deploy), making easy show to the team and get feedback.
- Automatic Docs, customizable doc page, using MD. Separate Docs page deployable.
- Easier and resilient testing, (unit, e2e, snapshot...) you test the stories, where you already have mock data, and different states are written, no necessity of write different states in test.
- Use of tools like Chromatic, to automate snapshot testing, giving feedback to the design team.

Examples:

- Gitlab [base / accordion - default ⋅ Storybook (gitlab-org.gitlab.io)](https://gitlab-org.gitlab.io/gitlab-ui/?path=/story/base-accordion--default)
- Airbnb dates [Storybook (airbnb.io)](https://airbnb.io/react-dates/?path=/story/daterangepicker-drp--default)
- React 95 [Storybook (react95.io)](https://storybook.react95.io/?path=/story/window--default)

## WRITING UI DOCUMENTATION

Storybook + MDX -> [MDX (storybook.js.org)](https://storybook.js.org/docs/react/writing-docs/mdx)

## TESTING WITH STORYBOOK

- [Using Storybook stories with Testing Library - YouTube](https://www.youtube.com/watch?v=k6NG96awIJ0)
- [Unit testing with Storybook](https://storybook.js.org/docs/react/workflows/unit-testing)
- [Interaction testing with Storybook](https://storybook.js.org/docs/react/workflows/interaction-testing)

# UI UTILITY LIBS

## TABLES

React table [React Table - Hooks for building lightweight, fast and extendable datagrids for React (tanstack.com)](https://react-table.tanstack.com/)

Examples -> [react-table examples - CodeSandbox](https://codesandbox.io/examples/package/react-table)



## DRAG AND DROP

[react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd)

Demo -> [Storybook (react-beautiful-dnd.netlify.app)](https://react-beautiful-dnd.netlify.app/iframe.html?id=board--simple)

# TESTING

## React Testing Library 

[React Testing Library | Testing Library (testing-library.com)](https://testing-library.com/docs/react-testing-library/intro/)