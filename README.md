# RIPEMD160.net

This is a simple implementation of RIPEMD160 for .NET

I need to have Renci SSH.NET compiled for my project and it doesn't compile from the devel branch for .NET core as .NET Core 2 is lacking RIPEMD160 support.

I am not a hashing expert, so I focused on functional. The initial commit is pretty much a REALLY straight port of [H. Dobbertin, A. Bosselaers, B. Preneel, ``RIPEMD-160, a strengthened version of RIPEMD](https://homes.esat.kuleuven.be/~bosselae/ripemd160.html). I have basically just ported it and done some basic testing and debugging.

The version I'm working on now will work as expected in [System.Security.Cryptography](https://docs.microsoft.com/en-us/dotnet/api/system.security.cryptography.ripemd160?view=netframework-4.7.1) so that it can be added directly to SSH.NET. 

License, I believe the original code is released into the public domain. I am also releasing my code into the public domain in this case.

If you need to include it in a project and need more details for licensing, please contact me and I'll assist however I can though I'm not a lawyer. I can relicense under MIT if that helps.