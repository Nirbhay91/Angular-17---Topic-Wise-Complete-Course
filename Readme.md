# Angular 17 - Topic Wise Complete Course

## Angular Introduction
- What is Angular?
- Angular Environment and IDEs
- Installing Angular CLI and Creating a Sample Project
- Understanding Directory Structure and Configuration Files
- Bootstrapping Angular Application
- Role of `AppModule` and Component Declaration
- Angular CLI Commands
- Installing Bootstrap and Styling the Application
- Decorators in Angular
- NgModules

## Components
- What are Components?
- Creating Components with CLI & Nesting Components
- Component Templates and Component Styles
- Passing Data Between Components

## Standalone Components
- What are Standalone Components?
- Advantages of Standalone Components
- Using Standalone Components
- Referring Standalone Components from Non-Standalone Components and Vice Versa

## Data Binding
- Data Binding
- String Interpolation
- Property Binding
- One-Way Binding
- Two-Way Binding
- Event Binding

## Directives
- Understanding Directives
- Structural Directives and Attribute Directives
- Using `ngIf` to Output Data Conditionally
- Enhancing `ngIf` with an Else Condition
- Styling Elements Dynamically with `ngStyle`
- Applying CSS Classes Dynamically with `ngClass`
- Outputting Lists with `ngFor`
- Getting the Index with `ngFor`
- Using `trackBy` to Improve Performance
- Understanding `ngSwitch`
- Creating Custom Attribute and Structural Directives
- Using `HostListener` to Listen to Host Events
- Using `HostBinding` to Bind to Host Properties

## Debugging and Error Handling
- Understanding Angular Error Messages
- Using VS Code to Debug Angular Applications
- Using Angular DevTools
- Creating and Using Global Custom ErrorHandlers
- Using the New `ng` Object

## Controlling CSS Scope
- Understanding View Encapsulation
- Shadow DOM
- Emulated

## Lifecycle Hooks
- Understanding the Component Lifecycle
- Seeing Lifecycle Hooks in Action
- Tracking Changes
- Lifecycle Hooks and Template Access
- Accessing the Template & DOM with `@ViewChild` & `@ViewChildren`
- Projecting Content into Components with `ng-content`
- Accessing `ng-content` with `@ContentChild` & `@ContentChildren`
- New Lifecycle Hooks in Angular

## Pipes
- Pure and Impure Pipes
- Using Built-In Pipes
- The `PipeTransform` Interface
- Creating Custom Pipes
- Performance Implications of Impure Pipes
- Standalone Pipes

## Signals
- Need for Signals
- Readonly & Writable Signals
- `set()`, `compute()`, `effect()`, `update()` Methods
- Signal Inputs
- Model Inputs
- `viewChild` & `contentChild` Queries
- Passing Data Between Components Using Signals

## New Control Flow (Block Directives)
- Declarative Control Flow
- `@for`
- `@if`
- `@switch` Statements
- Keywords in `@for`

## Deferrable Views / Deferred Rendering
- `@defer` Block
- `@placeholder` Block
- `@loading` Block
- Understanding Triggers in `@defer`
  - on Idle
  - on Viewport
  - on Interaction
  - on Hover
  - on Immediate

## New Features and Deprecations
- Nullish Coalescing Operator (`??`)
- Non-Null Assertion Operator (`!`)
- Strict Type Checking
- Strict Mode Properties
- Disabling Strict Mode Type Checking
- Directive-Composition API
- `takeUntilDestroyed` Operator
- `DestroyRef`
- Changes to `@Component` Annotation
- `REMOVE_STYLES_ON_COMPONENT_DESTROY` Token
- Integration with Bun.js

## Introduction to Forms Programming
- Building Forms
- Template Forms and Reactive Forms
- Understanding `FormBuilder`, `FormGroup`, `FormControl` Classes
- Basic Form Validation

## Introduction to RXJS and HTTP Programming
- Need for RXJS Library
- Promises vs RXJS
- Observables, Observer, Subject
- Types of Subjects
- RXJS Operators
- `subscribe()`
- `next()`

## Introduction to Routing
- Introduction to Routing
- Route Definition Object
- Router Outlets
- Passing Parameters to Routes
- Lifecycle of Router
- Implementing Guards and Resolvers
- Creating Nested Routes
- `Router.forChild`
- `Router.forRoot`
- Location Strategies
- Binding Route Parameters to Component Inputs

---

# Angular 17 - Advanced Topics (S2)

## Forms Programming
- Forms Programming Recap
- Creating Custom Validators
- Implementing Asynchronous Validations
- Conditional Validations
- Dynamic Forms
- Submitting Form Data to the Server

## RXJS and HTTP Programming
- RXJS Recap
- Consuming Web Services
- Passing Parameters Using HTTP Headers
- Creating Custom HTTP Interceptors
- Error Handling in RXJS

## Using Services & Dependency Injection
- Understanding DI in Angular
- Constructor-Based Hierarchical Injector
- Singleton and Non-Singleton Objects
- Using Service Classes
- Working with DI Decorators
  - `@Injector()`
  - `@Injectable()`
- Working with Providers
  - `useClass`
  - `useValue`
  - `useFactory`
  - `useExisting`
- Avoiding Name Collisions Using InjectableTokens
- The `inject()` Function

## Creating Progressive Web Applications (PWA)
- Enabling PWA in Angular Applications
- Caching Assets for Offline Use
- Caching Dynamic Assets & URLs
- Testing PWA Readiness
- Working with Service Workers
- `SWPush` and `SwUpdate`

## Angular Universal (SSR)
- Server-Side Rendering (SSR)
- Client-Side Rendering (CSR)
- SSR vs CSR
- Implementing SSR with Angular Universal
- Static Site Generators

## Web Components
- Web Component Specification
- Custom Elements
- Custom Elements Architecture
- Creating Custom Elements for Use in Other Frameworks/Libraries

## Loading Strategies
- Lazy Loading Components
- Eager Loading
- Preloading
- Feature Modules
- Shared Modules
- Core Modules

## Unit Testing
- Unit Testing with Karma and Jasmine
- Using Cypress for Unit Testing
- Using Jest, WebDriver for Unit Testing
- Testing Components and Directives

## Creating Mocks and Using Spies
- Testing Services
- Deploying Angular Applications
  - Angular Budgets
  - Hosting Angular Applications
  - Deploying Angular Apps to Cloud Platforms
  - Dockerizing Angular Applications
```
