A python3 client for ruter.no, made using the API at http://labs.ruter.no/

GNU AFFERO GENERAL PUBLIC LICENSE

Example run of beta 0.3:


Direct hit:

```
$ ./ruter.py lijordet
Avganger fra lijordet, oppdatert 22:15
Linje/Destinasjon             Platform Tid           Type Forsinkelse
  5 Vestli                    1        22:19:59      Ⓣ
  5 Vestli                    1        22:34:59      Ⓣ
  5 Vestli                    1        22:49:59      Ⓣ
```

Long name:

```
./ruter.py "borgen (i sørkedalsveien)"
Avganger fra borgen (i sørkedalsveien), oppdatert 22:15
Linje/Destinasjon             Platform Tid           Type Forsinkelse
 45 Majorstuen                1        22:18:00      🚌
 45 Majorstuen                1        22:48:00      🚌
 45 Voksen skog               2        22:34:00      🚌
```

Several hits:

```
$ ./ruter.py majorstuen
Flere treff, angi mer nøyaktig:
[3010203] majorstuen (i valkyriegata)
[3010200] majorstuen [t-bane]
[3010201] majorstuen (i kirkeveien)
[3010202] majorstuen (i sørkedalsveien)
```
