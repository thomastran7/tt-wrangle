# Module 1: Bonus Challenge 
## Thomas Tran

1. My assigned play is "King Lear"

2. Speaker 1: Kent

3. Speaker 2: Edgar

4. Question that was asked is: how many times did each speaker spoke and the sum of how many times the speakers spoke.

5. </br> 
- First command was used to take the whole html and put it into a text file. </br>
```curl "http://shakespeare.mit.edu/lear/full.html" -o king.txt``` 
- This next command was used to count the number of times Kent was mentioned and the output was put into a text file. </br>
``` grep 'KENT' king.txt -c > kent_count.txt ```
- Same as the command above, but instead of Kent, I've replaced that name with Edgar. </br>
``` grep 'EDGAR' king.txt -c > edgar_count.txt ```

6. </br>
- Kent spoke 154 times in the play.
- Edgar spoke 125 times in the play.
- The total sum of both speakers (Kent & Edgar) is 279 (154+125).
