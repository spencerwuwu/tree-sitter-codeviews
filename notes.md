## C-Sharp to CPP
- Cool and right function parameters
- Direct subsitution
    - parameter -> parameter_declaration
    - block -> compound_statement
    - local_declaration -> declaration
    - inovcation_expression -> call_expression
    - member_access_expression -> field_expression
    - element_access_expression -> subscript_expression

```
local_function_statement -> []
---
function_definition
```

```
variable_declaration -> []
---
declaration
```

```
if_statement -> [exp, block] 
--
if_statement -> [condition_clause -> exp, compound_statement]
```

```
assignment_expression -> [exp, assigment_operator, exp]
--
assignment_expression -> [exp, exp]
```

```
switch_statement -> 
[ exp, 
  switch_body -> [switch_section -> [
                    case_switch_label,
                    exp...
                    ]
                ]
]
---
switch_statement -> 
[ condition_clause, 
  compound_statement -> [ case_statement -> [
                                exp, 
                                exp...
                            ]
                        ]
]
```
