# Autosuggest with Datalist

[See demo](https://htmlpreview.github.io/?https://raw.githubusercontent.com/davidlim/datalist_autosuggest/master/datalist.html)

Firefox 41 support for the datalist HTML5 tag is better than any other browser. If you use an option tag with a value, text, and closing option tag, Firefox will do partial search on the value and text. The ideal user experience.

Chrome 45 will only autosuggest from the beginning of the value. The dropdown list will show the value and text, but you only get autosuggest from the value.

Internet Explorer 11 will autosuggest on the text, matching from the beginning.

My goal is to add javascript to emulate a dropdown menu of matches, both values and option text, for a user to pick from. The match should be anywhere in the value or text rather than having to begin with the search phrase.
