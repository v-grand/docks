# Documentation Repository Template

This repository is a template for project documentation.

## Local Development

To run the documentation site locally, use the following command:

\`\`\`bash
mkdocs serve
\`\`\`

## Publishing

To publish the documentation, use the following command:

\`\`\`bash
mkdocs gh-deploy
\`\`\`

## Adding Pages and Notebooks

To add a new page, create a new Markdown file in the \`docs\` directory and add it to the \`nav\` section of \`mkdocs.yml\`.

To add a new notebook, place the \`.ipynb\` file in the \`notebooks\` directory. It will be automatically converted and included in the documentation.