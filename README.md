# rusted
A Linux Desktop Enviroment (DE) written in Rust programming language (Rust). Let's see where it goes!

## To-do list for minimal working version
1. Find information and lay down the structure needed for basic Linux DE
2. Find crates which can help us on the way
3. Good luck for all of us!

### Structure of Lindux DE
1. Window manager - windows display information, applications, erros, etc.
2. Menu - allows access to different applications or settings trough Graphical User Interface (GUI).
3. Icons - graphical representation of button whuich is shortcut to application or other things.
4. Widgets
5. Tabs

### Elements of interaction
1. Cursor
2. Pointer
3. Insertion Point
4. Selection
5. Adjustment handle

## For newbies like me
1. Read about Desktop Enviroment elements: [DE](https://en.wikipedia.org/wiki/List_of_graphical_user_interface_elements)
2. Then you can look into wayland:
  2.1. Architecture can be found here which is crucial to understand at least at some level: [architecture](https://wayland.freedesktop.org/architecture.html)
  2.2. You could also look at FAQ of Wayland: [FAQ](https://wayland.freedesktop.org/faq.html)
  2.3. Additionaly you can look more into the Wayland trough its ducomentation: [DOCS](https://wayland.freedesktop.org/docs/html/)
3. It could be good to review Wayland trough Wayland book: [book](https://wayland-book.com/introduction.html)
4. We are using smithay crate to interact with Wayland protocol and here you can learn more about it: [smithay](https://smithay.github.io/book/intro.html)

## Reference
* Desktop Enviroment elements: [DE](https://en.wikipedia.org/wiki/List_of_graphical_user_interface_elements)
* Wayland (window system protocol and architecture): [Wayland](https://wayland.freedesktop.org)
* Intro to Wayland: [intro](https://wayland-book.com/introduction.html)
* Wayland with Rust trough smithay crate: [smithay](https://smithay.github.io/book/intro.html)
