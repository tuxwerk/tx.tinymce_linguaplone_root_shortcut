tx.tinymce_linguaplone_root_shortcut
====================================

Navigate with tinymce to plone site root for language neutral content

Works for Plone 4.3+ (Should also work on Plone 5)

INSTALL:

If you are using buildout you can do this:

* Add ``tx.tinymce_linguaplone_root_shortcut`` to the list of eggs to install, e.g.:

    [buildout]
    ...
    eggs =
        ...
        tx.tinymce_linguaplone_root_shortcut
       
* Re-run buildout, e.g. with:

    $ ./bin/buildout -N
        
Navigate to TinyMCE ControlPanel (portal_tinymce/@@tinymce-controlpanel) and add "Root" to Link and Image Shortcuts.

Origin reference: http://docs.plone.org/5/en/develop/plone/forms/wysiwyg.html#tinymce-shortcuts
