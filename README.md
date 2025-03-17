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
- `ft_printf_utils.c` → Helper functions for printing  
- `ft_print_numbers.c` → Functions for integer and hexadecimal conversions  
- `ft_print_chars.c` → Functions for characters and strings  
- `ft_print_address.c` → Function for pointer addresses  
- `libft/` → Helper functions from Libft (if used)  

## **🛠️ Installation & Usage**  

### **🔹 Cloning the Repository**  
```sh
git clone https://github.com/yourusername/ft_printf.git
cd ft_printf
make