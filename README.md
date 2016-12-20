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
				jason-schema-faker and json-server to mock api, more info on
										http://json-schema-faker.js.org/
										http://json-schema.org/
										https://github.com/typicode/json-server
				trackjs for error logging, it has a free trial for 30 days
										i didn't install it. It's in the production build module,
										chapter: demo:Error logging
				heroku for production deployment for the api (or backend)
							we created a new project called js-dev-env-demo-api
								where we use heroku
				surge for production deployment for the ui
					we added a script to package.json called deploy, so npm run deploy
					will do the trick, it should be called after npm run build
					the deployment part is all in the last module
					
					
webpack creates a file which we called bundle.js, and import it in index.html
				the file does not exist physically, but it is in memory 
				
to see the original code you write, in the browser, 
	use source maps aka(the debugger) in your code, to set breakpoints				

if you work in react you can use eslint-plugin-react


you can check the CI server at travis-ci.org, ci.appveyor.com
login with github account => activate the repo you want => push a commit that contains the .travis.yml file => then it does the build
the CI will show if the commit is correct or not, by running test on it
travis tests if your project works in a linux environment

login with github account => activate the repo you want => push a commit that contains the appveyor.yml file => then it does the build
the CI will show if the commit is correct or not, by running test on it
appveyor tests if your project works in a windows environment



you will receive an email after each build, with the result of the build


the production configuration is in webpack.config.prod.js, and the files are in
the dist folder


list of react starter-kits:
-- http://andrewhfarmer.com/starter-project/
