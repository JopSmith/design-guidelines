# Paginator

## 1. Description

A Paginator component divides large sets of content into multiple pages and provides controls to navigate between them. It displays the total number of pages, indicates the current page, and includes navigation elements such as next, previous, and direct page selection. A Paginator helps manage large volumes of data by limiting how much content is shown at one time.

## 2. Usage

### When to Use

Use a Paginator when presenting extensive lists, tables, or search results that would otherwise create long and difficult-to-scan pages. It is particularly useful for improving performance and readability by keeping each view focused and manageable.

### Do
- Use a Paginator when there are more than 25 items in one view
- Use page list pagination for small, fixed sets of pages
- Use a page selector when there are fewer than 12 pages
- Use page selector pagination for larger datasets
- Always show the current page and total number of pages
- Place table pagination at the bottom right under the table

### Don't
- Display very long lists without breaking them into pages
- Use complex pagination patterns for simple datasets
- Hide page numbers or remove context about total pages
- Force users to scroll through hundreds of items on a single page
- Obscure which page the user is on
- Position pagination controls in inconsistent or unexpected locations

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
