# Intro to Offensive Security

## Hacking your first machine

```
gobuster -u http://fakebank.com -w wordlist.txt
```

- -u: The target URL or Domain
- -w: Path to wordlist

```
/bank-transfer
```

Visting this page led me to the admin portal.

I successfully transferred $2000 from 2276 to 8881 and got the answer to the TryHackMe question.

```
BANK-HACKED
```

## What is Offensive Security?
Offensive Security is the process of breaking into computer systems, exploiting software bugs, and finding loopholes in applications to gain unauthorized access to them.

## Glossary
- gobuster: Directory brute forcing tool that sends a lot of requests to a webpage and sees if any pages exists.
