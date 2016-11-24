#t-table

## List of properties

1. Data `array` 
1. Searchable `boolean`
  1. Searchable Column Details `object`
1. Sortable `boolean`
  1. Sortable Column Details `object`
1. Different Header Row `boolean`
1. Pagination `boolean`. `if disabled then infinite scroll is enabled.`
  1. Rows Per Page `Number`
1. Filterable `string` `No, Auto Apply, Manual`
  1. Filter Details `object`
1. Multi Select Operations `boolean`
  1. Multi Select Details `object`
1. Reorderable `string` `No, Row, Column, Both` `row reorder will kill sort, not work unless data write acccess is available, has other issues  about how will the component change its own code`
1. Details Pane `boolean`
  1. Template `object`
1. Hoverable `boolean`
1. Banded Rows `boolean`
1. Export Options `boolean`
1. Editable `string` `Cell, Via Form, Via Redirect` `if Cell or Via Form is chosen then a pencil icon appears on the right of every row`
1. Add Items `string` `No, Via Form, Via Redirect`

Note - for add and edit, if any one column contains objects, then only `Via Redirect` option will work in that case for that column.


## List of Subcomponents and their properties
+
+- t-column
+  -editable
+  -ordering
+  -searchable
+  -text-alignment (right, left, center)
+  
+- t-table
+  -sortable
+  -searchable
+  -has-header
+  -filters-applicable
+  -pagination
+  -banded rows
+  -hoverable rows
+  -reorderable rows
+  -row selection

