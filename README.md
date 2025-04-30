# pkg_kill
Fast OpenBSD package database unlocker

## Manifesto
The program is designed for fast and beautiful unlocking of OpenBSD package manager databases, as I often had problems with this. On OpenBSD, unlike Linux distributions, the lock for the database is not stored in a file, but is a process.

## Installation
```
git clone https://github.com/Ad4ndi/pkg_kill
doas cp pkg_kill/pkg_kill /usr/sbin
rm -rf pkg_kill
```

## Usage
Just type 'doas pkg_kill':
![image](https://github.com/user-attachments/assets/e0d6ec6f-a89c-42ce-ba00-e739f95d99f7)
