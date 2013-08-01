affiliates-translations
=======================

Translation template repository for the Affiliates plugins.

Use the .pot file to derive a translation .po file, for example use affiliates-x.y.z.pot to derive affiliates-de_DE.po for your the German language and Germany.

Use poedit or run

  msgfmt -o affiliates-de_DE.mo affiliates-de_DE.po

to create the .mo file, then add the .po and .mo files obtained at locations indicated below.

Note that for the Affiliats plugin, you only need to add one set of files, for Affiliates Pro you need to add two sets and for Affiliates Enterprise there are three sets of .po/.mo files to be added.

- Affiliates :

  affiliates/lib/core/languages

- Affiliates Pro :

  affiliates-pro/lib/core/languages
  affiliates-pro/lib/ext/languages

- Affiliates Enterprise :

  affiliates-enterprise/lib/core/languages
  affiliates-enterprise/lib/ext/languages
  affiliates-enterprise/lib/eext/languages
  
