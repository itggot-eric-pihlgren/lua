Lua
======

## Stark eller svag typning
Lua är ett språk som använder sig av svag typning. Kodexemplet nedan gav ett svar utan felmeddelanden.
```lua
x = "20";
y = 10;

z = x + y;

print(z)
```
__Output__
```bash
30
```
## Dynamisk eller statisk typning
Lua har en dynamisk typning.  Kodexemplet nedan gav ett svar utan felmeddelanden.
```lua
x = 20
x = 10
x = 13.37

function add(y, z)
	return y + z
end

print(add(13, 37))

print(add("13", "37"))
```
__Output__
```bash
50
50
```

### Kompilerat eller Tolkat
Lua är ett tolkat språk.

## Native eller Virtuell maskin
Lua använder sig av en regiserbaserad virtuell maskin.

## Imperativt/Procedurellt eller Deklarativt
Lua är ett procedurellt och imperativt programspråk.

## Funktionellt
Lua är ett funktionellt språk.

## Objektorientering
Lua är i grunden inte ett objektorienterat språk, men det tillhandahåller mekanismer för att implementera klasser och arv direkt i språket.

## Open eller Closed Source
Lua är ett "Open Source" språk och vem som helst får göra vad som helst.

## Användningsområde
Meningen med Lua var att bli ett generellt inbäddningsbart förlägnt språk. Utvecklarna på Lua, fokuserade på att förbättra fart, portabelitet, sträckbarhet och lätthanterligt i utveckling.

## Övriga utmärkande drag
