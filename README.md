## Visual Studio Code Extension
This is a simple extension for Visual Studio Code that adds some basic syntax highlighting and snippet support to the editor.

### Making the Extension
Run the following:

    mkdir -p dist/
	cd src/
    vsce package --allow-missing-repository
	mv helasuno*.vsix ../dist/

If vsce isn't installed, get it:

    npm install -g @vscode/vsce

### Installing the Extension
In Visual Studio Code:

1. Open the Command Palette
2. Select "Extensions: Install from VSIX..."
3. Select the VSIX file in dist/
4. Profit


## Licence
The code and materials are provided under the MIT licence.

### MIT Licence
Copyright 2024-2025 Bryan Smith.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.