# Complete React & Full-Stack Development Handbook  
**Detailed Table of Contents with Subfolder Projects**

Each subfolder listed below is a **React Vite project** (except where noted) that covers the specific concepts of that module. The projects are designed to be hands-on and incremental, building a strong foundation from prerequisites to full-stack development.

---

## Module 00: Prerequisites · HTML · CSS · JavaScript · Projects  
*(These projects use React Vite as a playground to practice foundational web technologies within a component environment.)*

| Subfolder | Description |
|-----------|-------------|
| `00-01-html-basics` | Semantic HTML, forms, tables, multimedia, accessibility attributes. |
| `00-02-css-fundamentals` | Selectors, box model, units, positioning, display, z-index. |
| `00-03-css-flexbox-grid` | Flexbox and CSS Grid layouts with practical examples. |
| `00-04-css-responsive-design` | Media queries, mobile-first design, fluid typography, viewport units. |
| `00-05-css-animations-transitions` | CSS transitions, keyframe animations, transforms. |
| `00-06-js-fundamentals` | Variables, data types, operators, control flow, loops. |
| `00-07-js-functions-scope` | Function declarations, expressions, arrow functions, scope, closures. |
| `00-08-js-arrays-objects` | Array methods, object manipulation, destructuring, spread/rest. |
| `00-09-js-dom-manipulation` | DOM API, selecting elements, events, creating/removing nodes (using `useRef`/`useEffect` for demonstration). |
| `00-10-js-async` | Callbacks, promises, async/await, fetch, error handling. |
| `00-11-js-modules` | ES modules, import/export, default and named exports. |
| `00-12-prereq-projects` | Small integrated projects: todo list, calculator, quiz app (built with vanilla JS concepts inside React). |

---

**Updated Module 01: React Setup**  

| Subfolder | Description |
|-----------|-------------|
| `001-older-way-by-nodejs-team-create-react-project_By_hand_manual` | **Manual React Setup (Older Way)** – Create a React project from scratch: install React, ReactDOM, Babel, Webpack manually; configure `webpack.config.js`, `.babelrc`; understand the underlying tooling. |
| `002-official-way-by-react-js-team-using-npm-npx` | **Create React App (Official Way)** – Use `npx create-react-app` to bootstrap a project; explore CRA structure, scripts, and default configuration. |
| `003-latest-way-by-vite-team-using-npm-vite` | **Vite Setup (Latest Way)** – Use `npm create vite@latest` to set up a React project with Vite; understand the speed benefits and modern configuration. |
| `01-01-vite-setup` | Creating a Vite project, folder structure, `main.jsx`, `App.jsx`, dev server. |
| `01-02-jsx-basics` | JSX syntax, embedding expressions, attributes, self-closing tags, comments. |
| `01-03-components-intro` | Functional components, importing/exporting components, rendering. |
| `01-04-reactdom-render` | `ReactDOM.createRoot`, `render`, `StrictMode`, mounting. |
| `01-05-project-structure` | Organizing files, components folder, assets, public folder. |

---

This now includes the three historical/setup approaches at the top, ensuring learners understand the evolution and different ways to start a React project.

---

**Updated Module 02: React Fundamentals**  

| Subfolder | Description |
|-----------|-------------|
| `02-00-jsx` | Deep dive into JSX rendering, JS expressions, conditional rendering, attributes, arrays, `.map()`, lists. |
| `02-01-components-rendering` | Rendering React components, component tree, root component, importing/exporting components. |
| `02-02-props-parent-to-child-component` | Passing data to components via props, destructuring props, prop types basics. |
| `02-03-use-state-hook` | Introduction to `useState` hook, initializing and updating local state. |
| `02-04-event-handling-basics` | Basic React event handling with `onClick`, `onChange`, `onSubmit`, event handler functions, and events with state. |
| `02-05-value-child-cmpnt-fun-var-pass-as-props` | Passing values, child components, functions, and variables as props; callback props. |
| `02-06-conditional-rendering` | Conditional rendering with `if`/`else`, ternary operators, logical `&&`, returning `null`. |
| `02-07-functional-components` | Deep dive into functional components, default props, props.children. |
| `02-08-state-basics` | `useState` in depth: batching behavior, functional updates, object/array state. |
| `02-09-rendering-lists` | Rendering arrays with `.map()`, importance of keys, filtering/sorting lists. |
| `02-10-fragments` | `React.Fragment`, shorthand `<>`, avoiding extra DOM nodes. |
| `02-11-composition` | `props.children`, composition vs inheritance, slots pattern. |
| `02-12-props-validation` | PropTypes, defaultProps, type checking for props. |

---

This structure now includes basic event handling before advanced prop-passing concepts, providing a granular progression from JSX fundamentals through components, props, state, events, conditional rendering, lists, composition, and props validation.


---

**Updated Module 03: Events & DOM**  
*(Expanded with additional subfolders for deeper coverage)*

| Subfolder | Description |
|-----------|-------------|
| `03-01-event-handling` | Synthetic events, `onClick`, `onChange`, event object basics. |
| `03-02-event-binding` | Arrow functions in render, binding in class components (brief). |
| `03-03-passing-arguments` | Passing parameters to event handlers. |
| `03-04-form-events-handling` | `onSubmit`, `onChange`, controlled vs uncontrolled inputs. |
| `03-05-keyboard-mouse-events` | `onKeyDown`, `onKeyUp`, `onMouseEnter`, `onMouseLeave`. |
| `03-06-refs-basics` | `useRef` for DOM access, reading values, focusing elements. |
| `03-07-uncontrolled-components` | Using refs to read form values on submit. |
| `03-08-event-propagation` | Event bubbling, capturing, `stopPropagation`, `preventDefault`, event delegation. |
| `03-09-event-object-deep-dive` | SyntheticEvent properties, `target` vs `currentTarget`, event pooling (legacy), `persist()`. |
| `03-10-keyboard-event-handler` | Advanced keyboard events: key combinations, `key` vs `keyCode`, global keyboard shortcuts. |
| `03-11-dom-manipulation-useref` | Advanced `useRef` for DOM manipulation: measuring elements, managing focus, timers, imperative APIs. |

---

This expansion provides a more granular progression from basic event handling to advanced topics like propagation, event object internals, and extensive DOM manipulation with refs.

---

**Updated Module 04: Components & Lifecycle**  
*(Original topics plus added subfolders for class-based CRUD, functional lifecycle, and performance optimizations mimicking shouldComponentUpdate)*

| Subfolder | Description |
|-----------|-------------|
| `04-01-class-components` | Class syntax, `this.state`, `this.setState`, rendering. |
| `04-02-lifecycle-methods` | `componentDidMount`, `componentDidUpdate`, `componentWillUnmount`. |
| `04-03-useeffect-lifecycle` | Mimicking lifecycle with `useEffect` (mount, update, unmount). |
| `04-04-cleanup-effects` | Cleanup functions, subscriptions, timers. |
| `04-05-error-boundaries` | Class-based error boundary component, catching errors. |
| `04-06-higher-order-components` | HOC pattern, enhancing components. |
| `04-07-render-props` | Render prop pattern, sharing logic. |
| `04-08-class-components-crud-app` | **Class Component CRUD App** – Build a complete Task Manager app using class components, state, lifecycle methods, and forms. |
| `04-09-functional-components-lifecycle` | **Functional Lifecycle Deep Dive** – Explore mount and update phases in functional components using `useEffect` and `useLayoutEffect` with various dependency arrays. |
| `04-10-useeffect-did-mount-update` | **useEffect as componentDidMount & componentDidUpdate** – Simulate class lifecycle methods with `useEffect` dependency arrays, including infinite loop pitfalls. |
| `04-11-component-should-update-usememo` | **useMemo for shouldComponentUpdate** – Use `useMemo` to memoize computed values and prevent unnecessary recalculations, optimizing render performance. |
| `04-12-component-should-update-usecallback` | **useCallback for shouldComponentUpdate** – Use `useCallback` to stabilize function references and prevent unnecessary child re-renders, akin to shouldComponentUpdate. |

---

This expanded module covers both class and functional component lifecycles, plus practical patterns for optimizing component updates with memoization hooks.

---

**Updated Module 05: Hooks (Real-World Focused)**  
*(Filtered to include only hooks that are commonly used in production React applications)*

| Subfolder | Description |
|-----------|-------------|
| `05-01-usestate-deep-dive` | The core state hook — lazy init, functional updates, object/array state. |
| `05-02-useeffect-deep-dive` | Side effects, data fetching, subscriptions, cleanup, dependency arrays. |
| `05-03-usecontext` | Consume context values; avoid prop drilling in real apps. |
| `05-04-usereducer` | Manage complex state transitions with actions (e.g., forms, carts). |
| `05-05-usememo-usecallback` | Prevent expensive recalculations and stabilize function references. |
| `05-06-useref-deep-dive` | Access DOM nodes, keep mutable values, store previous values. |
| `05-07-uselayouteffect` | Run effects synchronously after DOM mutations; measure layout, avoid flicker. |
| `05-08-useimperativehandle` | Expose imperative methods from child components (e.g., focus, scroll). |
| `05-09-useid` | Generate stable unique IDs for form inputs and accessibility attributes. |
| `05-10-usetransition` | Mark non-urgent updates to keep UI responsive during heavy rendering. |
| `05-11-usedeferredvalue` | Defer rendering of a value (e.g., search results) to keep inputs fast. |
| `05-12-usesyncexternalstore` | Subscribe to external stores (Redux, Zustand, browser APIs) safely. |
| `05-13-rules-of-hooks` | Understand and enforce hook rules to avoid bugs. |
| `05-14-custom-hooks-intro` | Build reusable hooks; share logic across components. |
| `05-15-use-previous` | Track the previous value of state or props (useful in effects). |
| `05-16-use-local-storage` | Persist state to `localStorage` and sync across tabs. |
| `05-17-use-debounce-throttle` | Limit how often a function runs (search inputs, scroll handlers). |
| `05-18-use-on-click-outside` | Detect clicks outside an element — close modals, dropdowns, popovers. |
| `05-19-use-event-listener` | Attach and clean up event listeners declaratively. |
| `05-20-use-media-query` | Respond to CSS media queries in JavaScript for responsive layouts. |
| `05-21-use-window-size` | Track viewport width/height for responsive components. |
| `05-22-use-fetch` | Simple data fetching with loading, error, and cancellation. |
| `05-23-use-form` | Manage form state, validation, and submission easily. |
| `05-24-use-toggle` | Simple boolean state toggling (show/hide, open/close). |
| `05-25-use-interval-timeout` | Declarative timers that clean up automatically. |
| `05-26-use-hover` | Track hover state of an element (tooltips, effects). |
| `05-27-use-document-title` | Update the browser tab title dynamically. |

---

**Removed hooks (rarely used in production):**  
- `useDebugValue` — only for custom hook library authors during development.  
- `useInsertionEffect` — extremely niche; intended only for CSS-in-JS library internals.  
- `useHistory` (custom undo/redo) — too specific; not generally needed in typical apps.

This list focuses on hooks you will actually encounter and use in day-to-day React development, ensuring every topic is practical and immediately applicable.

---

**Updated Module 06: Advanced State**  
*(Renamed folder slugs and descriptions to be more meaningful, simple, and reflect real-world usage)*

| Subfolder | Description |
|-----------|-------------|
| `06-01-shared-state-lifting-up` | **Lifting State Up** – Share state between sibling components by moving it to their common parent (real use: synced inputs, cart count). |
| `06-02-global-state-context-reducer` | **Context + useReducer for Global State** – Combine Context API and reducer to manage app-wide state (real use: theme, user, cart). |
| `06-03-normalizing-state-data` | **State Normalization** – Store data in flat structures keyed by ID to avoid duplication and simplify updates (real use: lists of entities like posts, users). |
| `06-04-immutable-update-patterns` | **Immutable Updates for Objects & Arrays** – Safely update nested state using spread, map, filter without mutating (real use: adding/removing items in arrays). |
| `06-05-immer-simplify-immutability` | **Immer for Simpler Immutable Updates** – Use the Immer library to write mutating-like syntax while producing immutable updates (real use: complex nested state). |
| `06-06-url-state-search-params` | **URL Search Params as State** – Use `useSearchParams` to read/write query parameters; share state via URL (real use: filters, pagination, shareable links). |
| `06-07-server-state-react-query` | **Server State with React Query** – Fetch, cache, and synchronize server data; handle loading/error/mutations (real use: API data that changes on server). |
| `06-08-state-machines-xstate` | **Finite State Machines with XState** – Model complex UI states with explicit transitions (real use: multi-step forms, onboarding, complex UI flows). |

Now every folder name clearly states its purpose, making it easier to understand what real-world problem it solves.

---

## Module 07: Forms

| Subfolder | Description |
|-----------|-------------|
| `07-01-controlled-forms` | Controlled inputs, text, select, checkbox, radio. |
| `07-02-uncontrolled-forms` | Uncontrolled inputs, `defaultValue`, refs. |
| `07-03-form-validation` | Manual validation, error messages, validation on submit. ,joi |
| `07-04-react-hook-form` | Using React Hook Form library. |
| `07-05-formik` | Using Formik library. |
| `07-06-custom-form-hooks` | Building a custom `useForm` hook. |
| `07-07-dynamic-forms` | Adding/removing fields dynamically. |
| `07-08-file-upload` | File input, preview, uploading with FormData. |
| `07-09-multi-step-forms` | Wizard pattern, step navigation, state per step. |

---

## Module 08: API Integration

| Subfolder | Description |
|-----------|-------------|
| `08-01-fetch-api` | Fetching data with `fetch` in `useEffect`, loading/error. |
| `08-02-axios` | Axios setup, interceptors, base URL. |
| `08-03-loading-error-states` | Handling loading, error, success UI states. |
| `08-04-abort-controller` | Cancelling requests, cleanup. |
| `08-05-react-query` | React Query for data fetching, caching, mutations. |
| `08-06-swr` | SWR library for data fetching. |
| `08-07-graphql-intro` | Apollo Client, queries, mutations. |
| `08-08-websockets` | Real-time data with WebSockets (e.g., Socket.IO client). |

---

**Updated Module 09: React Router**  
*(Expanded with additional focused subfolders covering all key routing concepts)*

| Subfolder | Description |
|-----------|-------------|
| `09-01-basic-routing` | `BrowserRouter`, `Routes`, `Route`, `Link`. |
| `09-02-nested-routes` | Nested routes, `Outlet`, layout routes. |
| `09-03-route-params` | `useParams`, dynamic route segments. |
| `09-04-navigation` | `useNavigate`, `useLocation`, `NavLink` active styles. |
| `09-05-query-params` | `useSearchParams`, reading/writing query strings. |
| `09-06-protected-routes` | Route guards, redirect if not authenticated. |
| `09-07-lazy-loading-routes` | Code splitting with `React.lazy`, `Suspense`. |
| `09-08-404-handling` | Catch-all route, custom 404 page. |
| `09-09-route-transitions` | Animating route changes with Framer Motion. |
| `09-10-react-router-dom-anchor-vs-create-browser-router` | Compare `<a>` tags vs `createBrowserRouter` and `RouterProvider`; understand full router setup. |
| `09-11-react-router-link` | Deep dive into `Link` component: internal navigation, state passing, replacement behavior. |
| `09-12-react-router-navlink` | `NavLink` for active styles, `className` function, `end` prop for exact matching. |
| `09-13-react-router-useparam-route-parameter` | Using `useParams` to read dynamic route parameters; multiple params, nested params. |
| `09-14-react-router-uselocation-query-parameter` | Using `useLocation` to read query strings; parsing with `URLSearchParams`. |
| `09-15-react-router-usenavigate` | Programmatic navigation with `useNavigate`; redirects, history stack, `replace`. |
| `09-16-react-nested-router-outlet-to-child-route-renders-in-parent` | Nested routes with `Outlet`; rendering child routes inside parent layout; index routes. |
| `09-17-react-router-not-found-route` | Dedicated 404 route with `path="*"`; custom not-found component; nested 404s. |
| `09-18-form-handling-with-route` | Submitting forms and navigating based on results; combining form actions with routing. |
| `09-19-react-router-browser-router` | Deep dive into `BrowserRouter` configuration, basename, history, and server requirements. |

This comprehensive module now covers every fundamental and advanced React Router concept with dedicated hands-on projects, ensuring no topic is missed.

---

**Updated Module 10: Authentication & Authorization (Simplified)**  
*(Rewritten with simple, clear folder names and descriptions for real-world use)*

| Subfolder | Description |
|-----------|-------------|
| `10-01-login-jwt` | User logs in, gets a token, and we send it with every request. |
| `10-02-route-guards` | Protect pages so only logged-in users can see them. |
| `10-03-role-based-access` | Show or hide UI based on user role (admin, editor, regular user). |
| `10-04-token-refresh` | Keep user logged in by silently refreshing the token when it expires. |
| `10-05-social-login` | Sign in with Google / GitHub accounts. |
| `10-06-password-reset` | Send reset link via email, let user set a new password. |
| `10-07-user-session-context` | Store the logged-in user data in a global context so any component can access it. |

This version uses plain language and focuses on what each part does in a typical app.

---

**Updated Module 11: State Management**  
*(Redux Basics and Redux Toolkit broken down into focused, real-world subfolders)*

| Subfolder | Description |
|-----------|-------------|
| `11-01-redux-store-create` | Create a Redux store — the single source of truth for your app state. |
| `11-02-redux-actions` | Define action types and action creators — what happened in your app. |
| `11-03-redux-reducers` | Write reducers to update state immutably when actions are dispatched. |
| `11-04-redux-dispatch` | Dispatch actions from UI events; see how state changes flow through the store. |
| `11-05-redux-connect` | Use `connect` in class components to map state and dispatch to props. |
| `11-06-redux-toolkit-setup` | Configure the store with `configureStore` — modern Redux setup with sensible defaults. |
| `11-07-redux-toolkit-slice` | Use `createSlice` to define reducers and actions in one place — less boilerplate. |
| `11-08-redux-toolkit-hooks` | Use `useSelector` and `useDispatch` in functional components to read and update state. |
| `11-09-redux-toolkit-async-thunks` | Handle API calls and async logic with `createAsyncThunk`. |
| `11-10-rtk-query` | Data fetching and caching built into Redux Toolkit — automatic loading/error states. |
| `11-11-zustand` | Tiny, fast state library — simple store, no boilerplate. Great for small/medium apps. |
| `11-12-jotai` | Atomic state — independent pieces of state that compose easily. Good for React-first granular state. |
| `11-13-recoil` | Facebook's state library using atoms and selectors — less common now, but similar to Jotai. |
| `11-14-mobx` | Observable-based state — automatic tracking of what changed. Use if you like reactive, non-functional style. |
| `11-15-context-vs-redux` | When to use built-in Context vs a full state library — compare performance, complexity, and real-world scenarios. |

Now Redux is broken into individual concepts, making it easier to learn step by step and build real projects.

---

## Module 12: Performance Optimization

| Subfolder | Description |
|-----------|-------------|
| `12-01-react-memo` | `React.memo` for preventing re-renders. |
| `12-02-usememo-usecallback-optimization` | Optimizing with `useMemo`, `useCallback`. |
| `12-03-code-splitting-lazy` | Code splitting, `React.lazy`, `Suspense`. |
| `12-04-virtual-lists` | Virtualized lists with `react-window` or `react-virtualized`. |
| `12-05-debounce-throttle` | Custom hooks for debounce/throttle. |
| `12-06-bundle-analysis` | Analyzing bundle size, `source-map-explorer`, `vite-bundle-visualizer`. |
| `12-07-profiling` | React DevTools Profiler, identifying bottlenecks. |
| `12-08-tree-shaking` | ES modules, sideEffects, tree shaking best practices. |

---

## Module 13: Advanced React

| Subfolder | Description |
|-----------|-------------|
| `13-01-portals` | `createPortal` for modals, tooltips, dropdowns. |
| `13-02-forwardref` | Passing refs to child components. |
| `13-03-compound-components` | Tabs, accordion, select components using compound pattern. |
| `13-04-controlled-uncontrolled-patterns` | Flexible components supporting both modes. |
| `13-05-state-reducer-pattern` | `useReducer` for component state logic. |
| `13-06-render-props-advanced` | Advanced render prop usage. |
| `13-07-hoc-advanced` | Advanced HOC patterns, composition. |
| `13-08-context-advanced` | Dynamic context, multiple providers, context selectors. |

---

## Module 14: React Testing

| Subfolder | Description |
|-----------|-------------|
| `14-01-jest-setup` | Configuring Jest with Vite, `vitest` alternative. |
| `14-02-react-testing-library` | `render`, `screen`, queries. |
| `14-03-testing-components` | User events, assertions, testing UI. |
| `14-04-testing-hooks` | `renderHook`, testing custom hooks. |
| `14-05-mocking` | Mocking modules, API calls, `jest.mock`. |
| `14-06-testing-async` | `waitFor`, `findBy`, async testing. |
| `14-07-snapshot-testing` | Snapshot tests, updating snapshots. |
| `14-08-e2e-testing` | End-to-end with Cypress or Playwright (separate setup). |

---

## Module 15: React + TypeScript

| Subfolder | Description |
|-----------|-------------|
| `15-01-ts-setup-vite` | Vite with TypeScript template, config. |
| `15-02-typing-props` | Interfaces for props, `FC`, children. |
| `15-03-typing-state` | `useState` with types, union types. |
| `15-04-typing-events` | Typing event handlers (`ChangeEvent`, `FormEvent`). |
| `15-05-typing-refs` | `useRef` types, `RefObject`. |
| `15-06-typing-context` | Context with TypeScript, provider types. |
| `15-07-typing-hooks` | Typing custom hooks. |
| `15-08-advanced-types` | Generics, utility types, type vs interface. |

---

## Module 16: Modern React

| Subfolder | Description |
|-----------|-------------|
| `16-01-react18-features` | `createRoot`, automatic batching, `flushSync`. |
| `16-02-suspense` | `React.Suspense` for data fetching with `React.lazy` or libraries. |
| `16-03-starttransition` | `useTransition` for non-urgent updates. |
| `16-04-usedeferredvalue` | `useDeferredValue` for deferred rendering. |
| `16-05-concurrent-mode` | Understanding concurrent rendering concepts. |
| `16-06-server-components-intro` | React Server Components (with Next.js or RSC demo). |
| `16-07-streaming-ssr` | Streaming server-side rendering (overview, Next.js). |

---

## Module 17: Styling

| Subfolder | Description |
|-----------|-------------|
| `17-01-css-modules` | Scoped CSS with CSS Modules. |
| `17-02-styled-components` | CSS-in-JS with Styled Components. |
| `17-03-emotion` | Emotion library for CSS-in-JS. |
| `17-04-tailwind-css` | Utility-first CSS with Tailwind. |
| `17-05-sass` | Sass preprocessor, variables, mixins. |
| `17-06-css-in-js-comparison` | Comparing different CSS-in-JS libraries. |
| `17-07-ui-libraries` | Material-UI, Ant Design, Chakra UI usage. |
| `17-08-theming-dark-mode` | Theme context, CSS variables, dark mode toggle. |

---

## Module 18: React Architecture

| Subfolder | Description |
|-----------|-------------|
| `18-01-project-structure` | Feature-based structure, atomic design, folder organization. |
| `18-02-component-design-principles` | SOLID, DRY, component cohesion. |
| `18-03-design-patterns` | Container/presentational, custom hooks pattern, provider pattern. |
| `18-04-dependency-injection` | Using Context for dependency injection, testing benefits. |
| `18-05-reusable-component-library` | Building a small design system, publishing components. |
| `18-06-monorepo-setup` | pnpm workspaces, Turborepo, sharing code. |
| `18-07-micro-frontends` | Module Federation, splitting app into micro frontends. |

---

## Module 19: React Security

| Subfolder | Description |
|-----------|-------------|
| `19-01-xss-prevention` | Escaping output, avoiding `dangerouslySetInnerHTML`. |
| `19-02-sanitization` | Sanitizing HTML with DOMPurify. |
| `19-03-csrf-protection` | CSRF tokens, same-site cookies. |
| `19-04-cors` | Configuring CORS, preflight requests. |
| `19-05-token-security` | Secure token storage, httpOnly cookies, localStorage risks. |
| `19-06-content-security-policy` | Implementing CSP headers. |
| `19-07-dependency-audit` | `npm audit`, Snyk, keeping dependencies secure. |

---

## Module 20: Deployment

| Subfolder | Description |
|-----------|-------------|
| `20-01-build-optimization` | `npm run build`, analyzing bundle, environment variables. |
| `20-02-environment-variables` | `.env`, Vite env variables, mode-specific. |
| `20-03-deploy-vercel` | Deploying to Vercel. |
| `20-04-deploy-netlify` | Deploying to Netlify. |
| `20-05-deploy-aws` | S3 + CloudFront deployment. |
| `20-06-docker` | Containerizing React app with Docker. |
| `20-07-ci-cd` | GitHub Actions for CI/CD. |
| `20-08-ssr-deployment` | Deploying SSR apps (Next.js) on Vercel/Node. |

---

## Module 21: Projects  
*(Each is a larger, full-featured React Vite project integrating all previous concepts.)*

| Subfolder | Description |
|-----------|-------------|
| `21-01-ecommerce-app` | Product listing, cart, checkout, auth, API integration. |
| `21-02-social-media-dashboard` | User feed, posts, likes, comments, profiles. |
| `21-03-task-management-app` | Kanban board, drag-and-drop, CRUD. |
| `21-04-chat-application` | Real-time chat, WebSockets, rooms. |
| `21-05-blog-platform` | Blog posts, Markdown, comments, admin panel. |
| `21-06-portfolio-website` | Portfolio with animations, contact form. |
| `21-07-admin-dashboard` | Data visualization, charts, tables. |
| `21-08-video-streaming-app` | Video list, player, comments (YouTube clone). |
| `21-09-food-delivery-app` | Menu, cart, order tracking. |
| `21-10-real-estate-listing` | Listings, maps, filters. |

---

## Full-Stack Add-On: Express & MongoDB  
*(Each subfolder is a full-stack project with a React Vite frontend and an Express/MongoDB backend.)*

| Subfolder | Description |
|-----------|-------------|
| `FS-01-express-setup` | Express server, routes, middleware, basic API. |
| `FS-02-rest-api-crud` | Building a RESTful API with CRUD operations. |
| `FS-03-mongodb-mongoose` | MongoDB connection, Mongoose models, schema. |
| `FS-04-auth-jwt` | JWT authentication, protected routes, user model. |
| `FS-05-file-upload` | File upload with Multer, storing files. |
| `FS-06-validation-error-handling` | Input validation, error handling middleware. |
| `FS-07-deployment-fullstack` | Deploying frontend and backend (e.g., Vercel + Render). |

---

## Final Cheat Sheet  
| Subfolder | Description |
|-----------|-------------|
| `cheat-sheet` | A React Vite app that displays a comprehensive cheat sheet of React concepts, hooks, patterns, and common snippets. |

## Final Interview Revision  
| Subfolder | Description |
|-----------|-------------|
| `interview-revision` | A React Vite app with flashcards, key concepts, and interview questions for quick revision. |

---

This structure ensures **no topic is missed** and provides a hands-on project for every concept, building from zero to full-stack proficiency.
---


