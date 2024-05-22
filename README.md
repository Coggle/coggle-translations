# Coggle Translations
Help translate [Coggle](https://coggle.it) into your native language!

This repository holds translations of Coggle's interface into different
languages, what's here should match what's live on the site – so if you see a
mistake, submit a [pull
request](https://help.github.com/articles/using-pull-requests/) to fix it!

We now use [fluent](https://projectfluent.org) for our translations, so for a
guide to the syntax of our .ftl files you can read the [fluent
tutorial](https://projectfluent.org/fluent/guide/).

The legacy l20n translations are no longer used, but they can be found in the
legacy folder for reference.

## Found a problem?
If you've found a problem with an existing translation, please open a [new
issue](https://github.com/Coggle/coggle-translations/issues) to report it!

## Contributing Improvements
We accept pull-requests to the `main` branch, which we'll then test and merge.

To make a pull-request you'll first have to fork this repository, make and
commit your changes back to github. If you're new to Github here's a [great
guide](https://help.github.com/articles/using-pull-requests/) to the process.

## Creating a new Language
To create a new language, in your own fork of the repository:

 1. Create a new file, named after the [language
    code](http://www.lingoes.net/en/translator/langcode.htm) for
    the language you want to translate, for example the British-English
    translation is in a file called `en-GB.ftl`.

 2. Start adding translations to your file! The en.ftl file contains the
    generic english translations, and is a good template.
 
 4. Then submit a pull request for us to add the language. You can do this as
    soon as your file has any translations (it doesn't have to be complete!).
    When you submit a pull request you are authorising us to use your
    contributions on Coggle.

 5. As you make and commit new changes, they will appear on the existing pull
    request (until that is merged), after that you should open a new [pull
    requests](https://help.github.com/articles/using-pull-requests/) to update
    the main Coggle/translations repository with your changes. You may have to
    [sync your fork](https://help.github.com/articles/syncing-a-fork/) to pull
    in other people's changes, too.

 6. For significant contributions we'll happily upgrade your Coggle account for
    free, just drop us an email from the address you use to sign in ;)

## Translating Text
If there's a specific bit of text in Coggle that you want to translate, first
find that in the `en.ftl` translations, then copy and paste it into your own
translation file.

For example, to translate the "Unleash Your Creativity" section from the
homepage, you would copy these items:

```
index-unleash = Unleash your creativity
index-blurb = Produce beautiful notes quickly and easily. Share them with friends and colleagues to work on your ideas together.
index-viewgallery = Or take a look at the <a data-l10n-name='gallery'>Coggle Gallery</a> for inspiration.
```

Each html element generally has a separate translation. Where items like `<a>`
link anchor elements occur in a translation, they must have a data-l10n-name
that matches a name in the html. In general, new html should not be added to
translated text (only very basic text elements like `<b>` and `<br>` are
supported)
 
## Questions? Feedback?

If you want to contribute but have any questions / don't know how to get
started, just drop us an email at
[translate@coggle.it](mailto:translate@coggle.it), and we'll do our best to get
you started!

