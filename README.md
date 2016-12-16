# javascript-starter-kit

npm start , will start the server
npm run share, will generate a public url where others can view my local work
for other commands check package.json

we use  express to create the server
				babel for transpiling
				webpack for bundling
				npm scripts for automation
				ESLint for linting
				mocha for testing, continuous integration (CI) with travis, and appveyor
				
webpack creates a file which we called bundle.js, and import it in index.html
				the file does not exist physically, but it is in memory
				
to see the original code you write, in the browser, 
	use source maps aka(the debugger) in your code, to set breakpoints				

if you work in react you can use eslint-plugin-react


you can check the CI server at travis-ci.org, ci.appveyor.com
login with github account => activate the repo you want => push a commit that contains the .travis.yml file
the CI will show if the commit is correct or not, by running test on it
travis tests if your project works in a linux environment

login with github account => activate the repo you want => push a commit that contains the appveyor.yml file
the CI will show if the commit is correct or not, by running test on it
appveyor tests if your project works in a windows environment
