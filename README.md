# Comment Alter

This module makes it possible to alter (change values of) fields on a node when leaving a comment.

This can be used to create a tracker similar to [Case Tracker](http://drupal.org/project/casetracker) or other [support or project management modules](http://groups.drupal.org/node/17948).

However, unlike those modules which have the available fields hard-coded, this module allows you to edit any field on a content type and check "Enable altering this field from comments"!

By using only standard Backdrop components like Fields and Views, you can construct any variety of full-featured bug trackers, customer support, sales or project management tools.

This is most similar to [Comment Driven](http://drupal.org/project/comment_driven) (for Drupal 6), except (1) it's available for Drupal 7 and (2) it's design is much simpler! Rather than inventing lots of new code and APIs, **Comment Alter** strives to integrate with other modules (like core's Node module to store the changes as new revisions and Diff module for displaying the changes made in a particular comment).


## Requirements

Besides core modules like Node and Comment, the only dependency is [Diff](https://github.com/backdrop-contrib/diff) module.

## Installation

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Visit the configuration page under _Structure > Content types > content_type >
  Configure_ (admin/structure/types/manage/content_type/configure) _> Comment settings_ and configure settings under the _Comment alter settings_ as you like.

- Then click on the _Manage fields_ tabs and configure any field (admin/structure/types/manage/content_type/fields/field_name) and check on the _Enable altering this field from comments_ checkbox.


## FAQ

Q: I want to implement a custom feature for the module/extend the module's functionality.\
A: Please contact [AltaGrade](https://www.altagrade.com) for customizations of
this module as well as Backdrop consulting, installation, development, and customizations.


## Issues

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/comment_alter/issues.

## Current Maintainers

- [Alan Mels](https://github.com/alanmels).
- Seeking additional maintainers.

## Credits

- Ported to Backdrop CMS by [Alan Mels](https://github.com/alanmels).
- Originally written for Drupal by [CSÉCSY László](https://github.com/boobaa).
- Sponsored by [AltaGrade](https://www.altagrade.com)

## License

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.

