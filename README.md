# Lakhya2
lakhya@DESKTOP-AC8492J:~$ pwd
/home/lakhya
lakhya@DESKTOP-AC8492J:~$ ls
lakhya@DESKTOP-AC8492J:~$ cd
lakhya@DESKTOP-AC8492J:~$ mkdir tezpur
lakhya@DESKTOP-AC8492J:~$ pwd
/home/lakhya
lakhya@DESKTOP-AC8492J:~$ cd /home/lakhya/tezpur
lakhya@DESKTOP-AC8492J:~/tezpur$ pwd
/home/lakhya/tezpur
lakhya@DESKTOP-AC8492J:~/tezpur$ ls
lakhya@DESKTOP-AC8492J:~/tezpur$ mkdir documents
lakhya@DESKTOP-AC8492J:~/tezpur$ pwd
/home/lakhya/tezpur
lakhya@DESKTOP-AC8492J:~/tezpur$ ls
documents
lakhya@DESKTOP-AC8492J:~/tezpur$ mkdir music
lakhya@DESKTOP-AC8492J:~/tezpur$ ls
documents  music
lakhya@DESKTOP-AC8492J:~/tezpur$ mkdir games
lakhya@DESKTOP-AC8492J:~/tezpur$ ls
documents  games  music
lakhya@DESKTOP-AC8492J:~/tezpur$ cd /home/lakhya/tezpur/documents
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ pwd
/home/lakhya/tezpur/documents
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ touch me.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
me.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ touch we.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ touch sivasagar.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
me.txt  sivasagar.txt  we.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ mv me.txt tezpur/
mv: cannot move 'me.txt' to 'tezpur/': No such file or directory
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
me.txt  sivasagar.txt  we.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ mkdir sivasagar
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
me.txt  sivasagar  sivasagar.txt  we.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ mv sivasagar.txt sivasagar/
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
me.txt  sivasagar  we.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ cd /home/lakhya/tezpur/documents/sivasagar
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ ls
sivasagar.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ mkdir jorhat
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ mv me.txt jorhat/
mv: cannot stat 'me.txt': No such file or directory
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ cd /home/lakhya/tezpur/documents
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ mv me.txt jorhat/
mv: cannot move 'me.txt' to 'jorhat/': No such file or directory
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ mv me.txt sivasagar/
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
sivasagar  we.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ touch zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
sivasagar  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ mv *.txt sivasagar
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ ls
sivasagar
lakhya@DESKTOP-AC8492J:~/tezpur/documents$ cd /home/lakhya/tezpur/documents/sivasagar
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ ls
jorhat  me.txt  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ mv we.txt jorhat/
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ ls
jorhat  me.txt  sivasagar.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ mv *t jorhat/
mv: cannot move 'jorhat' to a subdirectory of itself, 'jorhat/jorhat'
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ mkdir ghy
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ ls
ghy  jorhat
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ ls
ghy  jorhat
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ mv *t ghy/
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ ls
ghy
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar$ cd /home/lakhya/tezpur/documents/sivasagar/ghy
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy$ ls
jorhat
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy$ cd /home/lakhya/tezpur/documents/sivasagar/ghy/jorhat
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
me.txt  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls ghy/
ls: cannot access 'ghy/': No such file or directory
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ touch jitu
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
jitu  me.txt  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ touch minu
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
jitu  me.txt  minu  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ mv jitu minu/hiru
mv: failed to access 'minu/hiru': Not a directory
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ mkdir minu
mkdir: cannot create directory ‘minu’: File exists
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ mkdir hari
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
hari  jitu  me.txt  minu  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ mv jitu hari/hiru
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
hari  me.txt  minu  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ cd /home/lakhya/tezpur/documents/sivasagar/ghy/jorhat/hari
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat/hari$ ls
hiru
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat/hari$ mv hari ghy/
mv: cannot stat 'hari': No such file or directory
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat/hari$ cd
lakhya@DESKTOP-AC8492J:~$ pwd
/home/lakhya
lakhya@DESKTOP-AC8492J:~$ cd /home/lakhya/tezpur/documents/sivasagar/ghy/jorhat
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
hari  me.txt  minu  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ rm -i me.txt
rm: remove regular empty file 'me.txt'?
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
hari  me.txt  minu  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ rm -i me.txt
rm: remove regular empty file 'me.txt'? y
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
hari  minu  sivasagar.txt  we.txt  zubeen.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ rm -i *.txt
rm: remove regular empty file 'sivasagar.txt'? y
rm: remove regular empty file 'we.txt'? n
rm: remove regular empty file 'zubeen.txt'? y
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ ls
hari  minu  we.txt
lakhya@DESKTOP-AC8492J:~/tezpur/documents/sivasagar/ghy/jorhat$ cd
lakhya@DESKTOP-AC8492J:~$ pwd
/home/lakhya
lakhya@DESKTOP-AC8492J:~$
