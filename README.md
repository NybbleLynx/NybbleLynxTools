# NybbleLynxTools
This is common library of code split into modules that will be used across multiple other projects. This allows for easy updating of this common code across multiple projects without making the same change multiple times.

### Planned Modules

- Core       - Common classes and features that can be used anywhere. These features don't quite fit into other modules. This will be required by other modules.
- Logging    - Provides logging functionality.
- Excel      - Using external library (most likely EPPlus) to provide functions to read/write Excel files.
- External   - Provides a common access fucntionality for external code housed in dlls (Dynamic Link Libraries). E.g win32.dll
- Hosting    - Provides fucntionality for dependency injection. Submodules from this will interface to different IoC libraries.
