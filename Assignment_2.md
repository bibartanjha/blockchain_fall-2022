# Assignment 02 - Bitcoin Script

Name    : Bibartan Jha
Email   : jha.b1bartan@utexas.edu
Discord : bibberoni

## Program Inputs
```python
<"hi my name is bib">
<20>
<30>
<10>
<1>
<1>
```

## Program Script

The script goes through the following operations:

```python
OP_AND
OP_ADD
OP_SUB
OP_SUB
OP_NOT
<0>
OP_EQUAL
OP_IF 
<"hi my name is bib"> 
OP_ENDIF
OP_EQUAL
```

## Output
```python
himynameisbib 20 30 10 1
himynameisbib 20 30 11
himynameisbib 20 19
himynameisbib 1
himynameisbib 0
himynameisbib 0 0
himynameisbib 1
himynameisbib
himynameisbib himynameisbib
himynameisbib himynameisbib
1
```

## Result

The `OP_EQUAL` result should evaluate to true.

## Resources

**Script Wiz IDE**  
https://ide.scriptwiz.app
