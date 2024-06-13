# Sims 4 Mod Project Template

This template comes with automated building. It supports versioning of all files.

## Dependencies

- This template is made for [Visual Studio Code](https://code.visualstudio.com/).
- [Sims 4 Mod Development Tools](https://github.com/SanjoSolutions/sims4-mod-development-tools?tab=readme-ov-file#sims-4-mod-development-tools) for compiling the Python scripts.
- The Visual Studio Code extension [Sims 4 Toolkit](https://github.com/SanjoSolutions/s4tk-vscode/releases/download/0.2.4-with-build-task-fix/s4tk-vscode-0.2.4-with-build-task-fix.vsix) for creating the mod package. The linked file includes a fix for running the build command with a task. After the file has been downloaded, it can be installed in Visual Studio Code by opening the "Extensions" side bar, clicking on the three dots, selecting "Install from VSIX..." and then selecting the downloaded file.

## Adjusting the template for your project

- Replace `<AUTHOR_NAME>` in all files with your author name.
- Replace `<MOD_NAME>` in all files with your mod name.
- Rename the folder `src/code/Author/ModName` to your mod name.
- Rename the folder `src/code/Author` to your author name.
- It might be required to adjust the path to "sims4-mod-development-tools" in the file `.vscode/tasks.json`.

## License

This template is released under a MIT-0 license (see LICENSE).
With this license you can license you project that is based on this template under any license.
You can also remove the LICENSE file.
