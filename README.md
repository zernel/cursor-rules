# Cursor Rules Project Template

This project serves as an initialization template for new projects. After cloning, you can directly copy the `.cursor` and `docs` directories to quickly set up the basic documentation and rule system for your project.

## Directory Structure

- `.cursor/`: Stores project rules, error logs, lessons learned, and other files related to automation and AI assistance.
  - `rules/`: Recommended location for rule files, error documentation (`error-documentation.mdc`), and lessons learned (`lessons-learned.mdc`).
- `docs/`: Contains core project documentation, including requirements, architecture, technical solutions, and active development context.
  - `product_requirement.md`: Product Requirement Document (PRD), describing project goals, core requirements, and problems to be solved.
  - `architecture.md`: System architecture document, describing system components, relationships, dependencies, and overall flow.
  - `technical.md`: Technical solution and development environment, including technology stack, environment setup, and key technical decisions.
  - `active_context.md`: Active development context, serving as the single source for task planning, progress tracking, current work, active decisions, known issues, and next steps.

## Usage

1. Clone this project:
   ```bash
   git clone <repository-url> your-new-project
   cd your-new-project
   ```
2. Copy the `.cursor` and `docs` directories to the root of your new project:
   ```bash
   cp -r .cursor docs <your-new-project-directory>
   ```
3. Complete your project documentation by following the instructions in each template file under the `docs/` directory.

## Recommended Workflow

- All project-related requirements, architecture, technical details, and development context should be documented in the corresponding files under the `docs/` directory.
- For detailed documentation structure and content templates, refer to the files in the `docs/` directory.