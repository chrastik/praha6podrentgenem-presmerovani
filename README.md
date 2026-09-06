# Přesměrování praha6podrentgenem.chrast.eu

Původní adresa webu [Praha 6 pod rentgenem](https://praha6podrentgenem.cz/).
Tenhle repozitář neobsahuje nic než přesměrovací stránku — web sám žije
v repozitáři [`praha6-pod-rentgenem`](https://github.com/chrastik/praha6-pod-rentgenem)
a běží na doméně **praha6podrentgenem.cz**.

`index.html` i `404.html` přesměrují na novou doménu se zachováním cesty
i hash routy, takže staré odkazy typu `.../#/zakazky?rok=2024` dorazí na správné místo.
