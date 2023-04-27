# rusted
A Linux Desktop Enviroment (DE) written in Rust programming language (Rust). Let's see where it goes! ((The project will be stopped for some time to learn more about linux))

## To-do list for minimal working version
1. Create WM (Window Manager) code with winit crate which will open on the start a window with rust-based terminal.
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
2. Then you can look into winit crate:
   - Git repository which has more guided text for newbies: [repository](https://github.com/rust-windowing/winit)
   - Docs.rs for winit will show the documentation of winit crate: [docs.rs](https://docs.rs/winit/0.28.3/winit/)

## Reference
* Desktop Enviroment elements: [DE](https://en.wikipedia.org/wiki/List_of_graphical_user_interface_elements)
* Window Manager (WM): [WM](https://wiki.archlinux.org/title/Window_manager)
* Winit crate: [winit-git](https://github.com/rust-windowing/winit), [winit-docs.rs](https://docs.rs/winit/0.28.3/winit/)
