# [Petr Paleta - Co programatory ve skole neuci](http://www.martinus.sk/?uItem=16013)

**[@danielharcek](https://twitter.com/danielharcek)**

> Pravidlo prvni
> 
> Kvalita odbornych pracovniku je pro uspech projektu rozhodujici

Autor pri pisani knihy cerpal z vlastnej praxe. Text povodne vznikal ako dokumentacia chyb ci uz programatorskych alebo manazerskych, ktorych sa dopustil, alebo s ktorymi sa stretol. Ma sluzit ako prirucka na predchadzanie tymto chybam. Kniha je mixom technologickych (teoria) a manazerskych tem. Takto koncipovana je vhodna pre vyvojarov - zvlast juniorskych, veducich timov a manazerov sw projektov, ktory sa este s komplexnym nahladom na problematiku tvorby SW intenzivne nestretali. Velmi cennou moze byt pre juniorskych vyvojarov, ktori sa s podobnou literaturou este nestretli. Pripomina mi Dokonaly Kod a Programator Pragmatik, pricom v porovnani s oboma je celistvejsia a kompaktnejsia. Nevyhnutnou daňou za celistvost v rozumnom pocte stran a citatelnost je ze text ide skor do sirky ako do hlbky a je pomerne “soft” Verim ze v dobe vydania, roku 2003 bola jednym z najprinosnejsich priruciek pre oblast vyvoja sw.

Kniha je delena na 10 casti ktore obsahuju 43 kapitol. Vacsina kodu je uvedena v .NET / C#, aj suvisiace nastroje a postupy adresuju tuto platformu. Vzhladom na datum publikacie, je vsak velka cast z nich neaktualna. 

V prvej casti, __Tajemstvi Tvorby Softwaru__, popisuje specifika vyvoja software aj pomocou uvedenia paralel k inym profesiam. Zoznam vseobecnych pravidiel pre uspesny vyvoj software sa tieto specifika snazi zcelit do paradigmy, ktora tvori ramec uspesneho vedenia projektov. V strucnosti su nimi akceptacia chyb ako nevyhnutneho produktu vyvoja, zavedenie opatreni na ich vcasne odchytenie a eliminovanie, vysoka odbornost, potreba neustaleho vzdelavania, formovanie malych nezavislych timov, nutnost podpory iniciativy zdola a mozno trocha kontroverzny nazor ze v dobe projektu sa programatori maju venovat svojej praci co najviac (nadcasy). Tato cast obsahuje aj typicke problemy pri vyvoji sw a ich priciny.

Cast druha, __Jak psat a nepsat program__, pomerne podrobne rozobera pravidla ako pisat kod, ak ste este necitali ziaden code stile guide, odporucam. Autor kladie velky doraz na citatelnost kodu a pohrava sa s myslienkou ze je nadradena bezchybovosti a kompletnosti (funkcnej) kodu. V kratkosti sa dotkne aj spravy pamate, programatorskych trikov a vstupnych dat.

__Proc Dochazi k Chybam__ strucne prechadza otazky bezpecnosti, quality assurance a programatorske slabosti. Tato cast ma prilis nezaujala, pre novacikov vsak moze byt prinosna. 

Stvrta cast __Co s Chybami__ nadvazuje na rozoberanu problematiku chyb. Autor hrubo kategorizuje typicke priciny a zdroje chyb, nezabuda aj na “_chyby mimo pocitac vyvojare_”, co je este stale este castym javom. Spomina aj code review, ktora sa v nasom priestore az dnes stava beznejsou praxou v ramci agilnych metod vyvoja.

Kniha pokracuje castou __Testovani aplikacie__, kde je nacrtnute aj automatizovane testovanie. Chyba jednotkove testovanie, ktore je dnes uz tak povediac standardom. Nacrtnuty je proces interneho testovania, idealne automatizovaneho po kazdom builde, s co najcastejsim vytvaranim buildov. Okrajovo je spomenuty aj spravny popis chyb, co je opat casty kamen urazu. Nespravny / povrchny popis chyby vedie tak ako zla specifikacia s najvacsou pravdepodnostou k neefektivne stravenemu casu a moznej frustracii vyvojara :). Cast je pomyselnym zavrsenim predchadzajucich kapitol, a popisuje koncept skusobnej prevadzky a prevadzky u zakaznika. Orientovana je skor na b2b aplikacie, ale koncept dev / staging / production je prakticky pouzitelny pri mnozstve typov aplikacii. 

__Zahajeni projektu__ je prvou z casti “projekt managerskych” resp. “analytickych”. Autor popisuje rizika a vyhody roznych typov projektov (interny, volny trh, na zakazku, subdodavka komplexneho riesenia). Velmi pragmaticky sa stavia over-deliveringu. Aspekt uvedomenia si ekonomiky projektu je jednym z leitmotivov knihy. Dolezitou castou je aj popis komunikacie so zakaznikom a varovanie pred typickymi obchodnymi chybami. Kapitoly analyza, projektovy plan a ekonomicka stranka projektu vyborne posluzia vyvojarom, ktori sa rozhodli osamostatnit a ist s kozou na trh, ci uz ako jednotlivec alebo skupina. Tuto cast uzatvara perlicka zo statno-obstaravacieho folkloru typickeho pre nas geograficky priestor.

Na cast __Lidske zdroje a komunikace__ som sa tesil, kedze je to moja oblubena tema. Psychologia timu a problematicke typy su spomenute sice kratko ale vystizne. Nezabuda upozornit, ze s velkostou timu, stupaju poziadavky na jeho riadenie (narast komunikacnych kanalov), no varuje aby aj male timy nezabudali na dokumentaciu. Text popisuje aj jednotlive role vyvojoveho timu a kriteria ich vyberu. Komunikacia s okolim aj vnutro firemna nasleduje po strucnom popise vedenia timu. Zvlast komunikacia so zakaznikom navyse v pripade problemov byva znova castym zdrojom problemov. Velmi pragmaticky, povedal by som az bez idealov je vypichnuta komunikacia s manazermi :).

Osma cast __Metodiky a technologie__ je ciastocne viac technicka. Spomenute su aj agilne metodiky, tu vsak text treba doplnit studiom sucasneho stavu. Struktura aplikacie popisuje dnes uz klasicky sposob vrstvenia monolytickeho kodu klient-server aplikacie. Popisane je aj vizualne modelovanie v standarde UML a nacrtnute su rizika pouzitia novych technologii a kniznic tretich stran, predovsetkym z pohladu kritickych aplikacii ako napr. v bankach. 

Predposledna cast, __Architektura aplikace__, velmi spravne popisuje, ze vykonnost aplikacie nie je mozne merat cez jednotlive sucasti ale ako celok, popisuje kriteria vykonnosti a zakladne strategie skalovania. Navrh uzivatelskych rozhrani popisuje zakladne otazky user experience. Prevadzka databaz a Protokoly a rozhrani opat velmi strucne popisuju typicke problemy tych - danych casti.

__Kdyz projekt bezi__ upozornuje na niektore best practices pri vyvoji, ako napr. pozor na “_skoro dokoncene_” ulohy alebo doraz castu komunikaciu so zakaznikom. Nasadenie a udrzba velmi strucne popisuje zivot aplikacie u zakaznika. Dobra spolupraca so spravcom systemu nie je opomenuta. Nakoniec autor pojednava o tom, ze vsetky pravidla treba zavadzat na zaklade realnej potreby a pochopenia situacie, a zdoraznuje potrebu diskusie a kompromisov.

Uplnym zaverom knihy je ukazkovy test pre programatora, konceptualne stale pouzitelny. 
Jednotlive casti su doplnene pribehmi autora z praxe, ktore su casto zabavnym osviezenim teorie.
