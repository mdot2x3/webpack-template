# webpack-template
Webpack template files with configuration and node modules prepared.

This template is set up to run webpack via scripts located in package.json.

To run webpack:
Enter 'npm run + script name' ('build', 'dev', 'deploy') -- example 'npm run dev'

'npm run build' is equivalent to running 'npx webpack',
'npm run dev' is equivalent to running 'npx webpack serve', and
'npm run deploy' runs 'git subtree push --prefix dist origin gh-pages' which is the final step in the webpack deployment process.