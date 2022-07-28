# `@duxli/react-data-table`

Unopinionated tools to help create data tables in React.

Includes a [demo app][demo].

## Goals

### Create data tables quickly without needing to use a specific UI library

As a developer, it can be infuriating when the most feature-rich libraries require a large buy-in.

For example, a team may only want to have tables that quickly sort and display rows.
However, most data table libraries enforce that specific UI components are used.
This can conflict with the existing look-and-feel of an app.

### Allow sorting, filtering, and pagination by API calls or client-side handlers

@todo - It's a goal that comes from painfully learned experiences

### Allow selection of rows, columns, or cells

@todo - It's a goal that comes from painfully learned experiences

### Allow simple columns (by key) or complex columns with custom keys

@todo - It's a goal that comes from painfully learned experiences

### Share configurations with contexts

Often times, an app will have very similar requirements for different tables.
Allowing the developer to specify default configuration values with a React context reduces the
burden on the developer and gives them a clear path to keep the configurations in one place.

### Provide table state to children

This reduces re-renders and helps tables load quickly even when they have many elements.

[demo]: ./demo/
