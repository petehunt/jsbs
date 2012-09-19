JSBS is a client-side skeleton project and utility scripts for using CommonJS modules. It includes JQuery as well, but you can remove it by replacing require-jquery.js with regular require.js.

Basic usage:

Clone this repo for your new project. Start dropping your js source (commonjs modules) into the src/ directory. The module named "main" is automatically laoded. Feel free to replace the html file under build/ if you want and add whatever CSS or other resources you want. Run bin/build.sh to compile the JS correctly (requires Node). You can then either drop the static resources in the build/ directory whereever you want or run bin/serve.sh to spin up a simple web server.
