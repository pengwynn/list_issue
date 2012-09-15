
## the following list demonstrates the &lt;ul>&lt;li>&lt;a> rendering issue:

* [list item 1](#link)
    * [list sub item 1.1](#link)
    * [list sub item 1.2](#link)
    * [list sub item 1.3](#link)
* [list item 2](#link)
    * [list sub item 2.2](#link)
    * [list sub item 2.3](#link)
    * [list sub item 2.4](#link)


## screenshot of it:

![screenshot](https://github.com/ypocat/list_issue/blob/master/screenshot.png)

## how should it look

When links are not used, the list is rendered correctly, without the extra bottom margin on the top-level elements:

* list item 1
    * list sub item 1.1
    * list sub item 1.2
    * list sub item 1.3
* list item 2
    * list sub item 2.2
    * list sub item 2.3
    * list sub item 2.4
