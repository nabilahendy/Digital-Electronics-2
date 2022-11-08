# Lab 6:  NABILA HENDY

### ASCII

1. Complete the table with selected ASCII codes.

   | **Char** | **Decimal** | **Hexadecimal** | **Binary** |
   | :-: | :-: | :-: | :-: |
   | `a` | 97 | 0x61 | `0b0110_0001` |
   | `b` | 98 | 0x62 | `0b0110_0010` |
   | `c` | 99 | 0x63 | `0b0110_0011` |
   | `0` | 48 | 0x30 | `0b0011_0000` |
   | `1` | 49 | 0x31 | `0b0011_0001` |
   | `2` | 50 | 0x32 | `0b0011_0010` |
   | `Esc` | 27 | 0x1B | `0b0001_1011` |
   | `Space` | 32 | 0x20 | `0b0010_0000` |
   | `Tab` | 9 | 9 | `0b0000_1001` |
   | `Backspace` | 8 | 8 | `0b0000_1000` |
   | `Enter` | 13 | 0x16  | `0b0000_1101` |

### UART communication

2. Draw timing diagram of the output from UART/USART when transmitting three character data `De2` in 4800 7O2 mode (7 data bits, odd parity, 2 stop bits, 4800&nbsp;Bd). The image can be drawn on a computer or by hand. Name all parts timing diagram.

 
![timediagram_lab6](https://user-images.githubusercontent.com/115028247/200660317-17a7d884-5b7d-422d-92b3-bb8ff701f840.png)

3. Draw a flowchart for function `uint8_t get_parity(uint8_t data, uint8_t type)` which calculates a parity bit of input 8-bit `data` according to parameter `type`. The image can be drawn on a computer or by hand. Use clear descriptions of individual algorithm steps.

   
![flowchart_lab6](https://user-images.githubusercontent.com/115028247/200660283-62ae0060-f6f2-44cd-bf32-891220b31534.png)




*Excersice 1: use online manual of UART library... :
uart_getc : get received byte from ringbuffer // UART_NO_DATA (RETURNS LOWER AND HIGHER BYTE) 
uart_putc: void uart_putc (unsigned char data) put byte to ringbuffer for transmitting via UART // data byte to be transmitted and returns nothing
uart_puts:  void uart_puts (const char *s) put string to ringbuffer for transmitting via UART and returns nothing *
