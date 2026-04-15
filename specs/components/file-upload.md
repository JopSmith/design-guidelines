# FileUpload

## 1. Description

A FileUpload allows users to attach and submit files within an interface. It may appear as a button that opens a file selector for single file uploads, or as a dropzone that supports dragging and dropping multiple files. The component typically provides feedback on selected files, upload progress, and any validation requirements such as file type or size limits.

## 2. Usage

### When to Use

Use a FileUpload component when users need to provide documents, images, or other supporting materials as part of a task or form submission. A button-based upload is suitable for simple, single-file needs, while a dropzone is more appropriate when multiple files are expected or when a more flexible interaction is beneficial.

### Do
- Use a button upload for simple single-file submissions
- Use a dropzone when multiple files are expected or drag and drop improves efficiency
- Clearly communicate accepted file types and size limits
- Provide clear feedback on upload progress and completion
- Allow users to remove or replace files before submission
- Ensure accessibility through keyboard interaction and clear labelling

### Don't
- Use a complex dropzone when only one file is required
- Restrict users to drag and drop only without providing a clickable alternative
- Wait until after submission to reveal validation rules
- Leave users uncertain about whether a file has uploaded successfully
- Lock users into a selection without an option to change it
- Rely solely on visual cues to explain how uploading works

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
