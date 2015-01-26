# Angulify
Angular by design neither works on server side nor supports server-side rendered output, thus Angular templates (Not rendered HTML) must be used to enable Angular for the view.

For example, using ng-repeat to show a list of items takes place on the client-side after the page is loaded which leads to some delay before the user can see the final rendered view/HTML. 
The core concept behind Angulify is about some scenarios where the list of items can be rendered on the server-side, delivered to the browser as initial view and then on the client-side that server-rendered HTML can be attached to Angular.

Angulify is an attempt to work around this issue.

# NOTE
Angulify is in very early phase. I am still doing the research for how this can be done and designed properly.

Please share your thoughts :)

# Research Results in Points
- I found interesting project angularjs-server for NodeJS (https://github.com/saymedia/angularjs-server). However its focus on other aspects than What I want to fix here. Mainly Angulify would be a client-side library
- This article (https://sourcegraph.com/blog/switching-from-angularjs-to-server-side-html) shows why having ready initial view is crucial especially for content driven pages
