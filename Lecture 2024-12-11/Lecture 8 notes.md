<div style="text-align: right;">
# Basics of cybersecurity principles and concepts. Threat vectors and types of cyberattacks. Security policies and best practices

Medžiaga parengta remiantis:

* Mike Chapple. CC Certified in Cybersecurity Study Guide (Sybex Study Guide).John Wiley & Sons, 2023, 256 pages
* Charles J. Brooks, Christopher Grow, Philip A. Craig, Jr., Donald Shor. Cybersecurity Essentials. John Wiley & Sons, 2018. 784 pages
* Kibernetinis saugumas ir verslas. Ką turėtų žinoti kiekvienas įmonės vadovas. NKSC prie KAM, 2020 (https://www.nksc.lt/doc/Kibernetinio_saugumo_vadovas_verslui_2020.pdf)
* Claudio Novelli, Federico Casolari, Philipp Hacker, Giorgio Spedicato, Luciano Floridi, Generative AI in EU law: Liability, privacy, intellectual property, and cybersecurity,
Computer Law & Security Review, Volume 55, 2024, 106066, ISSN 0267-3649, https://doi.org/10.1016/j.clsr.2024.106066.
* Iqbal H. Sarker, Helge Janicke, Ahmad Mohsin, Asif Gill, Leandros Maglaras, Explainable AI for cybersecurity automation, intelligence and trustworthiness in digital twin: Methods, taxonomy, challenges and prospects,
ICT Express, Volume 10, Issue 4, 2024, Pages 935-958, ISSN 2405-9595, https://doi.org/10.1016/j.icte.2024.05.007.


### Paskaitos aprašas:

Konfidencialumas (angl. confidentiality) užtikrina, kad tik įgalioti asmenys turėtų prieigą prie informacijos ir išteklių. Didelė dalis saugumo specialistų būtent ir dirba prie šios srities. Konfidencialumo rizikos apima šias sritis: ​
* Šnipinėjimas/šniukštinėjimas (angl. snooping). Asmuo, vaikštinėja po biurą ar kitas patalpas ir tiesiog stebi, kokią informaciją gali surinkti. Tai dažnai nutinka, kai žmonės palieka dokumentus, įrenginius ar kitus jautrius duomenis neapsaugotus.​
* Šiukšlių naršymo (angl. dumpster diving) atakos taip pat siekia rasti jautrią informaciją, tačiau užpuolikas nevaikšto po biurą. Vietoje to, jie peržiūri šiukšles, ieškodamas svarbių dokumentų, kuriuos darbuotojas galėjo išmesti į šiukšliadėžę.​
* Pasiklausymo atakos (angl. Eavesdroping) gali būti tiek fizinės, tiek elektroninės. Fizinės pasiklausymo atakos metu užpuolikas tiesiog užima poziciją, kurioje gali girdėti pokalbius (valgykloje, koridoriuje ir pan.) ir klausosi jautrios informacijos. Elektroninės pasiklausymo atakos dar vadinamos „prisijungimu prie linijos“ (angl. wiretapping). Jos vyksta, kai užpuolikas įsilaužia į tinklą ir stebi duomenų srautą, kuris perduodamas elektroniniu būdu biure. Geriausias būdas apsisaugoti nuo elektroninių pasiklausymo atakų – naudoti šifravimą.
* Paskutinis konfidencialumo pažeidimo tipas yra socialinės inžinerijos atakos (angl. social engineering). Šių atakų metu užpuolikas naudoja psichologinius triukus, kad įtikintų darbuotoją perduoti jautrią informaciją ar suteikti prieigą prie vidinių sistemų. Užpuolikai gali apsimesti vykdantys skubią užduotį aukšto rango vadovo pavedimu, IT techniku arba išsiųsti apgaulingą el. laišką (phishing).​ Apsisaugoti nuo socialinės inžinerijos atakų yra sudėtinga. Jūsų sistema gali būti geriausiai apsaugota žvelgiant iš technologinės pusės, tačiau jei silpnoji grandis yra žmogus - jos nepadės. Geriausia gynyba prieš tokio tipo atakas – darbuotojų švietimas, mokant juos atpažinti socialinės inžinerijos pavojus, ir jų įgalinimas imtis veiksmų, kai įtariama, kad vykdoma ataka.

Vientisumas (angl. Integrity) -  užtikrinimas, kad informacija ir duomenys yra teisingi, nėra atsitiktinai ar neteisėtai pakeisti ir sunaikinti. Neteisėtas informacijos modifikavimas įvyksta, kai užpuolikas gauna prieigą prie sistemos ir atlieka pakeitimus, kurie pažeidžia saugumo politiką. Tai gali būti išorinė tiek išorinė, tiek vidinė ataka. Geriausias būdas apsisaugoti nuo tokio tipo vientisumo pažeidimų – laikytis mažiausių privilegijų principo (The principle of least privilege (PoLP)). Organizacijos turėtų kruopščiai apsvarstyti, kokias teises kiekvienam darbuotojui būtina turėti atliekant savo darbą, ir apriboti darbuotojų prieigą iki mažiausio įmanomo teisių rinkinio.​
* Apsimetinėjimo (angl. Impersonation) atakos. Šių atakų metu užpuolikas apsimeta kitu asmeniu, nei yra iš tikrųjų. Jie gali apsimesti vadovu, vadovybės nariu ar IT specialistu, kad įtikintų ką nors pakeisti duomenis sistemoje. Tai yra socialinės inžinerijos atakų forma. Detaliau: https://www.upguard.com/blog/impersonation-attack
* Tarpininko atakos (Man-in-the-Middle, MitM)​. Kartais Impersonation atakos būna elektroninės. Tarpininko atakos metu užpuolikas perima tinklo srautą, kai vartotojas jungiasi prie sistemos, ir apsimeta ta sistema. Užpuolikas tampa tarpininku tarp vartotojo ir sistemos, perduodamas informaciją tarp jų ir stebėdamas viską, kas vyksta. Šios atakos metu užpuolikas gali pavogti vartotojo slaptažodį ir vėliau pats prisijungti prie sistemos.​ Detaliau: https://www.ibm.com/think/topics/man-in-the-middle
* Replay Attacks. Šios atakos metu užpuolikas nesikiša į komunikaciją, tačiau randa būdą stebėti, kaip teisėtas vartotojas jungiasi prie sistemos. Jis užfiksuoja informaciją, naudojamą prisijungti, ir vėliau ją pakartoja tinkle, kad pats galėtų gauti prieigą.​ Detaliau: https://chain.link/education-hub/replay-attack
​
Geriausias būdas apsisaugoti nuo MitM ir Replay atakų yra šifravimo naudojimas, siekiant apsaugoti komunikaciją. Pavyzdžiui, tinklalapio srautas gali naudoti Transport Layer Security (TLS) protokolą, kuris neleidžia pasiklausytojams stebėti tinklo srauto.

Prieinamumas (angl. Availability) – užtikrinimas, kad visada yra prieiga prie tam tikros informacijos, duomenų bazės ar kitų elektroninių paslaugų.
* Denial-of-Service Atakos (DoS)​. Įvyksta, kai piktavališkas asmuo užtvindo sistemą didžiuliu tinklo srautu. Tikslas – siųsti tiek daug užklausų serveriui, kad jis nebegalėtų atsakyti į teisėtų vartotojų užklausas.​ Norint apsisaugoti - naudoti ugniasienes, kurios blokuoja neteisėtas užklausas.​ Bendradarbiauti su interneto paslaugų teikėju, kad šios atakos būtų blokuojamos dar prieš pasiekiant jūsų tinklą.​ Detaliau: https://www.microsoft.com/en-us/security/business/security-101/what-is-a-ddos-attack
* Elektros tiekimo sutrikimai gali įvykti tiek lokaliai, tiek regioniniu mastu dėl įvairių priežasčių:​ padidėjusi elektros paklausa gali perkrauti tinklą, gamtinės stichijos gali sutrikdyti paslaugų teikimą, kiti veiksniai. Esmė, kad jie visi trukdo naudotis sistemomis. Norint apsisaugoti nuo šio tipo sutrikimo reikia naudoti atsarginius elektros šaltinius ir rezervinius generatorius, kurie tiektų energiją sistemoms, kai nėra pagrindinio tiekimo.​
* Aparatūros gedimai. Serverių, kietųjų diskų, tinklo įrangos gedimai, galintys sutrikdyti prieigą prie informacijos. Projektuoti sistemas taip, kad sugedus vienam komponentui, kitas galėtų perimti jo funkciją.​ Detaliau: https://www.vpnunlimited.com/help/cybersecurity/hardware-failure
* Equipment Destruction Attack. Kartais įranga būna tiesiog sunaikinama. Tai gali būti tyčinis ar atsitiktinis fizinis pažeidimas arba didesnės nelaimės, tokios kaip gaisras ar uraganas, rezultatas.​ Nuo mažo masto sunaikinimo apsisaugoti galima naudojant perteklines sistemas.​ Norint apsisaugoti nuo didelio masto nelaimių, reikėtų turėti atsarginius duomenų centrus atokiose vietose arba naudoti debesijos infrastruktūrą.​ Detaliau: https://www.cybertraining365.com/cybertraining/Topics/Equipment_destruction_attack
* Paslaugų tiekimo sutrikimai gali kilti dėl programavimo klaidų, pagrindinės įrangos gedimų ar kitų priežasčių. Tokie sutrikimai trukdo vartotojams pasiekti sistemas ir informaciją, todėl yra prieinamumo problema.​ Projektuoti sistemas, kurios būtų atsparios klaidoms ir aparatinės įrangos gedimams.​

Vienas svarbiausių dalykų, kuriuos atliekate, yra užtikrinti, kad tik įgalioti asmenys gautų prieigą prie jūsų saugomos informacijos, sistemų ir tinklų. Tam naudojate prieigos kontrolės mechanizmus.​
* Identifikacija (angl. Identification). Asmuo, bandantis gauti prieigą, šiame etape nepateikia jokio įrodymo; jis tiesiog pateikia teiginį. Svarbu prisiminti, kad identifikacijos etapas yra tik pareiškimas, ir vartotojas tikrai gali pateikti klaidingą teiginį.​
* Įrodymai atsiranda antrajame proceso etape – autentifikacijoje (angl. Authentification). Autentifikacijos etape asmuo įrodo savo tapatybę taip, kad tai patenkintų prieigos kontrolės sistemos reikalavimus. Pavyzdžiui, biuro pastate apsaugos darbuotojas greičiausiai norėtų pamatyti asmens vairuotojo pažymėjimą, kad patvirtintų to asmens tapatybę​.
* Tačiau vien tapatybės įrodymo nepakanka, kad gautumėte prieigą prie sistemos. Prieigos kontrolės sistema taip pat turi būti įsitikinusi, kad turite teisę pasiekti sistemą. Tai yra trečiasis prieigos kontrolės proceso etapas – autorizacija (angl. Authorization). 
* Be identifikacijos, autentifikacijos ir autorizacijos, prieigos kontrolės sistemos taip pat turi apskaitos (angl. Accounting) funkcionalumą, leidžiantį administratoriams stebėti vartotojų veiklą ir ją atkurti iš žurnalų. Biuro pastato pavyzdyje apsaugos darbuotojas gali užrašyti asmens apsilankymą pastate lankytojų registracijos žurnale.​ Detaliau: https://www.proof.com/blog/what-is-identification-authentication-and-authorization

​
**Attack and threat vectors​**

* Atakos vektorius yra metodas, naudojamas neteisėtai prieigai prie tinklo ar kompiuterinės sistemos gauti.​
* Atakos paviršius – tai visų atakos vektorių, kuriuos užpuolikas gali panaudoti manipuliuodamas tinklu ar kompiuterine sistema arba išgaudamas duomenis, visuma.​
* Grėsmės vektorius gali būti vartojamas kaip sinonimas su „atakos vektoriumi“ ir paprastai apibūdina galimus būdus, kuriais įsilaužėlis gali gauti prieigą prie duomenų ar kitos konfidencialios informacijos.​ Detaliau: https://www.upguard.com/blog/attack-vector
</div> 
