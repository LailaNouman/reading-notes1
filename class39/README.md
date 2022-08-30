# Class-39:

### NextJs
To build a complete web application with React from scratch, there are many important details you need to consider:

- Code has to be bundled using a bundler like webpack and transformed using a compiler like Babel.
- You need to do production optimizations such as code splitting.
- You might want to statically pre-render some pages for performance and SEO. You might also want to use server-side rendering or client-side rendering.
- You might have to write some server-side code to connect your React app to your data store.

Next.js, the React Framework. Next.js provides a solution to all of the above problems. But more importantly, it puts you and your team in the pit of success when building React applications.

Next.js aims to have best-in-class developer experience and many built-in features, such as:

- An intuitive page-based routing system (with support for dynamic routes).
- Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis.
- Automatic code splitting for faster page loads.
- Client-side routing with optimized prefetching.
- Built-in CSS and Sass support, and support for any CSS-in-JS library.
- Development environment with Fast Refresh support.
- API routes to build API endpoints with Serverless Functions.
- Fully extendable.
 
### React Context
React context allows us to pass down and use (consume) data in whatever component we need in our React app without using props.

React context is great when you are passing data that can be used in any component in your application.

You can think of React context as the equivalent of global variables for our React components.

Props drilling is a term to describe when you pass props down multiple levels to a nested component, through components that don't need it. React context helps us avoid the problem of props drilling.

