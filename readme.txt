- Run ```npm install -g npm@10.9.0``` to update!

- I've used Vite, because it is faster that create-react-app, and it splits the app into 2 categories, dependencies and source code.
- Dependencies: These are things that do not change often during the development process. These bundles use ```esbuildis``` written in Go and is very fast than javascript.
- Source Code: It is called only on demand whenever required, and it is incredibly fast.

- SWC is a code transpiler much like Babel.


-- Hosting - hostinger 