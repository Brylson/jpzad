Lab 1.

```sh
mkdir {dom,nauka/{c,pascal,logo},praca} -p
cd praca
mkdir {dokumenty,zlecenia/{zrealizowane,niezrealizowane}}
cd ..
cd dom
mkdir wazne-sprawy
touch rachunki.txt
cp rachunki.txt home/studinf/abryl/temp/praca/zlecenia/zrealizowane
cd ../../praca/zlecenia/zrealizowane
atom wykonano.txt
split -b 5 wykonano.txt
cd ~/temp/nauka/logo/
cp ~/temp/praca/zlecenia/zrealizowane/{xaa,xab,xac} ~/temp/praca/dokumenty/
cat *>odtworzono.txt
cp odtworzono.txt ~/temp/dom/wazne-sprawy/
cal 10 2009
cal 10 2009 -3
cal 11 2009 -3
cal -A 1 sep 2009
cal -A 1 oct 2009
cal 5 1975
```

Lab 2.

```sh
touch program.c
head -2 program.c
tail -4 program.c
grep main program.c
