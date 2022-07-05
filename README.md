# Wordpress theme Tailwind - React ready

This repo contains a wordpress example theme. The theme uses the official @wordpress/scripts package to power the JS(X) and SCSS bundling.


After placing the folder in your WordPress themes, you then:

1. Point your terminal towards the new example folder.
2. Run npm install
3. Run npm run start and the package will now be watching for any saved changes to your JS or SCSS files.
Alternatively, you can run npm run preview and that will both start the watch task and start a proxy server running on localhost:3000 that will automatically refresh the browser anytime you save a change. In order for this feature to work you will need to change the domain in package.json on line #8. In my file it mentions myexample.local but obviously you will have a different local dev domain that you want to proxy.

Enjoy!