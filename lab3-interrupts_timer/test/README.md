# Lab 3: NABILA HENDY MNOUAR

### Overflow times

1. Complete table with overflow times.

   | **Module** | **Number of bits** | **1** | **8** | **32** | **64** | **128** | **256** | **1024** |
   | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
   | Timer/Counter0 | 8  | 16u | 128u | -- |1024u | -- |4096u | |
   | Timer/Counter1 | 16 |  2048u   |    4096u  | -- | | -- | | |
   | Timer/Counter2 | 8  |  16u   | 128u     | 512u   |1024u |4096u    | | |
   
   (using the formula ![timer_overflow](https://user-images.githubusercontent.com/115028247/196499008-f2e27c10-c0d2-4f24-8f1e-98d7aebf3166.png))


### Interrupts

2. In `timer.h` header file, define macros also for Timer/Counter2. Listing of part of the header file with settings for Timer/Counter2. Always use syntax highlighting, meaningful comments, and follow C guidelines:

   ```c
   /**
    * @name  Definitions for 8-bit Timer/Counter2
    * @note  t_OVF = 1/F_CPU * prescaler * 2^n where n = 8, F_CPU = 16 MHz
    */
   // WRITE YOUR CODE HERE
   #define TIM2_overflow_16ms()   TCCROB &= ~ (1<<CS01) ; TCCROB | = (1<<CS02) | (1<<CS00);
   #define TIM2 overflow interrupt enable() TIMSK2|=(1<<TOIE0);
   #define TIM2 overlow interrupt disable() TIMSKO &= ~(1<<TOIE);
  

Counter 0:  TCNT0, OCR0A, OCR0B, TIFR0, TIMSK0 // 
Counter 2:  TCNT2, OCR2A, OCR2B, TIFR2, TIMSK2 // 


