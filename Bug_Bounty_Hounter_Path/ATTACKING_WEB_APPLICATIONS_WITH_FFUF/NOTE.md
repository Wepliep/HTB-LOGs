## Bir ip yi etc/hosts a eklemek için kullanılabilecek bazı kısa komutlar:

```sh
+ echo "IP_ADDR   example.com" >> /etc/hosts
```
```sh
+ sudo sh -c 'echo "IP_ADDR   example.com" >> /etc/hosts'
```

## 1 den 1000 e kadar artan sayıları txt ye yazdırma:
```SH
Wepliep@htb[/htb]$ for i in $(seq 1 1000); do echo $i >> ids.txt; done
```
```SH
Wepliep@htb[/htb]$ cat ids.txt

1
2
3
4
5
6
<...SNIP...>
```

