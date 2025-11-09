# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV DPTR, #4500H
MOV A, @DPTR
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```

## OUTPUT
![WhatsApp Image 2025-11-09 at 19 55 32_c8353b8a](https://github.com/user-attachments/assets/d1b36fd5-564d-48ff-a2fc-6fc746a377a2)




## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV DPTR, #4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A, @DPTR
MUL AB
INC DPTR
MOVX @DPTR, A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```


## OUTPUT
![WhatsApp Image 2025-11-09 at 19 55 39_7da14bd1](https://github.com/user-attachments/assets/b0cb0587-1b9f-42b2-a9fa-81797b8cbe58)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
