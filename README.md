# Angulify
Angular by design neither works on server side nor supports server-side rendered output, thus Angular templates (Not rendered HTML) must be used to enable Angular for the view.

For example, using ng-repeat to show a list of items takes place on the client-side after the page is loaded which leads to some delay before the user can see the final rendered view/HTML. In some scenarios when the list of items can be rendered on the server-side and then on the client-side that server-rendered HTML can be attached to Angular. This is teh core concept behind Angulify.

Angulify is an attempt to work around this issue.

# NOTE
Angulify is in very early phase. I am still doing the research for how this can be done and designed properly.

Please share your thoughts :)
