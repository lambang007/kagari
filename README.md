# kagari
Kagari adalah software di tullis dengan perl yang berfungsi untuk menemukan shell backdoor di suatu website
<pre>



root@kagari:~#  git clone https://github.com/alintamvanz/kagari.git
root@kagari:~# cd kagari 
root@kagari:~/kagari # chmod 777 *
root@kagari:~/kagari # ./install

----------------------------------------------------------------------------------------------------------------------------------
This tool is created to help you find the file, a shell, a directory in a website.

instructions for use :

kagari run         : to run this tool
kagari -h/--help   : to see this
kagari --uninstall : to uninstall this tool on your system


the instructions for use "kagari run" :

kagari:target   >> SiteTargetHere.com    : You must enter your target
kagari:wordlist >> wordlist.txt          : wordlist separated by "," (comma) as the default wordlist of Kagari, you can create your own wordlist
kagari:SOShell  >> Home|shell|Files      : It is a word or phrase that is in the shell, file, or directory you are looking for. This helps locate the file you're looking for using the Regular Expression

----------------------------------------------------------------------------------------------------------------------------------
