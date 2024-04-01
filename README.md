# madm 
Mail auto configuration and interactive administration for OpenBSD
[Introduction (ru)](https://telegra.ph/Pereezd-pochty-05-24)
[How to script works (ru)](https://github.com/vasyahacker/madm/raw/main/explanation_ru.txt)

### Features
- Multi domain
- Mailbox quota
- Mailbox encryption (mail text <- secp521r1 <- SHA512 <- user password)

### Requirements / Components
- OpenBSD with OpenSMTPD (that's all, the rest of the packages will be automatically installed at first run)
- Dovecot
- Rspamd
- Redis
- SQLite
- imapsync (optional)

### Usage

Just download and run ./madm

Then the script will take care of everything

### Links
[there are a lot of links, so Google spreadsheet](https://docs.google.com/spreadsheets/d/1acLUWan3KfgRC4f8cv53Tr3hnavbfVNRbJUQlrmKrio/edit?usp=sharing)
