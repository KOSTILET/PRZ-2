# PRZ-2
PRZ-2
1. sudo su
2. sudo useradd super-{Kostomakhin.a.a}
3. passwd super-{Kostomakhin.a.a}
4. usermod -aG sudo super-{Kostomakhin.a.a}
5. groupadd group-{a}
6. usermod -aG group-{a} super-{Kostomakhin.a.a}
7. groups super-{Kostomakhin.a.a}
8. useradd user-{Kostomakhin.a.a}
9. usermod -aG group-{a} user-{Kostomakhin.a.a}
10. mkdir /home/super-{Kostomakhin.a.a}
11. chmod 770 /home/super-{Kostomakhin.a.a}
12. su user-{Kostomakhin.a.a}
13. touch /home/super-{Kostomakhin.a.a}/test1.txt
![prz-2](https://github.com/KOSTILET/PRZ-2/assets/64083435/c8c97de9-7ea5-45af-bbb3-051b6dde1d4d)
