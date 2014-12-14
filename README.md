Magento Snippets for Sublime Text
=================================

Snippets for daily work with Magento in Sublime Text (www.sublimetext.com/).

See also the blogpost on www.magegyver.de:
* http://www.magegyver.de/mageclass-sublime-text-snippet-fuer-magento-klassen/ (German)

## Magento Class (`mageclass`)

Generates an empty PHP class for current namespace and module, extending `Mage_Core_Block_Template` by default.

### How To

* create the new file in the location where you need it, for example `/app/code/local/MageGyver/SublimeSnippets/Block/Demo.php` (don't forget to save it)
* type `mageclass` and hit `tab`
* code for your new class will be created with vendor and module name the file belongs to
* this also works for files in deeper folder structures, for example `/app/code/local/MageGyver/SublimeSnippets/Block/Catalog/Product/View.php`

![snippet mageclass](i/snippet-mageclass.png "Snippet mageclass in Sublime Text")

## Magento Class Helper (`mageclass,helper`)

Generates an empty PHP helper class for current namespace and module, extending `Mage_Core_Helper_Abstract` by default.

### How To

* create the new file in the location where you need it, for example `/app/code/local/MageGyver/SublimeSnippets/Helper/Demo.php` (don't forget to save it)
* type `mageclass,helper` and hit `tab`
* code for your new class will be created with vendor and module name the file belongs to

![snippet mageclass](i/snippet-mageclass-helper.png "Snippet mageclass,helper in Sublime Text")
