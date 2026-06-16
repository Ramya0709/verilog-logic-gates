# Verilog Implementation of Basic Logic Gates


## AND Gate
Outputs 1 only when all inputs are 1.
<table>
<tr>
<td>

### Truth Table

| A | B | Y = A · B |
|---|---|-----------|
| 0 | 0 |     0     |
| 0 | 1 |     0     |
| 1 | 0 |     0     |
| 1 | 1 |     1     |

</td>

<td>
  
### Symbol

<img src="https://github.com/user-attachments/assets/cfd0db04-54e8-47fd-9a3b-c2130df66634" width="250"/>

</td>
</tr>
</table>

## NAND Gate
Outputs 1 when at least one input is 0.
<table>
<tr>
<td>

### Truth Table

| A | B | Y = (A · B)'|
|---|---|-----------|
| 0 | 0 |     1     |
| 0 | 1 |     1     |
| 1 | 0 |     1     |
| 1 | 1 |     0     |

</td>

<td>
  
### Symbol

<img width="300" height="169" alt="image" src="https://github.com/user-attachments/assets/7e338e57-efb8-4aba-a681-7b2a069aca49" />


</td>
</tr>
</table>

## OR Gate
Outputs 1 when at least one input is 1.
<table>
<tr>
<td>

### Truth Table

| A | B | Y = A + B |
|---|---|-----------|
| 0 | 0 |     0     |
| 0 | 1 |     1     |
| 1 | 0 |     1     |
| 1 | 1 |     1     |

</td>

<td>
  
### Symbol

<img width="300" height="180" alt="image" src="https://github.com/user-attachments/assets/ed811b94-f397-488f-b3a5-e662af18c05c" />


</td>
</tr>
</table>

## NOR Gate
Outputs 1 only when all inputs are 0 (NOT of OR).
<table>
<tr>
<td>

### Truth Table

| A | B | Y = (A+B)' |
|---|---|-----------|
| 0 | 0 |     1     |
| 0 | 1 |     1     |
| 1 | 0 |     1     |
| 1 | 1 |     0     |

</td>

<td>
  
### Symbol

<img width="400" height="170" alt="image" src="https://github.com/user-attachments/assets/cc74d38e-85d4-4a1d-84b4-f0ac1c8e0cab" />


</td>
</tr>
</table>

## NOT Gate
Outputs the inverse (complement) of the input.
<table>
<tr>
<td>

### Truth Table

| A | Y = A' |
|---|-----------|
| 0 |      1     |
| 1 |     0     |

</td>

<td>
  
### Symbol

<img width="297" height="170" alt="image" src="https://github.com/user-attachments/assets/2aa1ef65-f7dd-4b89-abf3-6757597144f8" />



</td>
</tr>
</table>

## XOR Gate
Outputs 1 when inputs are different.
<table>
<tr>
<td>

### Truth Table

| A | B | Y = A'B + AB' |
|---|---|-----------|
| 0 | 0 |     0     |
| 0 | 1 |     1     |
| 1 | 0 |     1     |
| 1 | 1 |     0     |

</td>

<td>
  
### Symbol

<img width="322" height="130" alt="image" src="https://github.com/user-attachments/assets/5dc4216e-71a6-4ef4-bd3e-14fae2582a7f" />


</td>
</tr>
</table>

## XNOR Gate
Outputs 1 when inputs are the same.
<table>
<tr>
<td>

### Truth Table

| A | B | Y = AB + A'B' |
|---|---|-----------|
| 0 | 0 |     1    |
| 0 | 1 |     0     |
| 1 | 0 |     0     |
| 1 | 1 |     1     |

</td>

<td>
  
### Symbol

<img width="261" height="82" alt="image" src="https://github.com/user-attachments/assets/3718f9ee-0f69-4b4e-9166-84d67cf98fde" />

</td>
</tr>
</table>
