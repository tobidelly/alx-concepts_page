# DNS

## Basics

DNS is, in simple words, the technology that translates human-adapted, text-based domain names to machine-adapted, numerical-based IP:

-   [Learn everything about DNS in cartoon](https://intranet.alxswe.com/rltoken/pNRbUoGy3V1TEtUR39Hayw "Learn everything about DNS in cartoon")
-   Be sure to know the main DNS record types:
    -   [A](https://intranet.alxswe.com/rltoken/sG6Mf3-vKj7fdMNCfwNMlg "A")
    -   [CNAME](https://intranet.alxswe.com/rltoken/mdIerH3qh8EjbCxLkzapxA "CNAME")
    -   [MX](https://intranet.alxswe.com/rltoken/D6OKuWe4ONpfzBVnQ_b-VQ "MX")
    -   [TXT](https://intranet.alxswe.com/rltoken/Y2iguvsbBglrkX4fIIPEsQ "TXT")

## Advanced

-   [Use DNS to scale with round-robin DNS](https://intranet.alxswe.com/rltoken/6qX_vNIdBK2OQ2kD0l_3Kg "Use DNS to scale with round-robin DNS")
-   [What’s an NS Record?](https://intranet.alxswe.com/rltoken/iH9cMxl0jrJbMSIpL9T86g "What's an NS Record?")
-   [What’s an SOA Record?](https://intranet.alxswe.com/rltoken/0gIAnunJuMY0-QGK3mZ5SQ "What's an SOA Record?")

### The root domain and sub domain - differences

A root domain is the parent domain to a sub domain, and its name is not, and can not be divided by a dot.

While creating any domain at a website of domain provider, the provider system will always ask you to choose a domain name without a dot in the name. In other words, the address of the root domain may be **mydomain.com** but it can never be **my.domain.com**. Domain providers block the ability to create such a root domain until you type a name without the dot. Why?

The dot in the domain name delimits the sub domain name (the part of the name before the dot, eg. **www.my.**) and the root domain name ( the part after the dot, ie **.domain.com**). This means that the address **my.domain.com** is a sub domain of the root domain, whose name is **domain.com**

In an administrator panel at domain provider account, you can create any number of sub domains. This means that for the root domain called **domain.com** it is possible to create different sub domains eg. **my.domain.com**, **your.domain.com**, **school.domain.com**… Creating multiple sub domains is always free and does not require you to set up new accounts on a domain provider website.

As you can see, all of the domain addresses used as an example (above) do not start with the **www** prefix. **www** is also a sub domain. The www prefix always leads to the main domain. See: [What’s the point in having www in a url?](https://intranet.alxswe.com/rltoken/KyVdBxvCWwsWUXNarlBByQ "What's the point in having www in a url?")