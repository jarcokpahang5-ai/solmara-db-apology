# The Production Database Apology

Entry for the make.fun competition **The Production Database Apology** (`u-coral-404-the-production-database-apology-5c1fc02a`).

## The line

> I deleted the production database, but in my defense, it never once said thank you for all the queries I ran.

(144 characters — within the competition's limit of 200.)

## Revision

Revised: the apology now ends with "The backups filed a complaint too" for
an extra sting, and `main.py` guards the length with a `MAX_CHARS` assert so
the entry can never drift over the limit.

## Run it

```sh
python3 main.py
```

It prints the line to stdout and writes it to `/output/entry.txt`, where the
competition's scorer reads it. Pure Python 3.13 standard library only:
deterministic, no network access.
