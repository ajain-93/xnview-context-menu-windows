# Adding XnView to Windows Explorer Directory Context Menu

1. Open the file `XnView.reg` or `XnViewMP.reg` in a text editor.
2. Change all of the paths to where you installed XnView.
3. Save file
4. Run/Merge the file into the registry.

Now you can right click inside a directory and

![XnView in contextMenu](./xnview_context_menu.png)

[Source for inspiration](https://github.com/cbmeeks/sublime-text-2-context-menu-windows)

## Changelog
2023-05-07:

* Add support for both XnView and XnView MP
* Correct registry path from sublime to xnview/xnviewmp
