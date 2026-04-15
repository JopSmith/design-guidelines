# DatePicker

## 1. Description

A DatePicker allows users to select a specific date from a calendar view rather than typing it manually. It typically appears as an input field that, when activated, displays a pop-up calendar where users can navigate between months and years to choose a date or date range.

DatePickers often include features such as date formatting, minimum and maximum date constraints, disabled dates, and localisation support. In some cases, they can optionally include a TimePicker, enabling users to select both a date and a specific time within the same component.

## 2. Usage

### When to Use

Use a DatePicker when users need to enter a date and accuracy, consistency, or ease of use is important — such as booking appointments, scheduling events, setting deadlines, or capturing birthdates. It is especially helpful when you want to reduce input errors, enforce rules (e.g. preventing past dates or limiting selection ranges), allow users to specify an exact date and time, or provide a faster alternative to manual date entry.

### Do
- Use a DatePicker for any field involving scheduling, booking, filtering by date range, or auditing
- Show a clearly labelled field with a calendar icon button to open the calendar
- Allow manual entry if the format is predictable and validated (e.g. DD/MM/YYYY), and mirror that entry back into the picker
- Use helper text to describe constraints (e.g. "Select a date within the next 30 days")
- Use a range picker (start + end) when filtering data by time window

### Don't
- Ask users to manually type formatted dates if that date must follow a specific rule or range
- Rely only on placeholder text to indicate what the date refers to — labels are required
- Force a calendar-only selection for power users entering known dates (slows them down)
- Fail silently when the user picks an out-of-range or invalid date
- Make users select start and end dates in two unrelated controls with no visual connection

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
