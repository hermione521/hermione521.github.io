---
layout: post
title: Bandit (unfinished)
---

Just to save checkpoint...

##level 0
bandit

##level 1
boJ9jbbUNNfktd78OOpsqOltutMc3MY1

##level 2
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

##level 3
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

##level 4
pIwrPrtPN36QITSp3EQaw936yaFoFgAB

##level 5
in -file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh

##level 6
    find . -size 1033c ! -perm /a+x

DXjZPULLxYr17uwoI01bNLQbtFemEgo7

##level 7
    find / -user bandit7 -group bandit6 -size 33c

HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

##level 8
cvX2JJa4CFALtqS87jk27qwqGhBM9plV

##level 9
    cat data.txt | sort | uniq -u

UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

##level 10
    strings data.txt | grep "="

truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

##level 11
    base64 -d data.txt

IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

##level 12
    cat data.txt | tr [a-zA-Z] [n-za-mN-ZA-M]

5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

##level 13
    file xxx
    according decompress command

8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

##level 14
    scp bandit13@bandit.labs.overthewire.org:~/sshkey.private sshkey.private
    chmod 600 sshkey.private
    ssh -i ./sshkey.private bandit14@bandit.labs.overthewire.org

4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e

##level 15
    telnet localhost 30000

BfMYroe26WYalil77FoDi9qh59eK5xNr

##level 16
    openssl s_client -connect localhost:30001 -quiet

cluFn7wTiGryunymYOu4RcffSxQluehd

##level 17
my idea:

    nc -vz localhost 31000-32000 2>&1 | grep succeeded
    openssl s_client -connect localhost:31046 -quiet
    ...
    31046 31518 31691 31790 31960

reference:

    nmap -sT localhost -p31000-32000
    echo test | nc -v localhost 31046
    ...

key:

    -----BEGIN RSA PRIVATE KEY-----
    MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
    imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
    Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
    DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
    JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
    x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
    KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
    J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
    d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
    YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
    vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
    +TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
    8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
    SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
    HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
    SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
    R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
    Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
    R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
    L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
    blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
    YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
    77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
    dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
    vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
    -----END RSA PRIVATE KEY-----

##level 18
kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd

##level 19
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x

##level 20
    ./bandit20-do --help
    ./bandit20-do cat /etc/bandit_pass/bandit20

GbKksEFF4yrVs6il55v6gwY5aVje5f0j

##level 21
one terminal:

    nc -l localhost 8080
    GbKksEFF4yrVs6il55v6gwY5aVje5f0j

the other:

    ./suconnect 8080

gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr

##level 22
    cat /etc/cron.d/cronjob_bandit22
    cat /usr/bin/cronjob_bandit22.sh
    cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv

Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI

##level 23
    cat /usr/bin/cronjob_bandit23.sh
    echo I am user bandit23 | md5sum | cut -d ' ' -f 1
    cat /tmp/8ca319486bfbbc3663ea0fbe81326349

jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n

##level 24 ???
    \#!/bin/bash
    cat /etc/bandit_pass/bandit24 > /tmp/level24/bandit24

wait for a minute..

0_0 Nothing happened!

It should be UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ

##level 25

