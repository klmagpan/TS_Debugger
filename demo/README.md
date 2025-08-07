# Shopping Cart Debugging Example
## Made with React + TypeScript + Vite# TS_Debugger

## Demo SetUp
### Install necessary packages
- npm install typescript –save-dev
- npm install ts-node –save-dev
- npm install react react-dom
- npm install --save-dev typescript @types/react @types/react-dom
- npm install --save-dev @vitejs/plugin-react

- Create tsconfig.json file: npx tsc –init (if needed)
- In package.json: build script: {“build: “tsc”}

### Run
- npm run build
- npx serve dist (shows html result and creates a server) 
	- Equivalent is to cd to dist path, then do “npx serve”
- OR npm run dev