FieldtypeMarkup
===============

ProcessWire Fieldtype which outputs markup as an Inputfield in the page editor.

Fieldtype renders runtime markup. Define output in field settings. Overwrite via template if needed. Include Page related values via {stringTags}. Textformatters applicable. Useful for concatenation of properties and field values, wrapped in any markup. The **output is modifiable** via hook with full ProcessWire Api accessible. Another hookable function: **hookProcessInput()** allows to modify whatever triggered by page save.