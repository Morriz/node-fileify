Small adaptation of substack/node-fileify to get access to the found files from within node context.

Now exports 2 items:

register: function (function(target, dir, optsOrEx) {…}
(same signature and output as the main exported function from substack)

files: {…} - each time the 'register' function is called, this hash is enriched with the files found
