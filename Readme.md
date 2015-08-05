ProcessQuickToggle
==================

Quickly toggle your checkboxes with extra action buttons via AJAX.

The module adds options into InputfieldCheckbox so you can toggle the checkbox
fields in the extra action buttons intruduced in [ProcessWire 2.6.5][pw-2-6-5]
via AJAX.

## Requirements
This module works only for ProcessWire versions later than 2.6.5.

## How to Install
1. Copy all the files in this directory to /site/modules/Babel/ 

2. In your admin, go to Modules > Refresh for new modules. 

3. Click the "Install" button next to Babel.

## Usage
Go to any checkbox field you want to enable quick toggle feature.
_Setup > Fields > my_checkbox_field_
There in the `Input` tab you will see a field _Enable Quick Toggle_ field. 
After you check it you will see the fields that you need to fill. Then save 
the field. Now there should be an extra button for every page that has this 
field in the Pages tree.

> _Note:_ You can also enable quick toggle for particular template contexts too.

[pw-2-6-5]: http://processwire.com/blog/posts/extra-action-in-your-page-list-processwire-core-updates-2.6.5/