---
views:
    kursrepo:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa
---

This Is A Testing Page For Markdown And Functions In The Framework
======

Testing Some Stuff With Lists
------------------------------

* Primary Item
* Primary Item
    * Sub Item?

Testing Tables
---------------

| Col 1 | Col 2 | Col 3 |
|-------|-------|-------|
| Testing | Nested List | <ul><li>Primary Item <ul><li>Secondary item</li></ul></li></ul> |


|Test   |  Test |          List                 |  Test |  Test |
|:---|:---|:---------------------------:|:---|:---|
| Test  | Test  | <ul><li>Primary</li><ul> | Test  | Test  |
| Test  | Test  |                           |  Test |  Test |
