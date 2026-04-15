# DataTable

## 1. Description

A DataTable is a structured component used to display large sets of data in rows and columns. It supports comparison, scanning, and analysis by presenting information in a clear, consistent layout, and may include features such as sorting, filtering, pagination, or row selection.

## 2. Usage

### When to Use

Use a DataTable when users need to review, compare, or manage structured data efficiently. DataTables are well suited for admin interfaces, dashboards, and data-heavy workflows where accuracy and clarity are critical. They work best when the data model is well defined and users need tools to find, organise, or act on specific rows without losing context.

### Do
- Use a DataTable for structured, comparable data
- Clearly label columns with meaningful, concise headers
- Support common tasks like sorting, filtering, or pagination when needed
- Align and format data consistently within columns
- Make rows and actions easy to scan and understand
- Ensure accessibility for keyboard and screen reader users
- Use a multi-select checkbox in the first column to select table rows
- Limit Select All to the current page when a table is paginated
- Use radio buttons for mutually exclusive row selection across the entire table
- Use checkboxes when multiple rows can be selected and retain selections across pages
- Use column headers only for labels and sorting, except for Select All in multi-select columns
- Use icon-only buttons for table actions to save space and improve scannability
- Use the danger severity style for destructive or negative row actions
- Use soft button styles for contextual or stacked table actions
- Use multi-select only when batch actions are supported

### Don't
- Use a DataTable for unstructured or narrative content where a simpler list or card layout would suffice
- Leave columns unlabelled or unclear or use vague or ambiguous names
- Show large datasets without ways to manage or navigate them
- Mix alignment or formatting inconsistently
- Overcrowd rows with too many actions or controls
- Rely on visual cues alone to convey meaning or state
- Make rows selectable by clicking anywhere in the row
- Select rows across all pages by default
- Allow more than one radio button to be selected at the same time
- Treat checkboxes as mutually exclusive or clear them unexpectedly
- Place inputs or components inside column headers
- Use text buttons that clutter compact table layouts
- Style destructive actions the same as neutral or positive actions
- Use high-emphasis button styles for closely grouped actions
- Use multi-select for single-row editing workflows

## 3. Composition

The DataTable consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Actions | Optional | Provides row-level or table-level actions, typically displayed as icon-only buttons to conserve space |
| Batch edit | Optional | Enables users to apply the same action or update to multiple selected rows at once |
| Empty state | Optional | Communicates that no data is available and may provide guidance, context, or next steps |
| Filters | Optional | Enables users to narrow down visible data based on specific criteria |
| Footer | Optional | Displays supplementary information such as totals or summaries |
| Multi-select | Optional | Allows users to select multiple rows using checkboxes for bulk actions or batch operations |
| Pagination | Optional | Breaks large datasets into manageable pages |
| Sorting | Optional | Allows users to reorder rows by column values to quickly find or compare data |

## 4. States

**Status:** Not documented in source material
