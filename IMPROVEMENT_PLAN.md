# Improvement Plan: angular-app

## Overview
Minimal Angular sandbox with almost no content — essentially an empty scaffold. Needs a clear purpose and implementation to be useful.

## Improvements

### Define a Purpose
- Choose a concrete feature to implement (e.g., a component library demo, a form validation showcase, or an Angular Signals demo) so the repo has a clear learning goal
- Add a README describing the purpose, what patterns it demonstrates, and how to run it

### Modernization
- Upgrade to Angular 19+ if on an older version
- Adopt standalone components (no NgModule) as the default pattern
- Add Angular Signals for reactive state management to demonstrate modern patterns

### Testing
- Add at least one unit test per component using Jest or Karma
- Add a simple e2e test with Playwright

### Code Quality
- Enable TypeScript `strict` mode
- Add ESLint with Angular rules
- Add Prettier for formatting

### DevOps
- Add GitHub Actions CI: lint + test + build on every push
