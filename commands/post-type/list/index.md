---
layout: default
title: 'wp post-type list'
display_global_parameters: true
---

`wp post-type list` - List post types.

<hr />

### OPTIONS

[\--&lt;field&gt;=&lt;value&gt;]
: Filter by one or more fields (see get_post_types() first parameter for a list of available fields).

[\--field=&lt;field&gt;]
: Prints the value of a single field for each post type.

[\--fields=&lt;fields&gt;]
: Limit the output to specific post type fields.

[\--format=&lt;format&gt;]
: Accepted values: table, csv, json, count. Default: table

### AVAILABLE FIELDS

These fields will be displayed by default for each term:

* name
* label
* description
* hierarchical
* public
* capability_type

There are no optionally available fields.

### EXAMPLES

    wp post-type list --format=csv

    wp post-type list --object-type=post --fields=name,public



