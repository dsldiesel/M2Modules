## Synopsis

A most basic module for Magento 2.

## Technical feature

This component demonstrates the modularity of Magento 2.  The [module.xml](etc/module.xml) is read by the system and used to manage isolated modules of the system.  By enabling this module, you can see how the system becomes aware of a module and loads the features packaged within a module.

## Installation

This module is intended to be installed using composer.  After including this component and enabling it, you can verify it is installed by going the backend at:

STORES -> Configuration -> ADVANCED/Advanced ->  Disable Modules Output

Once there check that the module name shows up in the list to confirm that it was installed correctly.
