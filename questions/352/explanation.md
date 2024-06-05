The `typedef` specifier provides a way for declaring a type alias. However, it does not introduce a new type-id. §[dcl.typedef]¶1 in the standard:

> A name declared with the `typedef` specifier becomes a typedef-name. Within the scope of its declaration, a typedef-name is syntactically equivalent to a keyword and names the type associated with the identifier in the way described in Clause [dcl.decl]. A typedef-name is thus a synonym for another type. A typedef-name does not introduce a new type the way a class declaration ([class.name]) or enum declaration does.