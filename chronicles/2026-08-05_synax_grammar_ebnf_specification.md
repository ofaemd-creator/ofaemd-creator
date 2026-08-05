# SYNAX (.sx) Language Grammar Specification

**Author:** Dr. Ömer Faruk Aydın  
**Date:** August 5, 2026  
**Domain:** Programming Language Design  

## Grammar Overview
SYNAX syntax emphasizes explicit typing, formal interval annotations, and hardware target qualifiers:
```ebnf
KernelDecl ::= 'kernel' Identifier '(' ParameterList? ')' ReturnType? WhereClause? Block ;
WhereClause ::= 'where' InvariantExpression (',' InvariantExpression)* ;
```
