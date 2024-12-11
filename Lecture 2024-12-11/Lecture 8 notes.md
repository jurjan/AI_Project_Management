# Basics of cybersecurity principles and concepts. Threat vectors and types of cyberattacks. Security policies and best practices

Medžiaga parengta remiantis:

* Mike Chapple. CC Certified in Cybersecurity Study Guide (Sybex Study Guide).John Wiley & Sons, 2023, 256 pages
* Charles J. Brooks, Christopher Grow, Philip A. Craig, Jr., Donald Shor. Cybersecurity Essentials. John Wiley & Sons, 2018. 784 pages
* Kibernetinis saugumas ir verslas. Ką turėtų žinoti kiekvienas įmonės vadovas. NKSC prie KAM, 2020 (https://www.nksc.lt/doc/Kibernetinio_saugumo_vadovas_verslui_2020.pdf)
* Claudio Novelli, Federico Casolari, Philipp Hacker, Giorgio Spedicato, Luciano Floridi, Generative AI in EU law: Liability, privacy, intellectual property, and cybersecurity,
Computer Law & Security Review, Volume 55, 2024, 106066, ISSN 0267-3649, https://doi.org/10.1016/j.clsr.2024.106066.
* Iqbal H. Sarker, Helge Janicke, Ahmad Mohsin, Asif Gill, Leandros Maglaras, Explainable AI for cybersecurity automation, intelligence and trustworthiness in digital twin: Methods, taxonomy, challenges and prospects,
ICT Express, Volume 10, Issue 4, 2024, Pages 935-958, ISSN 2405-9595, https://doi.org/10.1016/j.icte.2024.05.007.
* https://www.researchgate.net/publication/380359955_Enhancing_Cybersecurity_Resilience_at_the_DOST-CAR_Investigating_the_Human_Factors_Leading_to_Social_Engineering_Attacks


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
**Atakų ir grėsmių vektoriai**

* Atakos vektorius yra metodas, naudojamas neteisėtai prieigai prie tinklo ar kompiuterinės sistemos gauti.​
* Atakos paviršius – tai visų atakos vektorių, kuriuos užpuolikas gali panaudoti manipuliuodamas tinklu ar kompiuterine sistema arba išgaudamas duomenis, visuma.​
* Grėsmės vektorius gali būti vartojamas kaip sinonimas su „atakos vektoriumi“ ir paprastai apibūdina galimus būdus, kuriais įsilaužėlis gali gauti prieigą prie duomenų ar kitos konfidencialios informacijos.​ Detaliau: https://www.upguard.com/blog/attack-vector

Kibernetiniai nusikaltėliai išnaudoja atakos vektorius, kad pradėtų kibernetines atakas ir įterptų kenksmingus duomenų paketus (angl. payloads).​ Atakos vektoriai gali būti skaitmeniniai, pavyzdžiui, programinės įrangos pažeidžiamumas, arba žmogiškasis - darbuotojas, kurį galima paveikti, kad jis atskleistų privačius prieigos duomenis.​ Trečiųjų šalių tiekėjai yra kritiniai atakos vektoriai, nes jie turi prieigą prie privačių duomenų, priklausančių kiekvienam verslui, su kuriuo jie bendradarbiauja. Dėl to, kai tiekėjas yra pažeidžiamas, dažnai pažeidžiami ir visi jo klientai.​ Toks kibernetinis išpuolis vadinamas tiekimo grandinės ataka (angl. supply chain attack), ir dėl savo efektyvumo jis greitai tampa viena mėgstamiausių kibernetinių nusikaltėlių strategijų. Detaliau: https://www.fortinet.com/resources/cyberglossary/supply-chain-attacks

Socialinės inžinerijos atakos naudoja psichologinius triukus, siekiant manipuliuoti žmonėmis, kad šie atliktų tam tikrą veiksmą arba atskleistų jautrią informaciją, kuri pažeidžia organizacijos saugumą.​ Pavyzdžiui, užpuolikas, apsimetęs pagalbos tarnybos techniku, gali naudoti socialinę inžineriją, kad apgautų vartotoją ir priverstų jį atskleisti savo slaptažodį telefonu.​ Tai yra vienas sunkiausių apsisaugoti atakos tipų.​
* Autoritetas ir pasitikėjimas​ (angl. Authority and trust​). Nemažai psichologinių eksperimentų parodė, kad žmonės yra linkę klausyti ir paklusti asmeniui, kuris sugeba perteikti autoriteto įvaizdį. ​(Galite paskaityti Kevin Mitnick knygą The Art of Intrusion., labai įdomi, rekomenduoju)
* Įbauginimas​ (angl. Intimidation). Antra priežastis, kodėl socialinė inžinerija veikia, yra įbauginimas. Tai tiesiog prievartinis spaudimas, kai žmonės bauginami ir grasinama, kad jiems arba jų organizacijai nutiks kažkas blogo, jei jie nepadarys to, ko iš jų reikalaujama.​
* Sutarimas ir socialinis įrodymas​ (angl. Consensus and Social Proof). Trečioji socialinės inžinerijos taktika yra sutarimas ir socialinis įrodymas. Kai žmonės nežino, kaip elgtis tam tikroje situacijoje, jie dažnai stebi kitų elgesį ir seka jų pavyzdžiu. Tai vadinama bandos mentalitetu.​ Pavyzdžiui, tai nutinka, kai žmogus gatvėje užpuolamas, tačiau niekas neiškviečia pagalbos, nes kiekvienas stebi kitų reakciją ir laukia, kol kažkas imsis veiksmų.​
* Trūkumas (angl. Scarcity)​. Ketvirtoji taktika yra trūkumas: žmonių įtikinimas, kad jei jie neveiks greitai, praras galimybę arba kažką svarbaus. Socialinės inžinerijos specialistas gali panaudoti trūkumo taktiką, kad apgautų ką nors, priversdamas juos leisti įdiegti įrangą biure. Pavyzdžiui, užpuolikas gali pasirodyti su Wi-Fi maršrutizatoriumi ir teigti, kad jie diegia naujausią Wi-Fi technologiją kaimyniniuose biuruose ir jiems liko vienas papildomas maršrutizatorius. Jei biuro darbuotojai pageidauja, jie gali jį įdiegti čia.​ Jei darbuotojai sutinka, jie mano, kad gauna ankstyvą prieigą prie naujos technologijos, tuo tarpu įsilaužėlis įsitvirtina tinkle ir gauna prieigą.​
* Skuba (angl. Urgency)​. Naudodamas šią taktiką, įsilaužėlis sukuria situaciją, kurioje žmonės jaučia spaudimą veikti greitai, nes laikas baigiasi.​
* Familiarumas ir simpatija (angl. Familiarity and Liking)​. Paskutinė taktika yra paprasta: familiarumas ir simpatija. Žmonės yra linkę sakyti „taip“ tam, kuris jiems patinka. Socialinės inžinerijos specialistai naudoja pataikavimą, melagingus komplimentus ir suklastotus santykius, kad pelnytų taikinio palankumą ir paveiktų jų veiksmus. Geriausias būdas apsaugoti organizaciją nuo socialinės inžinerijos atakų – vartotojų švietimas. Visi organizacijos nariai turi suprasti, kad socialinės inžinerijos specialistai naudoja šias taktikas, siekdami gauti jautrią informaciją, ir būti budrūs dėl pašaliečių, bandančių naudoti šiuos metodus.​

**Kibernetinių atakų tipai**

* Phishing. Socialinės inžinerijos atakų tipas, kai taikinys yra kontaktuojamas el. paštu, telefonu ar trumpąja žinute asmens, apsimetančio teisėtu kolega ar institucija, siekiant apgauti jį ir priversti atskleisti jautrią informaciją, prisijungimo duomenis arba asmeninę identifikuojamą informaciją (PII). Netikros žinutės gali nukreipti vartotojus į kenksmingus tinklalapius, kuriuose slypi virusai ar kenkėjiška programinė įranga (angl. Malware).​ Šių atakų yra daug ir įvairių: https://www.upguard.com/blog/types-of-phishing-attacks

&nbsp;&nbsp;Išsamus straipsnis kaip apsisagoti nuo tokio tipo atakų: https://www.sciencedirect.com/science/article/pii/S0167404823002973

&nbsp;&nbsp;Kaip tai veikia DI Projektus?
&nbsp;&nbsp;* Duomenų nutekėjimas: gali atskleisti mokymosi duomenų rinkinius, kuriuose gali būti jautri arba patentuota informacija.
&nbsp;&nbsp;* Prieiga prie sistemos: pavogti prisijungimo duomenys gali suteikti neteisėtą prieigą prie DI infrastruktūros, tokios kaip debesijos platformos ar modelių diegimo aplinkos.​
&nbsp;&nbsp;* Modelių vagystė: gali sukelti AI modelių, intelektinės nuosavybės ar tyrimų duomenų vagystę.
&nbsp;&nbsp;* Manipuliacija rezultatais: kompromituotos sistemos gali lemti pakeistus arba nepatikimus DI modelių rezultatus

​

​

​

​

​
