# Sergey Sapunov

## Contacts
![email](images/m.png)
![mobile phone number](images/pn.png)

## Personality

## Skills
* Comp langs
  * Turbo-assembler (self eduction, last time ~1999)
  * Turbo-prolog (university program)
  * Turbo-pascal (university program)
  * Borland Delphi (university program)
  * Borland C++ Builder 6.0 (productive)
  * C# (university program)
  * Java (in progress)
* CLI automation (cmd, ps)
* SOLID, KISS, DRY, YAGNI
* Programming patterns (in progress)

## Code samples

```Java
    String idToShortURL(int n)
    {
        char[] map = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".toCharArray();
        if (n == 0) {
            return "a";
        }
        StringBuilder shortUrl = new StringBuilder();
        while (n > 0)
        {
            shortUrl.append(map[n % 62]);
            n = n / 62;
        }
        return shortUrl.reverse().toString();
    }
```

## Work Experience

## Education
* Bachelor of Maths, Krasnoyarsk State University (1996-2000)
* Stepic Certs
  * [Java](https://stepik.org/cert/484608)
  * [Linux](https://stepik.org/cert/108618)

## Languages
* Russian (native)
* English (B1)
* German (A1)
