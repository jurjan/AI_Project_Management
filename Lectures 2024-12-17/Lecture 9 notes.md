# Adversarial Attacks and Defenses: Adversarial attacks on machine learning models. Defense mechanisms against adversarial attacks. Adversarial robustness and detection techniques

Paskaitos įrašas: https://youtu.be/0uhnGG5c1I4

Literatūra:
* 	John Sotiropoulos. Adversarial AI Attacks, Mitigations, and Defense Strategies: A cybersecurity professional's guide to AI attacks, threat modeling, and securing AI with MLSecOps
* 	Zhao, W.; Alwidian, S.; Mahmoud, Q.H. Adversarial Training Methods for Deep Learning: A Systematic Review. Algorithms 2022, 15, 283. https://doi.org/10.3390/a15080283

* Paskaitos įrašas: https://youtu.be/0uhnGG5c1I4
* Paskaitos skaidrės: https://github.com/jurjan/AI_Project_Management/blob/main/Lectures%202024-12-17/Paskaita9.pdf

## Trumpas paskaitos aprašas

Yra daugybė skirtingų neuroninių tinklų architektūrų. Štai pagrindinės, kurias reiktų žinoti, kalbant apie priešiškas atakas:
* CNN (Konvoliuciniai neuroniniai tinklai): Dažniausiai naudojami vaizdų apdorojimui. Tokie modeliai kaip AlexNet, VGG ir ResNet pasiekė aukščiausius rezultatus ImageNet konkurse.
* RNN (Pasikartojantys neuroniniai tinklai): Plačiai naudojami kalbos modeliavime ir kalbos atpažinime. Ilgalaikės trumpalaikės atminties (LSTM) tinklai yra populiari RNN rūšis, padedanti išspręsti tradicinių RNN nykstančio gradiento problemą, kuri sulėtina arba sustabdo mokymą. (Daugiau apie nykstantį gradientą - https://lt.eitca.org/artificial-intelligence/eitc-ai-gcml-google-cloud-machine-learning/first-steps-in-machine-learning/deep-neural-networks-and-estimators/what-is-the-vanishing-gradient-problem/)
* Transformatoriai (BERT, GPT):
* LLM (Dideli kalbos modeliai): Jie dažniausiai yra didžiuliai ir priklauso Generatyvinio AI sričiai, kuri apima turinio generavimą – nuo vaizdų ir muzikos iki teksto. Generatyvinio AI pavyzdžiai: Generatyviniai priešiniai tinklai (GANs) - garsūs dėl naudojimo deepfake technologijoje. Variaciniai autokoderiai (VAEs)/ variational autoencoders (VAEs: naudojami kuriant naujas molekules vaistams ar naujus veidus remiantis esamais vaizdais. Egzistuojantys dirbtiniai neuroniniai tinklai (pvz., RNN) taip pat naudojami generatyviniam AI. OpenAI MuseNet, pavyzdžiui, naudoja RNN muzikai kurti ir įvairiems stiliams nuo Mocarto iki „The Beatles“ derinti.
* Saugumas remiasi triada, žinoma kaip CIA, ir gali būti apibūdinamas taip:
  * Konfidencialumas: Duomenų apsauga nuo neleistinos prieigos. Pavyzdžiui, prieigos ribojimas ir jautrių duomenų šifravimas užtikrina, kad juos gali peržiūrėti tik tie, kurie turi teisingą iššifravimo raktą.
  * Integralumas: Duomenų užtikrinimas, kad jie liktų nepakitę saugojimo ar perdavimo metu, išskyrus autorizuotus subjektus. Vienas būdų patikrinti duomenų integralumą – naudoti kriptografines maišos funkcijas.
  * Prieinamumas: Sistemų, duomenų ir išteklių prieinamumo užtikrinimas vartotojams, kai jų reikia. Tokie metodai kaip apkrovos balansavimas ir perteklinės sistemos dažnai naudojami palaikant sistemų prieinamumą esant dideliam poreikiui arba sistemų gedimams.
* Kibernetinio saugumo valdymo karkasai, tokie kaip NIST kibernetinio saugumo karkasas, siūlo standartizuotą požiūrį į kibernetinio saugumo rizikos valdymą. Jis susideda iš penkių pagrindinių funkcijų – Identifikuoti, Apsaugoti, Aptikti, Reaguoti ir Atkurti – ir padeda organizacijoms valdyti kibernetinės saugos rizikos gyvavimo ciklą.
  * https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf
* Kiti karkasai apima:
  * ISACA COBIT (Informacijos ir susijusių technologijų valdymo tikslai),
  * CIS kritinės saugumo kontrolės priemonės,
  * SOC2 (Sistemų ir organizacijų kontrolės 2),
  * FedRAMP (Federalinės rizikos ir autorizacijos valdymo programa),
  * PCI DSS (Mokėjimo kortelių pramonės duomenų saugumo standartas).
* Grėsmių modeliavimas yra struktūruotas metodas, naudojamas potencialioms grėsmėms sistemoje nustatyti, prioritetizuoti ir valdyti. Tai dažnai yra bendradarbiavimo reikalaujantis procesas, kuris prasideda nuo kritinių išteklių, procesų ir duomenų srautų identifikavimo, siekiant nustatyti galimas grėsmes. Svarbus šio proceso elementas yra pasitikėjimo ribų ( trust boundaries) nustatymas, apibrėžiant sritis, kuriomis pasitikima, ir tas, kurios kelia susirūpinimą.
* Yra daug būdų grėsmėms identifikuoti, tačiau išsiskiria du populiarūs metodai:
  * STRIDE metodas apima šešias grėsmių kategorijas:
    * Spoofing (tapatybės klastojimas),
    * Tampering (duomenų ar procesų klastojimas),
    * Repudiation (neatsakomybė),
    * Information Disclosure (informacijos atskleidimas),
    * Denial of Service (paslaugų trikdymas),
    * Elevation of Privilege (teisių eskalavimas).
    * Skaityti čia: https://owasp.org/www-community/Threat_Modeling_Process
* Atakų medžiai: Šie medžiai vizualizuoja kelius, kuriais užpuolikas gali bandyti pažeisti sistemą. Kiekvienas medžio mazgas žymi konkretų veiksmą arba įvykį, prisidedantį prie pagrindinio užpuoliko tikslo.
* MITRE ATT&CK sistema suteikia išsamų standartizuotą terminų žodyną ir įvairias technikas, skirtas grėsmėms identifikuoti naudojant atakų medžius. MITRE ATLAS yra naujesnis MITRE atakų karkasas, skirtas AI sistemoms.
  * https://attack.mitre.org/ (Egzaminui nereikia mokėti)
  * https://attack.mitre.org/
* Kai nustatome grėsmes, priskiriame joms riziką. Riziką dažniausiai vertiname remdamiesi tikimybe, kad grėsmė įvyks, ir poveikiu, kurį sukelia sėkmingas grėsmės išnaudojimas. Šis vertinimas padeda mums prioritetizuoti grėsmes ir jų švelninimo priemones.
* Švelninimo priemonės – tai būdai, kaip ginamės nuo nustatytų grėsmių. Dažniausiai aptariame saugumo kontrolės priemones (angl. security controls), kurios yra skirtos rizikos mažinimui arba neutralizavimui. CIS Benchmarks yra plačiai pripažintas standartinių kontrolės priemonių rinkinys, skirtas platformoms ir infrastruktūrai. OWASP Top 10 ir detalesnis OWASP taikomųjų programų saugumo tikrinimo standartas (ASVS) yra specifiniai standartai, skirti taikomųjų programų saugumui užtikrinti. Saugumo užtikrinimui naudojame saugumo testavimą, ypač penetracinius testus (pen testus), kuriuos atlieka išoriniai testuotojai. Šių testų metu simuliuojamos kibernetinės atakos, siekiant nustatyti pažeidžiamumus dar prieš sistemai pradėjus veikti gyvai. Tačiau saugumo testavimas ir penetraciniai testai kartais atliekami per vėlai vystymo cikle. Čia į pagalbą ateina DevSecOps. Integruojant saugumą į DevOps procesą, įgyvendiname  shift left security (https://www.aquasec.com/cloud-native-academy/devsecops/shift-left-devops/), įtraukiant saugumo tikrinimus daug anksčiau sistemos gyvavimo cikle. Tam naudojamos tokios priemonės kaip:
  * Nuolatinė integracija (CI),
  * Statinė taikomųjų programų saugumo analizė (SAST),
  * Dinaminė taikomųjų programų saugumo analizė (DAST),
  * Pažeidžiamumų skenavimas.
  * Šios priemonės leidžia aptikti pažeidžiamumus tiek kodo bazėje, tiek veikiančioje programoje (angl. application). DevSecOps apima tradicinius taikomųjų programų elementus, tokius kaip kodas, bibliotekos, paketai, konteineriai, aplinkos ir pačios aplikacijos.
* Kuo mažiau programinės įrangos ir paslaugų veikia serveryje, tuo mažiau galimų pažeidžiamumų. Įdiekite tik būtiniausią programinę įrangą. Kurdami konteinerius, apsvarstykite galimybę naudoti distroless OS. Šie atvaizdai sumažina konteinerio turinį iki minimalios reikalingos programų rinkinio, pašalindami OS specifines programas ir paketus. Tai sumažina atakos paviršių ir pagerina saugumą.
* Mūsų pagrindinis tikslas – sumažinti galimą atakos paviršių (attack surface) ir užkirsti kelią įsibrovėliams prieiti prie mūsų išteklių. Ribodami tinklo prieigą ir atskleisdami tik būtinąsias paslaugas, galime sumažinti atakos paviršių ir apsaugoti savo programą nuo neautorizuotos prieigos. Tinklo apsauga yra plati tema, tačiau paprastai ImRecS sistemai galima pritaikyti pagrindines apsaugos priemones:
  * Užkirsti prieigą prie API (išskyrus būsenos tikrinimą),
  * Priversti naudoti HTTPS ir mažiausiai TLS 1.2,
  * Įgyvendinti pagrindinę apsaugą nuo DoS atakų,
  * Pirmasis žingsnis – sugeneruoti Transport Layer Security (TLS) / Secure Socket Layer (SSL) sertifikatą ir raktą. TLS yra itin svarbus šifruojant komunikaciją su mūsų paslaugomis, nes tai padeda išvengti:
    * Spoofing (apsimetinėjimo) atakų,
    * Vidurio žmogaus (man-in-the-middle) atakų.
  * Užtikrinti autentifikaciją, duomenų apsaugą (encryption),
  * Integralumo kontrolė (Integrity control)
  * Modelio šifravimas apsaugo jį nuo klastojimo, tačiau neapsaugo nuo galimybės, kad piktavališkas darbuotojas pakeis jį kitu, suklastotu modeliu, kuris taip pat yra šifruotas.
  * Papildoma saugumo kontrolė – sugeneruoti SHA-256 maišos funkciją modelio failui. Ši maiša veikia kaip modelio „piršto atspaudas“ ir leidžia patikrinti, ar modelis nebuvo pakeistas.
  * Prieigos kontrolė
* Vienas pagrindinių skirtumų tarp DI ir tradicinių sistemų yra tas, kad DI vystymas priklauso nuo duomenų. Be to, DI įveda naujo tipo artefaktus – modelius, kurie yra kritiniai ir jautrūs ištekliai. Šis skirtumas sukuria naujas saugumo rizikas, net ir kūrimo etape.
* Tradicinės saugumo kontrolės priemonės, yra labai veiksmingos saugant DI aplinką ir artefaktus, tačiau ne logiką, įdiegtą jo „smegenyse“ – modelyje.
* Apgavimo ataka (evasion attack) naudoja trikdžius (nematomą triukšmą plika akimi), kad suklaidintų modelį. Šie trikdžiai generuojami naudojant procesą, panašų į gradientinį nusileidimą (gradient descent), siekiant apgauti modelį jo fiziškai nekeičiant. Pvz., pasinaudoti Adversarial Robustness Toolbox įrankiu ir šešėliniu modeliu (surrogate shadow model), kad sukurt trikdžius.
* Tradicinė kibernetinė sauga daugiausia orientuojasi į sistemų, tinklų ir duomenų apsaugą nuo skaitmeninių atakų, neautorizuotos prieigos ir žalos. Jos pagrindinė užduotis – įdiegti gynybos mechanizmus, tokius kaip ugniasienės, įsibrovimų aptikimo sistemos ir šifravimas, kad būtų apsaugoti skaitmeniniai ištekliai. Tradicinės saugos reakcija į grėsmes dažniausiai yra reaktyvi. Ji remiasi žinomais grėsmių parašais ir pažeidžiamumais, dėl ko tampa mažiau veiksminga prieš naujoviškas ir sudėtingas atakas, pagrįstas mašininiu mokymusi (ML) ir modelių veikimo principu. Priešiškas DI (Adversarial AI) įveda naują dimensiją į šį iššūkį – jis pasitelkia pažangius ML metodus, kad sukurtų kenksmingas įvestis, galinčias suklaidinti ML modelius. Tai pakelia priešiškas įvestis į optimizavimo problemą, kuri prisitaiko remdamasi modelio įvestimis ir išvestimis.
Dėl šio prisitaikymo tampa labai sunku aptikti tokias atakas naudojant tradicinius parašų aptikimo metodus.
* Nuodijimo atakos (poisoning attacks) apima mokymo ir validacijos duomenų rinkinių klastojimą, siekiant sukelti kenksmingas pasekmes (pvz., „galinius vartus“ / backdoors) arba parazitinį naudojimą („Trojos arklius“ / Trojan horses).
* Evasion attacks yra nukreiptos į jau įdiegtus modelius, siekiant sudaryti sąlygas sukčiavimui arba neteisingai klasifikacijai ir kartais DoS atakoms. Šios atakos vyksta skirtinguose etapuose, tačiau tiek nuodijimo, tiek apgavimo atakos kėsinasi į modelio integralumą.
* Išgavimo atakos (extraction attacks) ir inferencijos atakos (inference attacks) nukreiptos į modelio privatumą. Jos gali apimti: Modelio svorių išgavimą, kad būtų sukurtas panašus šešėlinis modelis (shadow model). Duomenų, naudotų modelio mokymui, nustatymą ir aproksimavimą.
* Galiausiai, didelių kalbos modelių (LLMs) ir priešiško DI pažanga sukėlė reikšmingų pokyčių Adversarial AI srityje: Prompt injekcijos gali priversti LLM generuoti nepageidaujamą turinį arba užteršti duomenis, kuriuos modelis naudoja atsakymams generuoti.
  NUODIJIMO ATAKOS
* Nuodijimo atakos (poisoning attacks) gali būti klasifikuojamos pagal jų taikomus metodus. Tai nuolat besivystanti sritis, tačiau pagrindiniai metodai yra šie:
  * Galinių vartų atakos (Backdoor attacks): Tai tikslingos atakos, kurios nukreiptos į konkrečias įvestis ir išvestis, tuo pačiu išlaikant aukštą tikslumą kitoms įvestims. Dažnai jos apima galinių vartų arba trigerio įterpimą į modelį.
  * Švarių etikečių atakos (Clean-label attacks): Šių atakų metu mokymo rinkinyje strategiškai įterpiami kenksmingi duomenys, kurie atrodo nekenksmingi ir kurių etiketės nėra keičiamos. Nepaisant šių apribojimų, užpuolikas siekia subtiliai manipuliuoti duomenimis taip, kad išmokytas modelis elgtųsi netinkamai pagal užpuoliko norus.
  * Pažangios atakos (Advanced attacks): Šios atakos naudoja pažangias strategijas, kurios pasinaudoja modelio vidinėmis savybėmis, pavyzdžiui, neuroninio tinklo gradientais.
  * Tikslingos atakos (targeted attacks): Šių atakų metu priešininkas siekia manipuliuoti modelio elgsena konkrečioms įvestims ir išvestims, dažnai nedarydamas reikšmingos įtakos bendram modelio tikslumui. Pavyzdys: Priversti šlamšto filtrą klasifikuoti el. laiškus iš konkretaus siuntėjo kaip ne šlamštą arba netinkamai išmokyti modelį, kad jis klasifikuotų lėktuvą kaip paukštį.
  * Netikslingos atakos (untargeted attacks): Šiose atakose užpuolikas siekia sumažinti bendrą modelio našumą, nesikoncentruodamas į konkrečius pavyzdžius. (https://www.chillcybersecurity.co.uk/what-are-untargeted-and-targeted-attacks/)
* Pastaba dėl klasifikavimo: Ši klasifikacija remiasi pagrindinėmis kiekvienos atakos savybėmis, aprašytomis įvairiuose moksliniuose straipsniuose, siekiant išryškinti pagrindinį metodą. Kai kurios atakos gali patekti į kelias kategorijas

  Apsauga nuo nuodijimo atakų.
  * Anomalijų aptikimas yra technika, naudojama identifikuoti duomenų dėsningumus, kurie neatitinka tikėtino elgesio. Tokie neatitinkantys dėsningumai vadinami anomalijomis arba išskirtimis (outliers). Duomenų nuodijimo atakų aptikimo kontekste anomalijų aptikimo algoritmai ieško duomenų taškų mokymo rinkinyje, kurie reikšmingai nukrypsta nuo daugumos, taip nurodydami galimą duomenų klastojimą ar kenksmingą įterpimą. Šią techniką galime naudoti:
    * Ad hoc pagrindu – kaip vienkartinį patikrinimą, atliekant duomenų analizę.
    * Integruotai į MLOps procesus – kaip duomenų validacijos dalį, kad nuolatos stebėtume įvesties duomenų kokybę ir aptiktume anomalijas prieš modelio mokymą.
Toks integravimas padeda sumažinti riziką, kad kenksmingi duomenys paveiks modelio veikimą.
  * Įtartinų duomenų taškų identifikavimas: Anomalijų aptikimas gali pažymėti duomenų taškus, kurie reikšmingai nukrypsta nuo normos. Tai padeda identifikuoti įrašus mokymo rinkinyje, kuriuos užpuolikas galėjo įterpti arba modifikuoti.
  * Automatinis stebėjimas: Anomalijų aptikimas gali būti automatizuotas, kad nuolat stebėtų gaunamus mokymo duomenis. Tai suteikia realaus laiko įspėjimus, jei aptinkami įtartini duomenys.
  * Klaidų (false positive) sumažinimas: Nors atliekant rankinę peržiūrą dėl žmogiškų klaidų gali būti pažymėti ir nekalti duomenys kaip kenksmingi, gerai sureguliuoti anomalijų aptikimo algoritmai gali sumažinti tokių klaidingų teigiamų rezultatų skaičių.
  * Anomalijų aptikimas gali būti efektyvi saugumo priemonė kovojant su duomenų nuodijimu, tačiau diegiant šią techniką būtina atsižvelgti į šiuos iššūkius:
    * Reguliavimas (Tuning): Anomalijų aptikimo algoritmai dažnai turi parametrus, kuriuos būtina atsargiai sureguliuoti. Netinkamas reguliavimas gali sukelti daug false positives (pažymėti nekalti duomenys) arba false negatives (neaptikti kenksmingi duomenys) rezultatų.
    * Kintantys duomenys (Evolving data): Į sistemą nuolat įtraukiant naujus, teisėtus duomenis, normos suvokimas gali kisti. Anomalijų aptikimo sistemos turi gebėti prisitaikyti prie pokyčių, kad išliktų veiksmingos.
    * Slaptos atakos (Stealthy attacks): užpuolikai gali įterpti nuodytus duomenis, kurie labai panašūs į teisingus duomenis. Tokie duomenys gali būti sunkiai aptinkami anomalijų aptikimo algoritmų, nes jie neperžengia nustatytų ribų ir atrodo kaip autentiški įrašai.
  * Advanced poisoning defenses with ART. Nors bendras anomalijų aptikimas nevertina poveikio modeliui, o atsparumo testai dažnai būna per daug orientuoti į specifinius atvejus, ART (Adversarial Robustness Toolbox) siūlo tarpinius gynybos metodus nuo nuodijimo atakų. Šie metodai remiasi moksliniais tyrimais ir sujungia pažangias anomalijų aptikimo technikas su testavimu prieš modelį, siekiant įvertinti duomenų poveikį. Šias priemones galima naudoti programiškai, tiek notebook aplinkoje, tiek MLOps procesuose, ir jos apima:
      * Aktyvacijų gynyba (Activation defenses)
      * Duomenų kilmės gynyba (Data provenance defenses):
      * Ribotumai: Duomenų kilmės patikrinimas ne visada yra praktiškas ir negarantuoja, kad patys duomenys nėra užnuodyti.
      * RONI (Rejection of Negative Impact) 
      * https://ml-ops.org/content/mlops-principles

  * Supply chain attacks:
    * https://owasp.org/www-project-machine-learning-security-top-10/docs/ML06_2023-AI_Supply_Chain_Attacks
    * https://medium.com/@scottbolen/outsmarting-ai-driven-supply-chain-attacks-a-comprehensive-guide-3a88f8bf93bb


## Užtuotis

Perskaityti ir detaliau susipažinti su:
* https://insights.sei.cmu.edu/blog/threat-modeling-12-available-methods/
* https://attack.mitre.org/
* https://csrc.nist.gov/pubs/ai/100/2/e2023/final
* https://atlas.mitre.org/tactics/AML.TA0002/
* https://openaccess.thecvf.com/content/CVPR2023W/AML/papers/Sarkar_Robustness_With_Query-Efficient_Adversarial_Attack_Using_Reinforcement_Learning_CVPRW_2023_paper.pdf
* Supply chain attack

  
* https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/defences/detector_poisoning.html
* https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/notebooks/poisoning_defense_activation_clustering.ipynb
* https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/notebooks/poisoning_defense_spectral_signatures.ipynb
* https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/notebooks/provenance_defence.ipynb



