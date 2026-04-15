# Skeleton

## 1. Description

A Skeleton component is a loading placeholder that previews the structure and layout of content before the actual data has loaded. It represents the shape and spacing of elements such as text blocks, images, or cards without displaying real content. This helps users understand what to expect and reduces perceived waiting time by signalling that the interface is actively preparing the page.

## 2. Usage

### When to Use

Use a Skeleton when content takes noticeable time to load and the final layout is known in advance. It is particularly effective for pages with structured content such as lists, cards, or detail views where maintaining layout stability improves the experience. Avoid using it as a permanent stand-in for missing content or on pages where loading is nearly instantaneous.

### Do
- Use when loading takes longer than 0.3 seconds on average
- Apply when multiple elements load at once
- Replace each placeholder with content as soon as it loads
- Use to reduce perceived wait times and reassure users
- Use Progress Indicators for long-running processes such as imports

### Don't
- Use for very quick loading pages
- Show a placeholder for a single simple item
- Wait for all content to load before replacing the placeholder
- Use as permanent filler for unfinished or unavailable features
- Use placeholders for background or extended processes

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
