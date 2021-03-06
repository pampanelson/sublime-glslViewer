# GLSL Viewer plugin for Sublime Text

![](http://patriciogonzalezvivo.com/images/glslViewer.gif)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4BQMKQJDQ9XH6)

Sublime Text plugin for live-coding GLSL Shaders using glslViewer ( MACOS X and Linux only).

## Installation
1. Install [glslViewer](https://github.com/patriciogonzalezvivo/glslViewer). By default it will be installed on ```/usr/local/bin``` if that's not the case edit it the ```glslViewer.sublime-settings``` file once you finish this steps.

2. You can choose to install the plugin it self with [Package Control](https://packagecontrol.io/) or by cloning [this repository](https://github.com/patriciogonzalezvivo/sublime-glslViewer) on you ```Packages``` Folder. For example:

```bash
cd ~/Library/Application Support/Sublime Text 2/Packages/
git clone https://github.com/patriciogonzalezvivo/sublime-glslViewer.git
```

## Usage

Every time you open a ```.frag``` or ```.fs``` file it will render it through ```glslViewer``` which will reload the shader every time you save it.

If the shader contain any ```uniform sampler2D```, a input label will apear down your Sublime Windows where you can enter the absolute or relative path to the image you want to load.

Also if you have a ```.vert``` file and/or 3D model (```.ply``` or ```.obj```) with the same name it will open them automatically. 

![](http://patriciogonzalezvivo.com/images/glslViewer-3D.gif)

## Extra commands

This plugin adds a GLSL *Build System* to re lunch `glslViewer` by pressing `Ctr`+`b` and also adds a command to *"create a new fragment shader template for glslViewer"* you can use to start working on a new shader.

## Suggestions

This plugin plays really well with this two other plugins:

* [Open​GL Shading Language (GLSL)](https://github.com/euler0/sublime-glsl)

* [Auto-save](https://packagecontrol.io/packages/auto-save)

## License

[MIT License](https://raw.githubusercontent.com/patriciogonzalezvivo/sublime-glslViewer/master/LICENSE)

## Author

glslViewer and this plugin was created and maintained by [Patricio Gonzalez Vivo](http://https://twitter.com/patriciogv): [github](https://github.com/patriciogonzalezvivo) | [twitter](http://https://twitter.com/patriciogv) | [website](http://patricio.io)
