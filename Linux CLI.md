## π λ¦¬λμ€μ μ£Όμ λλ ν λ¦¬

| λλ ν λ¦¬ | μ€λͺ                                                         |
| -------- | ------------------------------------------------------------ |
| bin      | κΈ°λ³Έ λͺλ Ήμ΄λ€μ΄ μ μ₯λ λλ ν λ¦¬                              |
| boot     | λΆνμ νμν κ°μ§ νμΌλ€μ΄ μ μ₯λλ κ³³                      |
| dev      | μμ€ν λλ°μ΄μ€ κ΄λ ¨ νμΌλ€μ΄ μ μ₯λλ κ²                    |
| etc      | μμ€ν μ€μ μ κ΄λ ¨λ κ°μ’ νμΌλ€μ΄ μ μ₯λλ κ³³               |
| home     | μ¬μ©μμ ν λλ ν λ¦¬κ° μμ±λλ κ³³                           |
| lib      | μ»€λκ³Ό νλ‘κ·Έλ¨μ νμν κ°μ’ λΌμ΄λΈλ¬λ¦¬κ° μ μ₯λλ κ³³       |
| media    | CD, USBκ°μ μΈλΆ μ₯μΉλ₯Ό μ°κ²°νλ κ³³                          |
| mnt      | νλΆμ°© κ°λ₯ν μ₯μΉλ€μ μμλ‘ μ°κ²°νλ κ³³ (WSLμ κ²½μ° μλμ°μ λλ ν λ¦¬μ μ°κ²°) |
| opt      | μΆκ° ν¨ν€μ§κ° μ€μΉλλ κ³³                                    |
| root     | root(μ΅κ³ κ΄λ¦¬μ)κ³μ μ ν λλ ν λ¦¬                           |
| run      | μ€νμ€μΈ μλΉμ€μ κ΄λ ¨λ νμΌλ€μ΄ μ μ₯λλ κ³³                |
| sbin     | μμ€ν κ΄λ¦¬μμ© λͺλ Ήμ΄λ€μ΄ μ μ₯λλ κ³³                       |
| sys      | λ¦¬λμ€ μ»€λ κ΄λ ¨ μ λ³΄κ° μλ κ³³                              |
| tmp      | μμ€ν μ¬μ©μ€ λ°μνλ μμλ°μ΄ν°κ° μ μ₯λλ κ³³              |
| usr      | κΈ°λ³Έ μ€ννμΌ, λΌμ΄λΈλ¬λ¦¬, ν€λ νμΌλ±μ΄ μ μ₯λλ κ³³         |
| var      | μμ€ν μ΄μμ€ λ°μνλ λ°μ΄ν°, λ‘κ·Έκ° μ μ₯λλ κ³³            |
| proc     | μ€νμ€μΈ νλ‘μΈμ€ λ° μ»€λ μ λ³΄κ° μ μ₯λλ κ³³ λμ€ν¬μμ΄ μλ λ©λͺ¨λ¦¬μ μ‘΄μ¬ |



------

## β¨οΈ λ¦¬λμ€μ μ€μ λͺλ Ήμ΄λ€

### pwd

> print working directory (ν¬μ§μμ΄ μλκ°)

νμ¬ μμΉν λλ ν μ μ λκ²½λ‘λ₯Ό νμν©λλ€.



### ls

> list (λΌμ)

νμ¬ μμΉν λλ ν λ¦¬ λ΄ νμΌ/λλ ν λ¦¬ λͺ©λ‘μ νμν©λλ€.

| μ΅μ | μ€λͺ                                                         |
| ---- | ------------------------------------------------------------ |
| -a   | μ¨κΈ΄νμΌμ ν¬ν¨ν λͺ¨λ  ν­λͺ© νμ                             |
| -d   | λλ ν λ¦¬ μ λ³΄λ§ νμ                                         |
| -F   | λλ ν λ¦¬λ /, μ€νκ°λ₯ νμΌμ *, μμΌνμΌμ =, λ§ν¬μΈ κ²½μ° @λ₯Ό νμΌμ΄μ λ€μ νμ |
| -l   | κ° ν­λͺ©μ μμΈ μ λ³΄λ€μ ν¨κ» νμ                            |
| -m   | κ° ν­λͺ©λ€μ μΌνλ‘ κ΅¬λΆνμ¬ νμ                             |
| -r   | ν­λͺ©λ€μ μ­μμΌλ‘ νμ                                       |
| -R   | νμ λλ ν λ¦¬μ λ΄μ©λ€λ νμ                                |
| -s   | kb λ¨μλ‘ νμ                                               |
| -t   | μ΅μ’ μμ μκ°μ κΈ°μ€μΌλ‘ νμ                                |
| -u   | μ΅μ’ μ‘μΈμ€ μκ° κΈ°μ€μΌλ‘ νμ                               |



### cd `{κ²½λ‘}`

> πͺ change directory (μ₯ λ€μ΄κ°κΈ°) λ€μ λ§λΆμ¬μ§ κ²½λ‘λ‘ μ΄λνλ λͺλ Ήμ΄μμ.



### mkdir `{λλ ν λ¦¬λͺ}`

> π make directory

λλ ν λ¦¬λ₯Ό μμ±ν©λλ€.

```
mkdir myfolder
```





### vi `{μμν  λλ μ΄μ΄λ³Ό νμΌλͺ}`

π vi μν°ν° μ€νν΄μ. ν΄λΉ νμΌλͺμ νμΌμ΄ μμΌλ©΄ μ΄κ³  μμΌλ©΄ μλ‘ μμ±(:wqλ‘ μ μ₯ν΄μΌ λ§λ€μ΄μ§)νμ£ .
[πvi λͺλ Ήμ΄ λ°°μ°λ¬κ°κΈ° βΆβΆβΆ](https://www.yalco.kr/10_vim)



### cp `{λ³΅μ¬ν  λμ}` `{λΆμ¬λ£μ κ²½λ‘ λλ μ νμΌλͺ}`

> π copy

νμΌμ λ³΅μ¬ν©λλ€. λλ ν λ¦¬λ₯Ό λ³΅μ¬ν  μμλ cp λ€μ -rμ λΆμ¬μΌ ν΄μ.

```
cp original.txt copied.txt
```



 

```
cp original.txt ../anotherfolder/
```





### mv `{μ?κΈΈ λμ}` `{λμ λλ ν λ¦¬ λλ μ νμΌλͺ}`

> move

νμΌμ΄λ λλ ν λ¦¬λ₯Ό μ?κΈ°κ±°λ μ΄λ¦μ λ³κ²½ν  λ μ¬μ©ν©λλ€.

```
mv original.txt ../anotherfolder/
```



 

```
mv original.txt renamed.txt
```





### rm `{μ­μ ν  λμ}`

> remove

νμΌμ΄λ λλ ν λ¦¬λ₯Ό μ­μ ν©λλ€. λλ ν λ¦¬λ₯Ό μ­μ ν  λλ rm λ€μ -rμ λΆμ¬μΌ νμ£ .

```
rm fileTodelete.txt
```



 

```
rm -r folderToDelete
```





### sudo `{λͺλ Ήμ΄}`

μ΅κ³ κ΄λ¦¬μ κΆνμ΄ μμ΄μΌ μ€νν  μ μλ λͺλ Ήλ€ μμ λΆμ¬λ£μ΄μ. μ€νμ λΉλ°λ²νΈλ₯Ό μκ΅¬νκΈ°λ νμ£ .
μ΄λ€ λͺλ Ήμ΄ μλ ₯μ `Permission` κ΄λ ¨ μ€λ₯κ° λ¬λ€λ©΄ `sudo` λͺλ Ήμ΄ νμνκ±°μμ.

```
sudo apt update
```



 

```
sudo rm -r importantFolder
```





------