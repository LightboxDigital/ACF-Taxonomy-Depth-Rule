# ACF Taxonomy Depth Rule

Taxonomy depth rule for advanced custom fields, easily display field groups depending on the taxonomy terms depth.

You can choose different operators for your rule test (equals, not equals, greater than, less than) and due to my requirements this is also compatible with Shopp.

## How to Install

Installing is simple, copy the `acf-taxonomy-depth-rule.php` file into your theme's folder and then put the following line of code into your functions.php

`<?php
require_once(rtrim( dirname( __FILE__ ), '/' ) . '/locations/taxonomy-depth.php');
?>`