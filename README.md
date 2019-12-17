# Listy dla blokera DNS

## Dostępne listy

* [gambling-sites.txt](https://github.com/mikejbc/test/blob/master/gambling-sites.txt)
* [porn-blocker-test.txt](https://github.com/mikejbc/test/blob/master/porn-blocker-test.txt)
* [garbage.txt](https://github.com/mikejbc/test/blob/master/garbage.txt)

## Komendy dla pihole

Update list z poziomu terminala

```{bash}
pihole updateGravity
```

Podgląd logu DNS na żywo

```{bash}
pihole -t
```

Wyszukanie domeny w logu

```{bash}
sudo grep nazwa-domeny.com /var/log/pihole.log
```

Sprawdzenie czy dana domena znajduje sie już na jednej z blocklist

```{bash}
pihole -q -adlist nazwa-domeny.com
```

## Źródło list

```
https://github.com/LukeSmithxyz/etc
```
