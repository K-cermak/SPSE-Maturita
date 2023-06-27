# Webové aplikace

### Všeobecné informace o ústních zkouškách můžeš nalézt [zde](../FaQ/USTNI.md).

### Jak probíhá výběr otázky a příprava?
- Nejprve vstup do učebny. Neťukej, jen se posaď na některou z krajních židlí (jsou vedle dveří) a počkej než tě učitel (nejspíše třídní) vyzve (většinou na tebe pokývne), ať si jdeš vylosovat otázku. Vhodné je do třídy dorazit 2-3 minuty před začátkem přípravy.
- Pro otázku jdi vždy zásadně předem (to znamená kolem tabule). Nechoď za učitelské stoly, učitelé to nemají rádi (ani když jsi první v daný den a je tam ještě volno).
- Po vylosování žetonu tě učitel posadí k volnému počítači (ty jsou u oken). Na těchto počítačich jednak běží nějaké scuffed scripty (asi hlídají co kdo dělá, takže ne, Copilota tam fakt nenastavíš..). Škola má také udělanou takovou speciální (rozuměj ještě víc scuffed) aplikaci, kde jsou jednotlivé okýnka pro každou otázku. U okýnka (otázky) je k dispozici jednak PDF zadání a případně odkaz přímo na stránku, ve které máš pracovat (to jsou vlastně všechny až na SQL otázky).
- Tato školní aplikace běží na localhostu a jednotlivé otázky jsou vlastně udělané v podsložkách. Ve VS Code je pak otevřena složka s localhostem a v jednotlivých podsložkách jsou pak umístěny základní soubory pro danou otázku.
    - Pro příklad: Máš otázku na editaci dat, ve VS Code je otevřena složka localhostu, v okýnku 15 na hlavním webu klikneš na PDF zadání a dále otevřeš samotnou podstránku. Ve VS Code si otevřeš danou podsložku (v tomto případě 15) a v ni už bude například připravený PDO connection a HTML stránka.

<br>

- Pokud si vylosuješ Regex, dej si pozor na to, jestli ho máš psát pro PHP nebo JavaScript.. Prý se to pár lidem prohodilo a pak to psali v jiném jazyku (sice nechápu jak, ale pokud má člověk nervy, tak se to stát asi může).
- Pokud si vylosuješ otázku na SQL, klidně to celé můžeš naklikat v phpMyAdmin a jen zkopírovat příkazy do Notepadu / volného souboru ve VS Code. Je ale dobré pak při zkoušce popsat, co vlastně ten příkaz dělá.
- Během zkoušky máš taktéž k dispozici Zeal. Pokud víš, jak se v něm orientovat a co kde hledat, je to strašná výhoda, takže určitě je vhodné se s ním seznámit dřív než na potítku..

<br>

### Musím používat PDO a phpMyAdmin? Co když nemám rád VS Code?
- Údajně všechny databázové připojení jsou napsané jak pro PDO, tak pro mysqli. Je ale lepší se naučit spíš PDO, protože ti učitelé spíše v případě problémů pak poradí s ním, než s mysqli.
- Z hlavní stránky je dostupný jak phpMyAdmin, tak i Adminer (pokud bys ho měl jakýkoliv důvod použít místo phpMyAdminu...).
- Jestli můžeš použít jiné IDE než VS Code netuším, ale spíše pochybuji. Zase nepíšeš tady celý projekt, ale pár řádku, takže to snad přežiješ.. 

<br>

### Jak probíhá samotná zkouška?
- Po uplynutí 30 minut času na přípravu následuje 15 minutová zkouška. Učitel zapne projektor a nastaví na něj tvojí obrazovku (to znamená, že ty se nikam nepřemisťuješ, zůstáváš na svém místě).
- Během zkoušky bys měl hlavně rozebrat to, co jsi udělal. Nejprve se tě pravděpodobně bude ptát přísedící (zkoušející vysvětluje zadání tomu, co si teď losoval žeton).
- Následně se tě začne ptát i zkoušející. Většinu času budou řešit tvůj napsaný kód, poté se případně budou ptát i na další otázky.
- Během celého zkoušení můžeš používat Zeal. Pokud ti už na přípravě zbývá nějaký čas, může být dobré si otevřít více tabů v Zealu s tématy, na které se tě můžou ptát, ať to pak zbytečně nehledáš.
- Pokud se v tématu orientuješ a je vidět, že vcelku všechno víš, je i dost velká šance, že tě pustí dřív (mě pustili po 5 minutách, protože jsem měl fakt strašně primitivní otázku a na všechno jsem +- odpověděl).

<br>

### Mám k dispozici papír či tužku na své poznámky?
- Ano, v lavici je k dispozici papír a obyčejná tužka. Pokud nechceš psát poznámky tužkou, doporučuji si vzít vlastní propisku či fix (je dobré pro jistotu o tom říct učiteli). Papír po konci zkoušky odevzdáváš, během celé zkoušky ho ovšem můžeš používat.

<br>

### O kolik je zkouška těžší oproti zkoušení s BAJ?
- Dle slov BAJ jsou příklady u maturitní zkoušky o něco jednodušší - například v otázce 21 - Návrh databáze (tu jsem měl já) je u zkoušení BAJ nutné vytvořit 5 tabulek, u maturit to byly jen tabulky 2. Navíc máš i víc času na přípravu (místo 15-20 minut máš 30 minut).
- Samozřejmě záleží na druhu otázky, ale reálně to moje zadání jsem měl udělané za 3 minuty, protože šlo jen o vytvoření 2 tabulek v phpMyAdminu a jejich propojení.

<br>

### Co když z pratického příkladu nebudu mít nic a jen budu vědět teorii?
- Pokud z praktického příkladu nebudeš mít vůbec nic či jen část, tak je stále dobrá šance, že dostaneš 3 / 4, pokud řekneš něco z teorie.

<br>

### Je BAJ v pohodě?
- No... Co se týče známkování, přišlo mi, že hodnotil dost mírně a tu 4 dal i tomu, kdo toho vyřešeného moc neměl.. Horší už jsou jeho otázky, snaží se dost slovíčkařit, ptá se strašně obecně a na dost specifické věci.
- Mě se třeba ptal na rozdíl mezi DECIMAL a FLOAT či jak se liší MyISAM a InnoDB. Možná ale dobré řešení je mu na jeho otázky odpovědět taky obecně - například že rozdíl mezi DECIMAL a FLOAT je v tom, jak uchovávají svoji hodnotu, rozdíl mezi MyISAM a InnoDB je v tom, jak ukládají své data (bude mu to stačit a nemusíš to někde hledat nebo si vzpomínat na přesné rozdíly).  

<br>

### Jak jsou na tom ostatní učitelé (BAT / RES / KAS)?
- BAT se mě fakt ptal na základní otázky a příšlo mi, že to směruje více do praktické stránky, ale zase je pravda, že naši třídu měl vcelku rád, netuším, jak to může být jinde, ale všeobecně bych řekl, že bude v pohodě.
- RES tento rok u maturity (až na opakující) nikdo neměl, takže nedokážu posoudit.
- KAS prý fakt hodně pomáhal u té praktické části, že prý z toho BAJ chytal mírně nervy, ale u zkoušky jsem nebyl, tohle mám z doslechu, takže přesně nevím..