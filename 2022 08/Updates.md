---
marp: true
---
<br><br><br><br><br><br>
# Jupyter notebooks in VS Code
August 2022 updates

---
## Updates
1. Core notebooks development experiences
2. Getting started with notebooks
3. Working with remote Jupyter servers *

## Try it out
1. Notebooks on vscode.dev / github.dev *
2. Pre-release version
3. Jupyter PowerToys extension

![bg w:350 right:40%](images/jupyter%20vsc.jpeg)

---
## Core notebooks development experiences (1 of 2)
_for a smoother UX that works "as expected"_

- Cell collapsing with blue bar
- Sticky scrolling nb cell buttons for long code cells
- Cell execution hints
    - Notebooks progress bar
    - `Go to…` running cell / most recently failed cell
    - Animated running icon when executing via settings: `notebook.outline.showCodeCells`
- Support for named indexes on the Data Viewer

---
## Core notebooks development experiences (2 of 2)
- "New File…"<br>![](images/two%20new%20files.png)
- Copy plot images to clipboard 🤩
- Search (over a few iterations)
    - Filtering text search for (1) md source, (2) rendered md, (3) code cell source, and (4) code cell output
    - Search results decorations in the scroll bar
    - Seeding search query from editor selection

---
## Getting started with notebooks
- "Get started" walkthrough
- Reducing unnecessary user interactions in 2 flows
    - No extensions installed --> runnable cells
    - Python extension not installed --> runnable cells
- Ex)
![w:950](images/install%20suggestions.png)

---
## Working with remote Jupyter servers
- Confusing remote/local server indication ➡️
- Mixed kernel options displayed⬇️<br>![w:700](images/local%20kernel%20suggested.png)
- Window reloads when switching between local & remote Jupyter servers 😖

![bg w:450 right:38%](images/local%20kernel%20remote%20server.png)

---
## Notebook experiences on the web
- Web extension for use in `vscode.dev` and `github.dev`
- Support still limited
    - Currently available features/support: https support, kernel completions, ipywidgets, nb debugging, variable viewing, exporting, IW, exporting IW, debuggin in IW, collapsible cells in IW, plot viewer, df viewer
    - +Copy links from vscode.dev ✨
<br>
> Connect to local kernel via remote Jupyter server connection:
`jupyter notebook --no-browser --NotebookApp.allow_origin='*'`

<br>
More on this here: https://github.com/microsoft/vscode-jupyter/discussions/10315

---
## Try out experimental features
- Pre-release version of the `Jupyter` extension<br>![](images/pre%20release.png)
- The `Jupyter PowerToys` extension
	- Kernel management panel
	- Contextual help panel
	- Execution grouping