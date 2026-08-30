# JupyterLab and Jupyter Notebook Tutorial

## Jupyter Notebook vs. JupyterLab

Jupyter is an open-source tool for creating and sharing documents that contain live code, visualizations, equations, and text.

## What is Jupyter Notebook?

- A simple, interactive environment to write and run code.
- Each document (called a notebook) is saved as a `.ipynb` file.
- Useful for quick prototyping, data exploration, and teaching.
- A **cell** in Jupyter Notebook is a container where you can write and run code, markdown, or raw text.

**Start Jupyter Notebook** by typing:

```bash
conda install jupyter
```

followed by:

```bash
jupyter notebook
```

## What is JupyterLab?

JupyterLab is the next-generation interface for Jupyter, offering a more advanced and flexible workspace.

### Why We Use JupyterLab

- **Multi-Panel Interface:** Open notebooks, terminals, text editors, and outputs side by side.
- **Better Navigation:** File browsing and workspace management are easier.
- **Extensions:** Customize with themes and advanced plugins.
- **Integrated Tools:** Combine notebooks with terminals and markdown in one window.

**Start JupyterLab:**

```bash
conda install jupyterlab
jupyter lab
```

## Key Differences

| Feature | Jupyter Notebook | JupyterLab |
|---|---|---|
| Interface | Single document view | Multi-tab, multi-panel |
| Customization | Limited | Extensive via extensions |
| Performance | Lightweight | Slightly heavier |
| Use Case | Quick tasks, tutorials | Large projects, workflows |

## When to Use What

- **Jupyter Notebook:** Simple analysis, tutorials, and quick checks.
- **JupyterLab:** Complex projects, interactive dashboards, and better organization.

## Why We'll Use JupyterLab

We will use JupyterLab because it provides:

- **Better Workflow** – Manage multiple notebooks and files in one view.
- **Scalability** – Ideal for data science and machine learning projects.
- **Future-Proofing** – JupyterLab is actively developed and might eventually replace Jupyter Notebook (my personal opinion).