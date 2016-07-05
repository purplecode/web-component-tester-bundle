# web-component-tester-bundle

Bundled version of web-component-tester with all of it's dependencies.

# To update
	
	rm -rf node_modules
	npm install --production
	rm node_modules/selenium-standalone/.npmignore
	npm run list-dependencies
	# update package.json
	npm version patch
	git commit -m "update"
	npm publish

# Usage

	npm install web-component-tester-bundle --ignore-scripts