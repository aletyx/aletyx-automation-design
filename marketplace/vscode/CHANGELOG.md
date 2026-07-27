# Changelog

## 10.2.0

Version 10.2.0 expands Aletyx Automation Design into a complete DMN development experience inside Visual Studio Code—from modeling and FEEL authoring to local execution, analysis, change review, and AI-assisted development.

### Model decisions faster

- Work in a modernized DMN canvas with Aletyx light and dark themes, clearer hierarchy, improved spacing, and more precise selection.
- Navigate large models with pan-by-default controls, lasso and hand tools, keyboard navigation, and improved zoom behavior.
- Create and manage Decision Services directly on the canvas, including collapse, expand, move, and resize interactions.
- Work with included models and namespaces more reliably, including linked types and cross-model references.
- Recover more gracefully from invalid or partially edited models without losing access to the editor.

### Write and navigate FEEL with confidence

- Use richer FEEL completion, diagnostics, and go-to-definition across decision logic and data types.
- Edit expressions in a larger focused editor with improved inline name editing.
- Author complex contexts, invocations, relations, lists, functions, and nested expressions with clearer structure.
- Get completion for nested enumerations, Java-backed types, and types from included models.

### Build better decision tables and data types

- Create decision-table-only `.dmns` files alongside standard `.dmn` models.
- Use the Priority hit policy in editing, analysis, execution, and result visualization.
- Detect gaps, overlaps, and missing rules in nested decision-table structures.
- Search and import data types, define inline enumerations, and manage nested fields and references more easily.

### Review every model change

- Inspect model changes in a dedicated Changes view with counts, grouping, and focused navigation.
- See granular highlights for model properties, nodes, edges, data types, boxed expressions, decision-table cells, rows, and columns.
- Accept or revert individual changes, logical groups, or all changes at once.
- Keep your active editing context while reviewing changes, with complete dark-theme support.

### Run and verify decisions locally

- Generate input forms from your model and run one or multiple input rows locally.
- Define expected outputs and see clear pass/fail regression results.
- Pin important outputs and visualize evaluation results directly on the diagram and decision tables.
- Run Camunda-compatible models and Priority hit-policy tables more reliably.
- Preserve runner inputs while editing and rerun decisions with fewer interruptions.

### Validate and analyze decision tables

- Review validation and analysis findings from dedicated workbench views.
- Find gaps, overlaps, missing rules, and problems in nested decision logic.
- Open a finding directly in its detailed analysis and focused model highlight.
- Read findings clearly in both light and dark themes.

### Work with Aletyx AI

- Ask Aletyx AI to explain, analyze, and modify DMN models without leaving the editor.
- Review AI-generated edits before accepting or reverting them.
- Generate runner inputs and test cases from your model and conversation.
- Keep conversation history, queue prompts while work is in progress, retry failed requests, and attach supporting files.
- Ask AI about validation and analysis findings from their context menus.
- Configure API access securely from the assistant, with clearer setup, loading, reconnecting, and unavailable states.

### Polished for everyday IDE use

- Use a more compact, responsive layout across regular and smaller editor windows.
- Access editing, execution, validation, analysis, changes, and AI tools with improved keyboard, pointer, and drag behavior.
- Keep filenames valid when renaming files, including protection against trailing dots and surrounding whitespace.
- Benefit from fixes for selection loss, stale highlights, analysis-detail navigation, and editing crashes.
- Configure Java Home and automatic startup for the local decision service from VS Code settings.

## 10.1.2

- New React-based BPMN Editor replacing the classic GWT-based editor
- DMN 1.6 support
- Quarkus 3.27.2 and Spring Boot 3.5.11 stack upgrades
- FEEL and B-FEEL expression language selection
- DMN Editor improvements: Data Types UX, Decision Services, read-only mode, autocompletion
- Security updates addressing recent CVEs
- Removed legacy GWT-based BPMN and DMN editors

## 10.1.1

- Quarkus 3.20.3 and Spring Boot 3.4.10 stack upgrades for enhanced performance and security

## 10.1.0

- Initial release
