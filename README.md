# HIPPO-BRAIN Management System

A comprehensive, professional platform for managing, editing, validating, and exporting structured AI instruction modules. Built with Next.js, TypeScript, and modern web technologies.

> **🔒 Private Project**: This is a private project. The source code is not publicly available.  
> **👉 Use the live demo below to explore and use the system.**

## 🌐 Live Demo

**👉 [Try it now - Live Application](https://hippo-brain-management-system-promp.vercel.app/)**

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-blue?style=for-the-badge)](https://hippo-brain-management-system-promp.vercel.app/)

The system is live and ready to use at: **https://hippo-brain-management-system-promp.vercel.app/**

**No installation required** - just open the link and start using the system!

## System Demo

Watch the system in action:

[![HIPPO-BRAIN Management System Demo](https://img.youtube.com/vi/AdKFEO9k0a8/maxresdefault.jpg)](https://www.youtube.com/watch?v=AdKFEO9k0a8&autoplay=1)

*Click the image above to watch the demo video on YouTube (video will start automatically)*

> **Note:** GitHub doesn't support autoplay in README files for security reasons. The video will autoplay when you click the link and open it on YouTube.

## Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Solution](#solution)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Usage Guide](#usage-guide)
- [Module System](#module-system)
- [License](#license)

## Overview

The HIPPO-BRAIN Management System is an advanced web application designed to manage complex AI instruction sets in a structured, modular format. It provides a complete ecosystem for creating, organizing, validating, and exporting AI prompts and instructions, making it easier to maintain consistency and quality in AI interactions.

## Problem Statement

Managing AI instructions and prompts at scale presents several challenges:

- **Lack of Structure**: Traditional prompt management relies on unstructured text files, making it difficult to organize, maintain, and version control instructions.
- **Inconsistency**: Without a systematic approach, instructions can become contradictory, duplicated, or inconsistent across different contexts.
- **Scalability**: As instruction sets grow, it becomes increasingly difficult to find, update, and manage specific rules or guidelines.
- **Validation**: There's no automated way to detect conflicts, duplicates, or missing dependencies in instruction sets.
- **Reusability**: Instructions are often duplicated or recreated instead of being modularized and reused across different contexts.
- **Export Flexibility**: Different AI models and use cases require different formats and subsets of instructions.

## Solution

The HIPPO-BRAIN Management System addresses these challenges by providing:

1. **Structured Module System**: Instructions are organized into modular JSON files with clear hierarchies, dependencies, and metadata.
2. **Comprehensive Validation**: Automated detection of duplicates, contradictions, circular dependencies, and inconsistencies.
3. **Advanced Editor**: JSON editor with syntax highlighting, validation, and auto-fix capabilities.
4. **Flexible Export**: Export instructions in multiple formats (text, markdown, PDF) with customizable filtering and ordering.
5. **Profile System**: Create and manage different instruction profiles for different use cases (e.g., coding, design, analysis).
6. **Custom Modules**: Extend the system with user-defined modules stored locally.
7. **Search & Discovery**: Powerful search functionality to find specific rules, modules, or content.
8. **Visualization**: Interactive views, mind maps, and dependency graphs for better understanding.

## Features

### Dashboard
- **Overview Statistics**: Total modules, rules, items, and categories at a glance
- **Category Breakdown**: Visual representation of modules organized by category (core, expertise, output, meta)
- **Priority Indicators**: Quick view of critical, important, and optional modules
- **Custom Modules Tracking**: Monitor user-created custom modules
- **Interactive Cards**: Click on statistics to see detailed information and examples

### Module Management
- **Browse All Modules**: View all available instruction modules in an organized grid
- **Category Filtering**: Filter modules by category (core, expertise, output, meta)
- **Priority Filtering**: Filter by priority level (critical, important, optional)
- **Module Details**: View complete module information including rules, subsections, dependencies, and metadata
- **Module Restoration**: Restore previous versions of modules from backup

### JSON Editor
- **Syntax Highlighting**: CodeMirror-powered editor with JSON syntax highlighting
- **Real-time Validation**: Instant feedback on JSON structure and schema compliance
- **Auto-formatting**: Automatic code formatting for consistent style
- **Module Creation**: Create new modules from scratch
- **Module Editing**: Edit existing modules with full validation
- **Custom Modules**: Create and manage custom modules stored in browser localStorage
- **Import/Export**: Import and export individual modules

### Validator
- **Comprehensive Validation**: Detects multiple types of issues:
  - **Duplicates**: Identical or highly similar rules across modules
  - **Contradictions**: Conflicting rules or guidelines
  - **Missing Dependencies**: Modules referencing non-existent dependencies
  - **Circular Dependencies**: Circular reference chains between modules
  - **Inconsistencies**: Formatting, numbering, or structural inconsistencies
  - **Conflicts**: Rules that override or conflict with each other
- **Severity Levels**: Issues categorized as errors, warnings, or info
- **Auto-fix Suggestions**: Automatic fixes for common issues
- **Detailed Reports**: Comprehensive validation reports with actionable insights

### Viewer
- **Formatted Display**: Beautiful, readable display of all instructions
- **Multiple Formats**: View as formatted text or markdown
- **Download Options**: Download instructions as TXT, MD, or PDF files
- **Filtering**: Filter displayed content by category, priority, or specific modules
- **Search Integration**: Search within the viewer

### Search
- **Full-text Search**: Search across all modules, rules, and content
- **Advanced Filtering**: Filter results by module, category, type, or priority
- **Highlighted Results**: Search terms highlighted in results
- **Quick Navigation**: Jump directly to relevant sections

### Export System
- **Multiple Formats**: Export as plain text, markdown, or PDF
- **Flexible Filtering**: Include/exclude specific modules, categories, or priorities
- **Ordering Options**: Order modules by priority, category, alphabetical, or dependency
- **Compression Modes**: None, compact, or minimal formatting options
- **Profile Support**: Export using predefined profiles
- **Custom Headers**: Add custom headers, roles, and identity statements
- **API Access**: Programmatic access via REST API

### Prompt Builder
- **Visual Module Selection**: Select modules via intuitive checkboxes
- **Template Presets**: Pre-configured templates (All Modules, Core Only, Development Focus, Full Stack, Minimal)
- **Custom Configuration**: 
  - Custom header text
  - Role selection
  - Custom identity statements
  - Profile selection
- **Live Preview**: Real-time preview of generated prompt
- **State Persistence**: Save and restore builder state
- **Export Options**: Download generated prompts in multiple formats
- **PDF Generation**: Generate vector PDFs with proper formatting

### Ideation System
- **Idea Management**: Create, edit, and manage project ideas
- **Template System**: Start from predefined templates (API Service, Application Platform, Automation Script, Data Analysis, Developer Tool)
- **Structured Ideas**: Ideas include:
  - Problem statement
  - Goals and objectives
  - Target audience
  - Constraints and requirements
  - Features list
  - Implementation steps
  - Tags and categories
- **Mind Map Visualization**: Visual representation of idea relationships
- **Idea Refinement**: Step-by-step refinement process
- **History Tracking**: Track idea evolution over time
- **Export Ideas**: Export ideas in various formats

### Custom Modules
- **Local Storage**: Custom modules stored in browser localStorage
- **Full Functionality**: Custom modules work identically to built-in modules
- **Isolation**: Custom modules don't affect original project files
- **Import/Export**: Share custom modules via JSON export/import
- **Version Control**: Track custom module versions

### Profiles
- **Use Case Profiles**: Predefined profiles for different scenarios:
  - Coding Deep Work
  - Design Focus
  - Analysis & Insights
  - And more...
- **Module Weights**: Adjust importance of modules per profile
- **Rule Weights**: Fine-tune rule importance
- **Enforcement Modes**: Strict, balanced, or loose enforcement
- **Include/Exclude**: Selectively include or exclude modules
- **Custom Profiles**: Create your own profiles

### Additional Features
- **Dark Mode**: Full dark mode support with theme persistence
- **Responsive Design**: Mobile-friendly interface
- **Accessibility**: WCAG-compliant components and interactions
- **Performance**: Optimized for fast loading and smooth interactions
- **Type Safety**: Full TypeScript coverage for type safety

## Technology Stack

### Core Framework
- **Next.js 14**: React framework with App Router for server-side rendering and API routes
- **React 18**: UI library with hooks and modern patterns
- **TypeScript 5**: Type-safe JavaScript

### Styling & UI
- **Tailwind CSS**: Utility-first CSS framework
- **Framer Motion**: Animation library for smooth transitions
- **Lucide React**: Icon library
- **next-themes**: Theme management (light/dark mode)

### Code Editing
- **CodeMirror 6**: Advanced code editor
- **@codemirror/lang-markdown**: Markdown syntax support
- **@codemirror/theme-one-dark**: Dark theme for editor

### Data & Validation
- **Zod**: Schema validation library
- **JSON Schema**: Structural validation

### Visualization
- **react-force-graph-2d**: Graph visualization for mind maps and dependencies
- **react-markdown**: Markdown rendering

### PDF Generation
- **pdf-lib**: PDF creation and manipulation

### Utilities
- **clsx**: Conditional class names
- **tailwind-merge**: Merge Tailwind classes intelligently

## 🚀 Getting Started

**The system is live and ready to use!**

👉 **[Visit the live application](https://hippo-brain-management-system-promp.vercel.app/)**

No installation or setup required - just open the link and start using the system immediately.

> **Note**: This is a private project. The source code is not available for public access or contribution.

The system is built with a modular architecture using Next.js, TypeScript, and modern web technologies. It includes:

- **Dashboard**: Overview of all modules and statistics
- **Module Management**: Browse, view, and manage instruction modules
- **JSON Editor**: Create and edit modules with validation
- **Validator**: Detect duplicates, contradictions, and inconsistencies
- **Prompt Builder**: Build custom prompts from selected modules
- **Viewer**: View and export instructions in multiple formats
- **Ideation System**: Create and manage project ideas
- **Search**: Full-text search across all modules and rules

## Usage Guide

### Dashboard

The dashboard (`/`) provides an overview of the entire system:

1. **View Statistics**: Click on any statistic card to see detailed information
2. **Browse Modules**: Scroll down to see all modules organized by category
3. **Search**: Use the search bar to quickly find modules or content
4. **Navigate**: Use the navigation menu to access different features

### Managing Modules

#### Viewing Modules
- Navigate to `/instructions` to see all modules
- Click on a module card to view details
- Use category/priority filters to narrow results

#### Editing Modules
1. Navigate to `/editor`
2. Select a module from the dropdown or create a new one
3. Edit the JSON in the editor
4. Click "Save" to save changes
5. Validation errors will be shown if any

#### Creating Custom Modules
1. Go to `/editor`
2. Click "New Module"
3. Fill in the required fields (id, title, category, priority)
4. Add rules and subsections as needed
5. Save - custom modules are stored in browser localStorage

### Using the Validator

1. Navigate to `/validator`
2. Click "Validate" to run validation
3. Review issues grouped by type and severity
4. Click on an issue to see details and location
5. Use "Auto-fix" for issues that support automatic fixing
6. Fix issues manually in the editor

### Exporting Instructions

#### Via UI (Viewer)
1. Navigate to `/viewer`
2. Configure filters (optional)
3. Click "Download TXT", "Download MD", or "Download PDF"
4. File will download with current date in filename

> **Note**: API access is available through the live application interface. For programmatic access, please use the web interface at the live demo link.

### Using the Prompt Builder

1. Navigate to `/builder`
2. **Select Modules**: Check modules to include, or use a template
3. **Configure Options**:
   - Add custom header text
   - Select roles
   - Set custom identity
   - Choose a profile
4. **Preview**: View the generated prompt in real-time
5. **Export**: Download as TXT, MD, or PDF
6. **Save State**: Your configuration is auto-saved to localStorage

### Using the Ideation System

1. Navigate to `/ideation`
2. **Create Idea**: Click "New Idea" or start from a template
3. **Fill Details**:
   - Problem statement
   - Goals and objectives
   - Target audience
   - Constraints and requirements
   - Features
   - Implementation steps
4. **Refine**: Use the refinement process to improve your idea
5. **Visualize**: View mind map of idea relationships
6. **Export**: Export idea in various formats
7. **Track History**: View idea evolution over time

### Search Functionality

1. Use the search bar in the navigation
2. Type your query
3. Results show matching modules, rules, and content
4. Click a result to navigate to the relevant section
5. Use advanced filters to narrow results

### Profiles

Profiles allow you to customize which modules and rules are emphasized:

1. Profiles are defined in `data/profiles.json`
2. Use profiles in the Prompt Builder
3. Profiles control:
   - Module weights (importance)
   - Rule weights
   - Enforcement mode (strict/balanced/loose)
   - Module inclusion/exclusion

## API Access

The system provides REST API endpoints for programmatic access. All API functionality is available through the live application interface.

**Available Endpoints:**
- `/api/modules` - Get all modules or filter by category/priority
- `/api/modules/[id]` - Get specific module details
- `/api/rules` - Get all rules across modules
- `/api/search` - Full-text search across modules and rules
- `/api/stats` - Get system statistics
- `/api/validate` - Run validation checks
- `/api/export` - Export modules in various formats (text, markdown, PDF)
- `/api/profiles` - Get available profiles

> **Note**: For detailed API documentation and usage examples, please use the live application interface.

## Module System

### Module Structure

Each module is a JSON file with the following structure:

```json
{
  "id": "module-id",
  "title": "Module Title",
  "category": "core|expertise|output|meta",
  "priority": "critical|important|optional",
  "version": "1.0.0",
  "lastUpdated": "2024-01-01",
  "dependencies": ["other-module-id"],
  "requires": ["other-module-id"],
  "description": "Module description",
  "keywords": ["keyword1", "keyword2"],
  "relatedModules": ["related-module-id"],
  "author": "Author Name",
  "contributors": ["contributor1"],
  "deprecated": false,
  "deprecatedSince": null,
  "replacedBy": null,
  "rules": [
    {
      "id": "rule-id",
      "content": "Rule content",
      "type": "rule|guideline|principle|capability|requirement|goal",
      "priority": "high|medium|low",
      "tags": ["tag1"],
      "examples": ["Example 1"],
      "relatedRules": ["related-rule-id"],
      "seeAlso": ["module-id", "rule-id"],
      "conflictResolution": {
        "overrides": ["other-rule-id"],
        "overriddenBy": ["other-rule-id"],
        "weight": 1.0
      }
    }
  ],
  "subsections": [
    {
      "id": "subsection-id",
      "title": "Subsection Title",
      "content": "Subsection content",
      "rules": [...],
      "items": ["item1", "item2"]
    }
  ]
}
```

### Module Categories

- **core**: Essential modules defining fundamental behavior (communication, workflow, global-rules)
- **expertise**: Domain-specific knowledge (engineering, design, architecture, financial, quant)
- **output**: Modules controlling output format and presentation (documents, output-format, creativity)
- **meta**: System-level modules (identity, versioning)

### Module Priorities

- **critical**: Must be included in every prompt generation
- **important**: Should be included in most cases
- **optional**: Include based on specific needs

### Rule Types

- **rule**: Specific behavioral instruction
- **guideline**: Recommended practice
- **principle**: Fundamental principle
- **capability**: System capability description
- **requirement**: Mandatory requirement
- **goal**: Objective or goal

## Custom Modules

You can create custom modules directly in the application interface. Custom modules are stored in your browser's localStorage and work identically to built-in modules:

- **Storage**: Custom modules are stored locally in your browser
- **Isolation**: Custom modules don't affect the original system modules
- **Full Functionality**: Custom modules support all features (rules, subsections, dependencies)
- **Import/Export**: Share custom modules via JSON export/import
- **Persistence**: Custom modules persist across page refreshes (browser-specific)

## License

This project is licensed under the Unlicense License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built for the HIPPO-BRAIN AI system
- Inspired by the need for structured AI instruction management
- Community contributions and feedback

## Support

For questions or feedback about the system, please use the live application interface.

> **Note**: This is a private project. The source code repository is not publicly accessible.

---

## 🔗 Links

- **🌐 Live Application**: [https://hippo-brain-management-system-promp.vercel.app/](https://hippo-brain-management-system-promp.vercel.app/)

**Version**: 1.0.0

**Last Updated**: 2025-12-01


