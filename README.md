# How to localize robots

```bash
cd robarch_ws

catkin build robarch_launcher

source devel/setup.bash

roslaunch robarch_launcher ur_robot_fabrication.launcher
```


# How to plan robot motion

1. Install required tools (see [here](#requirements))
2. Click `Use this template` on Github (you need to be logged in to Github)
3. Clone your new and shiny repo (eg. using `Github Desktop`)
4. Prepare your environment to [get started](#getting-started)
5. Delete this section of this document!
6. Replace all `REPLACE_ME` placeholders

## Requirements

Install the following tools:

- [Anaconda](https://www.anaconda.com/products/individual)
- [Visual Studio Code](https://code.visualstudio.com/) and extensions: [python](https://marketplace.visualstudio.com/items?itemName=ms-python.python), [pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) and [editorconfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [Github Desktop](https://desktop.github.com/)

## Getting started

Create a environment using `Anaconda prompt`:

    cd FOLDER_OF_REPO
    conda env create -n NAME_OR_TITLE -f environment.yml

Activate the environment:

    conda activate NAME_OR_TITLE
    python -m compas_rhino.install

Open folder in Visual Studio Code:

    code .

Select your environment from the lower left area in Visual Studio Code.


🚀 You're ready! 

Start coding on `example.py` and explore the `example_grasshopper.ghx` file.

## Additional ideas

A few additional things to try:

1. On Visual Studio Code, press `Ctrl+Shift+P`, `Select linter` and select `flake8`
1. To auto-format code, `right-click`, `Format document...`
1. (Windows-only) Change shell: press `Ctrl+Shift+P`, `Select Default Shell` and select `cmd.exe`
1. Try git integration: commit, pull & push are all easily available from Visual Studio Code.
