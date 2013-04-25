Variable Block
--------------

Overview
========
This module provides a Drupal block. The block is only displayed if the URL
param `varblock` is set. The value of `varblock` corresponds to a
`Variable Set` which are configured on the block configuration page.

Configuration
=============
Enter one or more `Variable Sets` on the block configuration page
(`/admin/build/block/configure/varblock/varblock`). Clicking on the
`Add Variable Set` button will add the set to the list and automatically
generate a `Variable Set ID` (a unique 10-characted string) used to identify
this set of variables.

Pages with the URL parameter `varblock` present and set to a Variable Set ID
will display the block with the variables defined by the associated
`Variable Set`.

You must assign this block to a valid region for it to appear.
