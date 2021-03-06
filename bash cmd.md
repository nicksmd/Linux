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
for i in {1..99..2}
do
done

for (( i=1; i<=$n; i++))
do
done

while
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

```shell
Operations
echo "5/2" | bc -l
echo $((5/2))
echo "scale=2; 100/3" | bc
let "count=$count+1"
```

```shell
text processing

cut -f -d
cut -c7
cut -c1-3

head -n
head -c

tail -n+K
tail -c+K

echo "Hello" | tr "e" "E"
 => HEllo
echo "Hello how are you" | tr " " '-'
 => Hello-how-are-you
echo "Hello how are you 1234" | tr -d [0-9]
 => Hello how are you
tr a-z A-Z
tr [:space:] '\t'
tr -d [:digit:]
tr "[([]" "[)]]"
tr -s " "
tr -s "\n"

sort
sort -n
sort -r
sort -k 2
sort -k 2 -t $'\t'
sort | uniq
sort -u

uniq
uniq -c (count)
uniq -d (get only duplicate value)
uniq -i (case insensitive)
uniq -u (get only unique value)

```

```shell
a[i]=$x
echo ${a[@]}
echo ${a[0]}
echo ${#a[@]}
declare -a array=(1 2 3)
a=($(cat))
```

```shell
grep -i (case insensitive)
grep -w (match only word)
grep -v (invert match)

sed 's/abc /xyz/gi'
sed 's/abc/{&}/gi'
```
