# OWASP Unsafe Passwords

This repo contains JSON dictionaries with top unsafe passwords. Passwords has been taken from dictionaries found at
https://weakpass.com/. Those files can be used e.g. if you are implementing
[OWASP Application Security Verification Standard 4.0](https://github.com/OWASP/ASVS/raw/master/4.0/OWASP%20Application%20Security%20Verification%20Standard%204.0-en.pdf).

All passwords:

* are at least 12 characters in length (OWASP ASVS 4.0 - 2.1.1)
* are in lower case (you need to transform password to lower case before check)

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.
