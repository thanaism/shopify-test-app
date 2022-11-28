run:
	yarn build
	find dist/assets -name 'index.*.js' | xargs -J% cp % ../test-app-oyster/extensions/test-theme-ext-oyster/assets/app.js
	find dist/assets -name 'index.*.css' | xargs -J% cp % ../test-app-oyster/extensions/test-theme-ext-oyster/assets/app.css