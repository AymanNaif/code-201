# Object-Oriented Programming, HTML Tables

# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

# Tables
## What's a Table?
A table represents information in a grid format.
Examples of tables include financial reports, 

## Basic Table Structure

* < table >
The < table > element is used
to create a table. The contents
of the table are written out row
by row.

* < tr >
You indicate the start of each
row using the opening < tr > tag.
(The tr stands for table row.)
It is followed by one or more
< td > elements (one for each cell
in that row).
At the end of the row you use a
closing < /tr > tag.

* < td >
Each cell of a table is
represented using a < td >
element. (The td stands for
table data.)
At the end of each cell you use a
closing < /td > tag.


## Table Headings
The < th > element is used just
like the < td > element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)
Even if a cell has no content,
you should still use a < td > or
< th > element to represent
the presence of an empty cell
otherwise the table will not
render correctly.


## Spanning ColumnS
Sometimes you may need the
entries in a table to stretch
across more than one column.
The colspan attribute can be
used on a < th > or < td > element
and indicates how many columns
that cell should run across.


## Spanning Rows
You may also need entries in
a table to stretch down across
more than one row.
The rowspan attribute can be
used on a < th > or < td > element
to indicate how many rows a cell
should span down the table.


## Long Tables
here are three elements that
help distinguish between the
main content of the table and
the first and last rows (which can
contain different content).
These elements help people
who use screen readers and also
allow you to style these sections
in a different manner than the
rest of the table 

1. < thead > :
The headings of the table should
sit inside the < thead > element.
2. < tbody > :
The body should sit inside the
< tbody > element.
3. < tfoot > :
The footer belongs inside the
< tfoot > element.

## Width & Spacing
There are some outdated
attributes which you should not
use on new websites. You may,
however, come across some
of them when looking at older
code, so I will mention them
here. All of these attributes have
been replaced by the use of CSS.
The width attribute was used
on the opening < table > tag to
indicate how wide that table
should be and on some opening
< th > and < td > tags to specify
the width of individual cells.
The value of this attribute is
the width of the table or cell in
pixels.

## Border & Background
The border attribute was used
on both the < table > and < td >
elements to indicate the width of
the border in pixels.
The bgcolor attribute was used
to indicate background colors
of either the entire table or
individual table cells. The value
is usually a hex code


