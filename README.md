# Datárum

Datárum is a small python library to convert Gregorian dates to Autophagian,
an Old English variant on the [French Republican calendar](https://en.wikipedia.org/wiki/French_Republican_Calendar), 
for use in various projects. The year zero for this calendar is 1970, using the
unix epoch as a starting point. So, the 1st Hærfest 0 corresponds to 23 Setpember
1970.

The leap years are calculated according to the Romme rule, which uses the
4-100-400 rule from the Gregorian calendar (a leap day becoming an extra 6th
Wending day).

## Hwý?

I appreciate the political impulse behind the French Republican calendar, as well
as its more rational system (12 months of 30 days, plus 5/6 celebratory days
at the end of the year). However, I like the aesthetics of Old English more than
the original french names for the months, so I've attempted to rougly translate
or otherwise approximate the Old English equivalents.

## Translation

|                   | French         | Old English | Translation                 |
|-------------------|----------------|-------------|-----------------------------|
| **Autumn**        | Vendémiaire    | Hærfest     | Harvest, autumn             |
|                   | Brumaire       | Mist        | Mist, fog                   |
|                   | Frimaire       | Forst       | Frost                       |
| **Winter**        | Nivôse         | Snáw        | Snow                        |
|                   | Pluviôse       | Reg         | Rain                        |
|                   | Ventôse        | Wind        | Wind                        |
| **Spring**        | Germinal       | Sǽd         | Seed                        |
|                   | Floréal        | Blóstm      | Blossom, flower             |
|                   | Prairial       | Mǽdland     | Meadow-land                 |
| **Summer**        | Messidor       | Ríp         | Reaping, harvest            |
|                   | Thermidor      | Hát         | Heat                        |
|                   | Fructidor      | Wæstm       | Growth, produce, fruit      |
| **Complementary** | Sansculottides | Wending     | A turning round, revolution |
