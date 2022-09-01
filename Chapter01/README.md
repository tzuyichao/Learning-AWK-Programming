
### Field Separator

```
awk -F: '/bash/ { print $1 "\t" $0 }' /etc/passwd
```

```
awk --field-separator=: '/bash/ { print $1 "\t" $0 }' /etc/passwd
```


### Regular Expression

```
terence@terence-virtual-machine:~/lab/Learning-AWK-Programming/Chapter01$ awk '$2 ~ /mail/' emp.dat
terence@terence-virtual-machine:~/lab/Learning-AWK-Programming/Chapter01$ awk '$4 ~ /mail/' emp.dat
Jack    Singh   9857532312  jack@gmail.com      M   hr      2000
Jane    Kaur    9837432312  jane@gmail.com      F   hr      1800
Eva     Chabra  8827232115  eva@gmail.com       F   lgs     2100
Ana     Khanna  9856422312  anak@hotmail.com    F   Ops     2700
Victor  Sharma  8826567898  vics@hotmail.com    M   Ops     2500
John    Kapur   9911556789  john@gmail.com      M   hr      2200
Sam     khanna  8856345512  sam@hotmail.com     F   lgs     2300
Emily   Kaur    8826175812  emily@gmail.com     F   Ops     2100
Amy     Sharma  9857536898  amys@hotmail.com    F   Ops     2500
```

