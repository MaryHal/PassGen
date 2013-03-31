PassGen
=======

Randomly generate simple passwords.

Help
====
> Usage: passgen [options] [length of passwords to generate]
>     -n, --numbers                    Exclude numbers
>     -u, --uppercase                  Exclude uppercase
>     -l, --lowercase                  Exclude lowercase
>     -s, --symbols                    Exclude symbols
>     -a, --ambiguous                  Exclude (possibly) ambiguous
>     -q, --quantity [num]             Number of passwords to generate
>     -h, --help                       Display this screen


Example Output
==============
> Generate 10 passwords of length 10 disallowing uppercase letters and ambiguous letters.
>     ./passgen -uaq10 10
>     >\u/}k8pfv
>     =tzo&*=jf?
>     x4m;4.{%tq
>     #afp]h+43_
>     .;<@$6b'>9
>     <$/3^7a:7`
>     t`_+4--^#9
>     |?#w]@g^%:
>     _z=s~./r.*
>     |hm=8+zq3-
>
> Generate 10 passwords of length 20 disallowing symbols and ambiguous characters.
>     ./passgen -saq10 20
>     6m3HVZN7fZYdScyXyUyV
>     WGkKjpuHNqXYNweXEPMr
>     phWr3j2MjL3FHSpzUsMb
>     rhvzysWGmnn6TpTe4W2A
>     JutjAxApbpX3oHbhkdtM
>     MBcpKNdFBcPWbfTKw3FL
>     PByEeMZGRGJAEqVvZSJL
>     JGuLrBd82Y8dFkEkTj59
>     iN8D7xMrkwk6im3bivx2
>     z7drYXo4gwKc3A9AtJ46

