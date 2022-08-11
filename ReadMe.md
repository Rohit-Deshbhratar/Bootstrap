# Bootstrap Practice

This repository contains examples practiced to learn bootstrap5. Every folder will contain a topic in bootstrap and in that folder respective HTML file will show the implementation of that topic.

For example In "Container" folder, HTML file show you what types of containers are, how they look and spaces taken by HTML elements in respective container.

## 1.Container Folder

This folder contains file which implemented Bootstrap 5 containers in different ways for better understanding.

### container.html

This example shows demonstration of ".container" class from bootstrap 5, how it looks on web page.
This example also shows us how margin & padding works in bootstrap 5 and it's effect on element.

### container-fluid.html

This example shows demonstration of ".container-fluid" class from bootstrap 5, how it looks on web page.
This file also shows us how margin & padding works in bootstrap 5 and it's effect on element.

## 2.Grid Folder

This folder contains files which implemented bootstrap grid concept.

### grid-basics.html

This example shows how to use .cols-_-_ & .col and it's working. Also shows us that how much space a column takes.

### grid-classes.html

This example shows working of col-sm|md|lg and their breakpoints. We also learned that when col-sm|md|lg met their respective breakpoint columns turns into rows.

### grid-without-classes.html

In this example we have only used .col class, Which divides the grid for columns as per requirement. We learned that only on .col in a row occupy entire row, whereas for multiple .col in a row spaces are divides equally.
If .col used with sm|md|lg| it becomes responsive.
NOTE: .col will only maintain equal spacing deosn't matter what breakpoint is.

## Margin Utilities Folder

This folder contains examples based on ms-auto, me-auto, standalone classes,guters, horizontal gutters, vertical gutters.

### margin-utility.html

In this example we will see how to move column to the right. For that we have used ".ms-auto" &
".me-auto". The output of both example will look same but the difference is, in ms-auto margin is set to auto, whereas in me-auto margin is set to right.

### standalone-classes.html

In this we have not used traditional nesting inside .row class. Instead we have used wrapping of
.clearfix class. But still managed to achive responsive image in the example.

### gutter-horizontal.html

This example demonstrates how gutters are managed manually. In this example we have shown how gutters affect size of elements and how can we manage gutters and how they look when managed manually.

### gutter-vertical.html

This example demonstrates how vertical gutters managed manually in three steps. In thes step an environment is set to see how it changes when vertical gutters are applied manually.

### gutters-vertical-horizontal.hmtl

This example demonstrates how vertical & horizontal gutters are managed using single class.
