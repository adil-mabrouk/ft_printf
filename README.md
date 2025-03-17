# **ft_printf – 42 Network Project**  

## **📖 About the Project**  
`ft_printf` is a custom implementation of the standard `printf` function in C. This project, part of the **42 School curriculum**, aims to deepen understanding of variadic functions, formatted output, and low-level string manipulation.

## **📌 Features**  
✔️ Handles standard format specifiers:  
   - `%c` → Character  
   - `%s` → String  
   - `%p` → Pointer address  
   - `%d` / `%i` → Decimal (integer)  
   - `%u` → Unsigned integer  
   - `%x` / `%X` → Hexadecimal (lowercase/uppercase)  
   - `%%` → Percent sign  

✔️ Supports variadic arguments using `va_list`  
✔️ Mimics the behavior of the real `printf` function  
✔️ Returns the number of characters printed  

## **📂 Project Structure**  
- `ft_printf.c` → Main function handling format parsing  
- `ft_printf.h` → Header file containing function prototypes  
- `ft_printadrs.c` → Function for handling pointer addresses (`%p`)  
- `ft_printchar.c` → Function for printing characters (`%c`)  
- `ft_printhex.c` → Function for printing hexadecimal numbers (`%x`, `%X`)  
- `ft_printnbr.c` → Function for printing integers (`%d`, `%i`)  
- `ft_printstr.c` → Function for printing strings (`%s`)  
- `ft_printuns.c` → Function for printing unsigned integers (`%u`)  

## **🛠️ Installation**  

### **🔹 Cloning the Repository**  
```sh
git clone https://github.com/adil-mabrouk/printf.git
cd ft_printf
make