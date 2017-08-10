```shell 
ls
    -a (all)
    -l (list)
    -R (recursion)
    *.txt
    ?.txt
    [A]*.txt ([] => or)
    [A-Z]*.txt
    [a-z]*.txt

su
exit
whoami
which
whereis
uname -a
cat .bash_history
pwd (print working directory)
cd (change directory)
mkdir (make directory)

```

```shell 
for i in {begin..end..hop}
do
done
```

```shell 
if [[ ]]
then
else
fi
```

```shell 
compare number:
- if [[ $a -eq $b ]]
- if [[ $a -ne $b ]]
- if [[ $a -ge $b ]]
- if [[ $a -gt $b ]]
- if [[ $a -le $b ]]
- if [[ $a -lt $b ]]
- if (( $a < $b ))
- if (( $a <= $b ))
- if (( $a > $b ))
- if (( $a >= $b ))
```

```shell 
compare string
- if [[ $x == [yY] ]]
- if [[ $x != $y ]]
- if [[ $x < $y ]]
- if [[ $x > $y ]]
- if [[ $x == "y" ]]
- if [[ $x == z* ]]
- if [[ $x == "z*" ]]
```
