# Luna Engine v0.6

This repository hosts the source code for Luna Engine v0.6, which is currently my personal game engine project for learning & research purposes.

This 0.6 version of Luna Engine is only a prototype version and I open sources it in case that it might be useful for you. I strongly recommend that you should **NOT** use the 0.6 version of the engine in any serious project and in any real production environment.

## Building

Building prerequisites:

* Windows 10
* Visual Studio 2017+ with C++17 Support

Building Steps:

1. Clone the project.
2. Add `/Tools/` to `PATH`.
3. Run `gen_vs2017.bat` or `gen_vs2019.bat`
4. To build `Studio` project, you need to configure compile options for shader files manually (`ps_5_0` for shaders with `Pixel` suffix, `cs_5_0` for shaders with `CS` suffix). You may also need to copy the compiled shader files to `/Solution/` directory manually.

## License

MIT

## Contact

Mail: jxmaster@yeah.net

Twitter: @jxmaster