---
layout: post
title: Note Python programing
description: My Python note programing.
date: 2020-02-20 10:59:00 +0700
categories: note
thumbnail: https://lh3.googleusercontent.com/fDrGzZVF22gr0E7GBxvTl4ulSYHv-U8UfER9MbT4ZAnYFVhiu5VstWsaNYx7X-Hn2iJn8rLP5z2oR0yGmK-CeE-eYSKSyGAlDy9mmsQDXS-_6FXbDYnXI1QaeOCKUe6AdU_r1UnOSSCaPbr2QTQa4XwJBQ1cPb4FPM8BQL_D1X36F_DljGqYYr8MdjPEahWardJxvc-D-gSCEOFcs9QYzpLDWGIRNTnXmjy2-LaZt419Cly4hn2MY78d1PgFI_Zh15dGgcIKjq_fpU3CgdltCaUvY1oXFZoL__7S8nJf6n6-Z_mcrq284gBVjuVmGm36QGG61wWlIj3wylV8mqOWR0dXxKalib23n3FdhWnObGfW_5LyUzgwbrSHIUSrS7CLEPxlmV8tA3UcX-hk0LqFVjsGOiwLnUS_C6Gl_A52N5kfW2JT61q5Q-Jllkfv0JEQDtAAqEG6WgWYosKu2mjJaTwvFKBued7EoKwMZVWPoJHrSXi_Cf_di-uO5_NxiKzpCUBfxbWjpiKWWAj9xfkRLjKTWMwoDelFaaAaUGOvaPZvFjQen8PpwtRihuZaSldexQja9ahmFRKNkdT0WVjGo10HQ_g6za56pqZoZrPDNuQPSurNp3HTQij5LLZOdS_rNPEVkSUn_Y_MO0iM_JfBDdAP6vTGHw5MmxsawHNHRImDlb9pmgm-oFBejrFXe8uBbEDoA6rJbVvP0IYAgn_d0xqv85-lhwxhBr5dEX4xe9leBNYR=w308-h164-no
---

![](https://lh3.googleusercontent.com/ZOSkiyEXEv6OmPBob4MEemSuaVKotkqzZnO7qn6IJ3F0CKbmMhI_QG7_9vf2uoEQqqyRze1JgsU-FBLlrfXiBxJNVGcloWHDXzX9j6PiJvZMJ2NrHq_04GNJ-e8YawyB9vq4QwQ26T4895AuqHfkjp69_ZlT8hLnYtjHndKO_G07JUTV5LSuFPX2YC3OMsKjPsn7z2FMWaVwMbNACjLlaFgGO4lOJnic0wi4L-xRBAizP0Z2LM6vLfqz_gWZV4Kgx_Xew7tCG8CvElFWkEwxc-flk8BUmxRlPpz43KDz5Fujrx9untedGqbtR_8BbaI25F_DSLFV5mHgPaMd6UMD5-wwkqsr8yjkTNOxpwr4GIFOVKevHGNpNFg3WGPhHZhHph8v9DWoAnBTp4migm8WCPWDmRiIJtxSNfrM5KfGk05TZx53HJDwHA3ygM_TR3EJi99WawrSPRq0JDtAdfacpcsqkyHEGwBTvHEbF-eFZ_G2PAgBgk4sqmks0a-kCMqY6cWSKkXSCDesTFUqkzlnj1LaDC4UVkMltSHo-nF1o4FmNJ3bi_TgEbNMs8Ksm5Ea7BtqsfdO-hJo5T-o-jx-hWOmOBuT6s2EzQoVOOFa1nKFnnG6JrI35vh_LDs0RnSCSK28fC-8wVsZi0-7CdiY1muHHcd-X7Ime4pItBPuHsbleaulP-6wLnZmZ8MnIF-4W6sklPSh5I4Mlfb13pCrL2xl77CLtd1VxTWsaXCw4YNqbK70=w680-h357-no)


### Criteria
- Known about python syntax
- Note some functions written by python

### Concept
- [What is python?](https://vi.wikipedia.org/wiki/Python_(ng%C3%B4n_ng%E1%BB%AF_l%E1%BA%ADp_tr%C3%ACnh)){:.text-link}
- 

### Programing
- *** "Tìm năm nhuận?" ***
```python
def checkYear(year): 
    # Return true if year is a multiple 
    # of 4 and not multiple of 100. 
    # OR year is multiple of 400. 
    return (((year % 4 == 0) and (year % 100 != 0)) or (year % 400 == 0)); 

year = 2000
if(checkYear(year)): 
    print("Leap Year") 
else: 
    print("Not a Leap Year")
```

- *** Find min max ***
```python
nums = [1, 8, 2, 23, 7, -4, 18, 23, 42, 37, 2]
 
max(nums)
```

- *** Sort numbers ***
```python
numbers = [1, 3, 4, 2] 

# Sorting list of Integers in ascending 
numbers.sort() 

print(numbers)
```

### Note

### TODO
- Reading
-

### References
- [What is python?](https://vi.wikipedia.org/wiki/Python_(ng%C3%B4n_ng%E1%BB%AF_l%E1%BA%ADp_tr%C3%ACnh)){:.text-link}
- [https://www.w3schools.com/python/](https://www.w3schools.com/python/){:.text-link}