.. every .rst file should include Includes.txt
.. use correct path!

.. include:: Includes.txt

.. Every manual should have a start label for cross-referencing to
.. start page. Do not remove this!

.. _start:

=============================================================
gridtocontainer
=============================================================

:Version:
   10.4.4

:Language:
   en

:Authors:
   Stefan Bublies

:Email:
   project@sbublies.de

:License:
   This extension documentation is published under the
   `CC BY-NC-SA 4.0 <https://creativecommons.org/licenses/by-nc-sa/4.0/>`__ (Creative Commons)
   license

Migrate EXT:gridelements to EXT:container

*****
Installation
*****

- Install via Ext-Manager or via Composer
- Add static template on root
- Select the grid migration module (you can see the modul as system maintainer)

.. image:: Resources/Public/Images/migrate_modul.jpg
  :width: 200
  :alt: Migrate Module

What grid elements do i have on my site?
--------

Click on "click here" in the important notice box in the first step. After that the extension analyzes your page and also gives you first instructions.

.. image:: Resources/Public/Images/whatforgridelements.jpg
  :width: 200
  :alt: Analyse the website


Migrate grid elements from gridelements layout key
--------

Click on "Migration form gridelements layout key" in the dropdown to migrate all elements on the web page using layout key.

.. image:: Resources/Public/Images/migrateall.jpg
  :width: 200
  :alt: Migrate all from layout key

TYPO3 and others
--------

**TYPO3**

The content of this document is related to TYPO3 CMS,
a GNU/GPL CMS/Framework available from `typo3.org <https://typo3.org/>`_ .

**Community Documentation**

This documentation is community documentation for the TYPO3 extension {extension.name}

It is maintained as part of this third party extension.

If you find an error or something is missing, please:
`Report a Problem <https://github.com/TYPO3-Documentation/TYPO3CMS-Example-ExtensionManual/issues/new>`__

**Extension Manual**

This documentation is for the TYPO3 extension <gridtocontainer>.

**For Contributors**

You are welcome to help improve this guide.
Just click on "Edit me on GitHub" on the top right to submit your change request.

.. toctree::
   :maxdepth: 3

   Introduction/Index
   Editor/Index
   Installation/Index
   Configuration/Index
   Developer/Index
   KnownProblems/Index
   Changelog/Index
   Sitemap
