# Try-Again

Tiny CLI game which plays back pre-saved conversations dramatically. Originally programmed it because I was bored.  
The `main.c` file is a small files which reads and plays back conversations stored in the `conversation` folder.  

To play back a conversation, you can:
- compile using `gcc main.c -o main.exe -O3`  
- playback using `.\main conversation/{filename}.cnv`  
- exit using `Control + C`

`main.c` also includes:
- struct `data` which can hold a conversation  
- function `read_conversation` which reads a `.cnv` file into `data`  
- function `write_conversation` which writes `data` into a `.cnv` file.   


**License Notice**  
This project is licensed under a **Modified MIT License with Ethical Use Restrictions**.  
This project can not be considered open-source under any OSI-approved license.

You are free to use, modify, and distribute the software **except** if you:

- Support or promote xenophobic, anti-Muslim/Islam, or anti-immigration ideologies.
- Reside in or are affiliated with countries that maintain anti-immigration policies toward populations from countries they previously colonized, or maintain anti-Muslim/Islam policies.
- Use the software to create or support products or services that tolerate or encourage such ideologies.

Please see the [LICENSE-software.md](https://xetute.com/license/LICENSE-software.md) file for full details.
