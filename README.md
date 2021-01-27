# rm
My assigned play was RichardIII  
Speaker1 is GLOUCESTER  
Speaker2 is BRAKENBURY  
### Commands which I have used  
curl "http://shakespeare.mit.edu/richardiii/full.html" -O  
grep 'GLOUCESTER' full.html  
grep 'BRAKENBURY' full.html  
grep -i 'GLOUCESTER' full.html  
grep -i 'BRAKENBURY' full.html
cat full.html | grep -i 'GLOUCESTER' -c  
cat full.html | grep -i 'BRAKENBURY' -c  
grep -n 'GLOUCETSER' nb.txt  
grep -in 'GLOUCESTER' nb.txt  
grep -iv 'GLOUCESTER' nb.txt  
grep -n 'BRAKENBURY' nb.txt  
grep -in 'BRAKENBURY' nb.txt  
grep -iv 'BRAKENBURY' nb.txt  
tr ' ' '\12' < nb.txt | sort | uniq -c | sort -nr > result.txt  

