### Hello there 👋

## Profile:
My name is **Charis** born 1/6/2003(d/m/y),
i'm a young self motivated developer currently
working at [InterMediaKT](https://intermediakt.org/), with a 
passion for backe-end development and the cyber-security industry.

```python
txt = [
    "Dev instance can't code bcs it's healthy. Run unSleep() and drinkCoffe() first to proceed",
    "uNSLeeping",
    "Drinking Coffee",
    "Coding"
]
st = [0, 0]

sl = lambda tm: __import__("time").sleep(tm)
pr = lambda text: print(text)

cl_dev_drc = lambda: (pr(txt[2]), sl(1), st.__setitem__(0, 1)) if not st[0] else None
cl_dev_usl = lambda: (pr(txt[1]), sl(1.5), st.__setitem__(1, 1)) if not st[1] else None
cl_dev_cod = lambda: (cl_dev_ren(1), True) if st[0] and st[1] else (pr(txt[0]), sl(1), cl_dev_drc(), cl_dev_usl(), False)

cl_dev_ren = lambda num: (pr(f"{txt[3]}{'.' * num}"), sl(.5), cl_dev_ren(num + 1) if num < 10 else None) if num < 10 else None

if not cl_dev_cod()[1]:
    cl_dev_cod()
```

## Things about me:
  - I'm a fast patient learner
  - Passionate about everything i do
  - Intrigued by complicated problems
  - Adaptable to any kind of environment
  - Fun to work with

## Jobs:
  - Vongrid: API Developer
  - InterMediakt: Software Engineer

## Hobbies:
  - Snowboarding
  - Roadtrips (Motorcycle)
  - Learning assembly for 6502 processor to make games for Atari2600

## Languages i speak:
  - Greek
  - English

Reach me through [Linkedin](https://www.linkedin.com/in/charalampos-rentoumis-69991b21b/)

### Other
[![HackTheBox](https://img.shields.io/badge/HackTheBox-111927?style=for-the-badge&logo=Hack%20The%20Box&logoColor=9FEF00)](https://app.hackthebox.com/profile/133324)

[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=TryHackMe&logoColor=white)](https://tryhackme.com/p/5skr0ll3r)
