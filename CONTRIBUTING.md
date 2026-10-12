# Organization guide

## Notebooks

- Store lessons in `notebooks/`.
- Use a two-digit sequence number and lowercase words separated by underscores: `01_python_and_data_types.ipynb`.
- Keep one main lesson or topic per notebook.
- Add new notebooks to the root README in learning order.
- Update README links and Colab badge URLs when moving or renaming notebooks.
- Preserve exercise prompts and personal notes. Label deliberate errors and incomplete exercises.
- Review saved outputs before committing, especially large results or personal information.

## Other materials

Create these folders when you have files to put in them:

- `data/`: small datasets you are permitted to share. Include a README describing sources, columns, units, and usage restrictions.
- `src/`: reusable Python code extracted from notebooks.
- `docs/`: supporting explanations and project notes.
- `assets/`: images referenced by notebooks or documentation.

For large external datasets, document where to obtain them and where to place them instead of committing them.

## Dependencies

The current notebook uses Python built-ins. If future lessons require external libraries, document them and add a requirements file with tested versions.

## Before saving changes

1. Check that documentation links point to the correct files.
2. Confirm notebooks open successfully.
3. Run changed code cells where appropriate, accounting for interactive input and deliberate exercise errors.
4. Review the Git diff for unintended changes.
