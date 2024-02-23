# Views Tree

Provides a tree-based style plugin for Views.

It is based off of the list style. Although it generates a nested view, there is
still only a single query run for the view making it quite performant.

## Usage

1. Create a new view using the Fields row style. Populate it with the
   appropriate fields you want.
2. Select the Tree (Adjacency model) style plugin.
3. Select the linking fields in the style configuration panel. Generally, you
   will want to link from a nodereference field to the nid on the same node
   type. That is, the nodereference field is used as a pointer to the "parent"
   node.
4. Save and enjoy.

## Compatibility

This module has been tested and used with the following relationship-oriented modules:

- Taxonomy (in core) - parent/child relationships
- Entity reference (in core) - references between any entities
- References - node and user references
- Organic Groups

## Install

Install this module using the official Backdrop CMS instructions at
<https://backdropcms.org/guide/modules>.

## License

This project is GPL v2 software. See the LICENSE.txt file in this
directory for complete text.

## Current Maintainers

- Seeking new maintainers

## Credit

Ported from Drupal 7 by [Martin Jones](https://github.com/nattywebdev) and
[Herb v/d Dool](https://github.com/herbdool).

- <https://www.drupal.org/u/geerlingguy>
- <https://www.drupal.org/u/crell>
- <https://www.drupal.org/u/gauravkapoor>
- <https://www.drupal.org/u/dawehner>
- <https://www.drupal.org/u/jhedstrom>
