# uzdevums
Json dati failā db.json sastāv no transportlīdzekļu saraksta, kas norīkoti uz tehniskās apskates(TA) līnijām apskašu laukumā.
Viena ieraksta rinda sastāv no 5 laukiem, kur:
id - Ieraksta identifikators;                            
numurs - norīkotās līnijas numurs;
rn - transportlīdzekļa numurs(TL);
datums - datums, kad norīkots līnijā;
s_datums - datums, kad pabeigta tehniskā apskate un TL ir izbraucis no TA laukuma.

Uzdevums ir izveidot vizuālu web lapu, kurā tiek atrādīti norīkotie transportlīdzekļi TA laukumā, un to sadalījums pa līnijām.
Norādot datumu un laiku jāatfiltrē tie ieraksti, kuri ir pa vidu starp <datums> un <s-datums>. 
Ja lauks <s-datums> ir null, tad tāds TL vēl ir TA laukumā, jāuzskata ka vērtība ir lielāka par norādīto datumu un laiku. 
Vienā līnijā esošie TL, jāsakārto pieaugoši pēc ID vērtības.
Apskašu līniju skaits ir 12
Datu atjaunošanai jānotiek bez lapas pārlādes. 
Uzdevuma izpildei vēlamā tehnoloģija ir React Js, Angular 8, vai Vue js.
