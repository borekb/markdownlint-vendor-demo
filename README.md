# markdownlint vendor demo

Demo for [DavidAnson/vscode-markdownlint#38](https://github.com/DavidAnson/vscode-markdownlint/issues/38)

1. Clone this repo
2. Open `README.md` in VSCode.
3. Press Ctrl+T (*Go to Symbol in Workspace*)

You should see a lot of hits from `vendor`:

![image](https://user-images.githubusercontent.com/101152/40686721-98081a96-6398-11e8-85be-874c7697f44d.png)

Also, the problems panel will show lint results of library files:

![image](https://user-images.githubusercontent.com/101152/40686768-bc191b42-6398-11e8-8c6e-fb5ba86554de.png)

All this with just README.md open.

## node_modules are fine

Try the same as above, you should *not* be getting hits from `node_modules`, i.e., everything behaves correctly.
