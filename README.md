# Coggle Translations
Help translate [Coggle](https://coggle.it) into your native language!

This repository holds translations of Coggle's interface into different
languages, what's in the
[production](https://github.com/coggle/translations/tree/production) branch
should match what's live on the site – so if you see a mistake, submit a pull
request to fix it!

We use [l20n](http://l20n.org) for our translations, so for a guide to the
syntax of our l20n files you can read the [l20n
tutorial](http://l20n.org/learn/). We use some html in our translations, 

## Contributing Improvements

We accept pull-requests to the `master` branch, which we'll then test and merge
into the `production` branch (at which point they will automatically be
deployed to the live site).

To make a pull-request you'll first have to fork this repository, make and
commit your changes back to github. If you're new to Github here's a [great
guide](https://help.github.com/articles/using-pull-requests/) to the process.

## Creating a new Language

To create a new language, in your own fork of the repository:

 1. Create a new file, named after the [language
    code](https://msdn.microsoft.com/en-us/library/ms533052(v=vs.85).aspx) for
    the language you want to translate, for example the British-English
    translation is in a file called `en-GB.l20n`.

 2. Add your language to the locales list in the `manifest.json` file.

 3. Start adding translations to your file!
 
 4. Then submit a pull request for us to add the language. You can do this as
    soon as your file has any translations (it doesn't have to be complete!).
    Before your pull-request can be accepted you'll have to agree to our
    [contributor
    agreement](https://www.clahub.com/agreements/Coggle/translations), which
    gives us the right to use your content on our site.

## Translating Text
If there's a specific bit of text in Coggle that you want to translate, first
find that in the en-GB or en-US translations (which we maintain), then copy and
paste it into your own translation file.

For example, to translate the "Unleash Your Creativity" section from the
homepage, you would copy this:

```
<index-description """
  <h1>Unleash your creativity</h1>
  <p>
     Produce beautiful notes, quickly and easily.
     Share them with friends and colleagues to enhance your ideas collaboratively.
     All for free!
  </p>
  <p>
     <a><span><b>Get started now! </b></span></a>
     <a><span>Or, read more.</span></a>
  </p>
""">
```

This is a fairly complex translation element, with bits of html mixed in - when
you translate you need to leave the same html elements in there, but you can
change any of the text.
 
## Questions? Feedback?

If you want to contribute but have any questions / don't know how to get
started, just drop us an email at
[translate@coggle.it](mailto:translate@coggle.it), and we'll do our best to get
you started!

