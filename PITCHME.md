## Password Security

#### LA GitHub Field Day 2018

JonLuca De Caro

---

#### You've been lied to

---

The average American has been conditioned to use passwords that are easy for computers to guess, but hard for humans to remember

---

Walk through average user's password selection process: 

- Pick a password: *mittens (their cat's name)* ||
- Need a capital: Mittens |
- Need a special char: Mitten$ |
- Need a num: Mitten$1 |

---

Overall complexity? 

8 characters. 

Time to crack on an average desktop with a modern GPU? 

*9 hours* <p style="font-size: 12px">(for salted md5 - unsalted? Instantaneously)</p>

---

And those numbers are just with brute force attempts!

---

- In reality, *9.1%* of all passwords show up in the Top 1000 Common Passwords List |
- The password "123456" accounts for 1% of all passwords |
- Small variations in the most common passwords will drastically reduce cracking times | 

---

There are some pretty bad developers out there

- Still use SHA1
- Still use MD5
- Store passwords in plaintext (see: 000webhost)
---

No, this is an audience of good developers, right? |

You'll use PBKDF2 with HMAC-SHA512 with 1,000,000 iterations and a 1024 salt.

---

#### Is cracking a password the only attack?

---

Password reuse is actually a much more suble issue

+++

Most people use the same password for different sites
---

The crazy part?

- A lot of these are public |

- 16.1 Million usernames/passwords per GB (uncompressed) |

---

### Demo

Connect to `0xDEADBEEF` and navigate to 169.254.100.154


---

### Questions?

<br>

@fa[twitter gp-contact](@jonlucadecaro)

@fa[github gp-contact](jonluca)

@fa[medium gp-contact](@jonluca)