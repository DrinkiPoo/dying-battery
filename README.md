# dying battery

1. Just a quick script I wrote to check how fast my laptop battery charges and discharges.
2. Depends on:  1. **tlp-stat** 2. **mutt** (only if you want to email the result)
3. It's a function and take a single parameter of number of minutes
4. Place this code in you .bashrc file and you can call it from the terminal after reloading the bashrc file. 
5. You can let it run in the background with the `&` operator at the end
6. Play around with the output options commented out at the end

**Example**  
`rate 5 &` --> run this test for 5 min in the background.
`rate 2` --> run this test for 2 minuts (terminal will be cooupied).
