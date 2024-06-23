# Bike Club - Access field storage

## Overview

Installs field_storage for the "Page access" node field, which is an entity reference type that uses the page access taxonomy to optionally limit page access to members, ride leaders, or administrators. Users must login to view content that has limited access.

### Where is page access used?
The page access field:
- Is included on Basic page, Event, and Webform node.
- Is not included on Announcement, Banner, FAQs, and Location.

## Contributed Modules Installed by the Recipe

Module 				  | Description
----------------------|------------
Taxonomy Access Control Lite | Governs access to nodes based on the taxonomy terms applied to the nodes. 


## Default Content

**Taxonomies**

Vocabulary	| Terms
------------|----------------------------------  
page_access | Admin, Members, Ride leaders

