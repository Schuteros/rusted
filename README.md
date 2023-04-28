# rusted
A Linux Desktop Enviroment (DE) written in Rust programming language (Rust). Let's see where it goes! ((The project will be stopped for some time to learn more about linux))

## To-do list for minimal working version
1. Create WM (Window Manager) code with x11rb crate which will open on the start a window with rust-based terminal.
2. Make a shortcut which let's user to toggle on/off terminal window
3. Make a handler which resolves opening of new windows
4. Enable window resizing graphically

### Structure of Lindux DE
1. Window manager - windows display information, applications, erros, etc.
2. Menu - allows access to different applications or settings trough Graphical User Interface (GUI).
3. Icons - graphical representation of button which is shortcut to application or other things.
4. Widgets - panels with different kind of functions (something like Gnome Extensions)

### Elements of interaction
1. Cursor
2. Pointer
3. Insertion Point
4. Selection
5. Adjustment handle

## For newbies like me
1. Read about Window Manager: [WM](https://wiki.archlinux.org/title/Window_manager)
2. Read about X protocol here which is going to be used in this project: [X](https://wiki.archlinux.org/title/Xorg)
3. Then you can look into x11rb crate:
   - Git repository : [repository](https://github.com/psychon/x11rb)
   - Docs.rs for x11rb will show the documentation of x11rb crate: [docs.rs](https://docs.rs/x11rb/latest/x11rb/)

## Reference
* Desktop Enviroment elements: [DE](https://en.wikipedia.org/wiki/List_of_graphical_user_interface_elements)
* Window Manager (WM): [WM](https://wiki.archlinux.org/title/Window_manager)
* x11rb crate: [x11rb-git](https://github.com/psychon/x11rb), [x11rb -docs.rs](https://docs.rs/x11rb/latest/x11rb/)
* X protocol: [X](https://wiki.archlinux.org/title/Xorg)
