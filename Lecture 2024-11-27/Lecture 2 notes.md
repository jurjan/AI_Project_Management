# DI projekto gyvavimo ciklas. AI projektų valdymo metodikų apžvalga
# AI Project Lifecycle. Overview of AI project management methodologies

Paskaitos įrašas: nėra (neįrašiau pasirodo :( )
Paskaitos skaidrės: https://github.com/jurjan/AI_Project_Management/blob/main/Lecture%202024-11-27/Paskaita%202.pdf

## Trumpas paskaitos aprašas

Nuorodos, kurios Jums bus naudingos sudarant planus, vertinant rizikas ir planuojant resursus:
* https://www.smartsheet.com/resource-planning-templates
* https://www.smartsheet.com/content/project-risk-templates
* https://www.process.st/templates/free-risk-assessment-template
* https://www.projectmanager.com/blog/resource-management-templates

Knyga, kurią labai rekomenduoju: https://www.mlebook.com/wiki/doku.php (Prieinama online)

Tiems, kas domisi sertifikatais - https://projectmanagementacademy.net/resources/pmbok-guide-in-project-management/

DI Projekto gyvavimo ciklas skirtingoje literatūroje gali būti kiek kitoks, tačiau esmė išlieka tokia pati. Fazių gali būti daugiau/mažiau. Tas pats ir kalbant apie ML Projekto gyvavimo ciklą. Pavyzdžiui, šios nuorodos gali Jums padėti lengvai prisiminti visus žingsnius:
* https://www.spaceo.ai/blog/ai-development-life-cycle/
* https://www.datacamp.com/blog/machine-learning-lifecycle-explained
* https://www.paloaltonetworks.com/cyberpedia/ai-development-lifecycle

<ins> Projekto valdymo metodologijos laikui bėgant keitėsi, prisitaikant prie kintančių projektų: </ins>

1. Waterfall Model/Krioklio modelis
   (1950s - 1970) Sukurta daugiausia gamybai ir statyboms, kur procesai yra linijiniai ir nuoseklūs. „Waterfall“ modelis laikosi linijinio, etapais pagrįsto požiūrio, kai kiekvienas etapas (toks kaip inicijavimas, planavimas, vykdymas ir užbaigimas) užbaigiamas prieš pradedant kitą. Daroma prielaidą, kad visi projekto reikalavimai gali būti apibrėžti iš anksto, todėl yra mažiau lankstus pokyčiams. Aiški struktūra, lengva valdyti paprastus, gerai apibrėžtus projektus, ypač naudinga pramonės šakose, kuriose pokyčiai yra brangūs ir sudėtingi. Ribotas lankstumas, todėl netinka projektams, kuriuose reikalavimai keičiasi arba yra neapibrėžti. Taip pat ribotas suinteresuotųjų šalių dalyvavimas vystymo etapuose.
   https://www.geeksforgeeks.org/waterfall-model/
2. Critical Path Method (CPM) and Program Evaluation and Review Technique (PERT) / Kritinio kelio metodas (CPM) ir programų vertinimo bei peržiūros technika (PERT)
   (1950s - 1960s) Sukurta sudėtingiems, didelės apimties projektams, tokiems kaip tarpvalstybinės greitkelių sistemos statyba ir kariniai projektai. Šie metodai orientuojasi į ilgiausios priklausomų užduočių sekos („kritinio kelio“) nustatymą, siekiant nustatyti projekto trukmę. PERT prideda laiko kintamumo ir statistinės analizės elementus prie CPM. Naudinga dideliems projektams su sudėtingomis tarpusavio priklausomybėmis ir grafikų optimizavimui. Leidžia vadovams sutelkti dėmesį į svarbiausias užduotis, kad būtų išvengta vėlavimų. Sudėtinga valdyti ir atnaujinti; mažiau efektyvu projektams, kuriuose yra daug neapibrėžtumo ar iteracinių pokyčių.
   https://www.projectmanager.com/guides/critical-path-method
   https://www.investopedia.com/terms/p/pert-chart.asp
3. Agile Project Management
   (1990s - Dabar) Sukurta programinės įrangos kūrėjų, kuriems reikėjo lankstesnės ir prisitaikančios metodikos. 2001 m. sukurtas „Agile“ manifestas formalizavo jos principus. „Agile“ pabrėžia iteracinę plėtrą, nuolatinį bendradarbiavimą su suinteresuotosiomis šalimis ir gebėjimą greitai reaguoti į pokyčius. Dažniausiai naudojamos „Agile“ sistemos apima „Scrum“, „Kanban“ ir „Lean“. Didesnis lankstumas, trumpesni kūrimo ciklai, nuolatinis grįžtamasis ryšys iš suinteresuotųjų šalių ir galimybė greitai prisitaikyti prie besikeičiančių reikalavimų. „Agile“ gali būti sudėtinga pritaikyti dideliems projektams, ir jai gali trūkti struktūros, reikalingos griežtai reguliuojamose pramonės šakose. Reikalingas aukštas suinteresuotųjų šalių įsitraukimo lygis ir komandos narių disciplina.
   https://www.agilealliance.org/agile101/
4. Scrum Framework (an Agile Approach) / Scrum karkasas
   (1990s - Dabar) Atsirado iš „Agile“ principų. „Scrum“ skirsto projektus į trumpus ciklus, vadinamus „sprintais“ (dažniausiai trunkančius 1–4 savaites). Akcentuojami vaidmenys, tokie kaip produkto savininkas (Product Owner), Scrum Master ir komandos nariai, bei renginiai, tokie kaip kasdieniai susitikimai („daily stand-ups“), sprinto planavimas ir sprinto retrospektyvos. Skatina dažną grįžtamąjį ryšį, adaptyvų planavimą ir suteikia komandoms galimybę savarankiškai organizuotis. Tinka dinamiškoms aplinkoms, kuriose reikalavimai greitai keičiasi. Gali būti sunku įgyvendinti be tinkamo „Scrum“ mokymo. Reikalauja dažnos komunikacijos ir gali netikti komandoms, nepratusioms prie glaudaus bendradarbiavimo.
   https://www.scrum.org/resources/what-scrum-module
5. Lean Project Management / Lean projektų valdymas
   (1980s - Dabar) Sukurtas gamybos pramonėje ir pritaikytas įvairių tipų projektams 1990-aisiais ir 2000-aisiais. „Lean“ metodika orientuota į vertės maksimizavimą, šalinant švaistymą, gerinant procesų srautą ir optimizuojant veiklas. Ji labai akcentuoja efektyvumą, nuolatinį tobulinimą ir vertės teikimą klientui. Padeda sumažinti švaistymą ir sąnaudas, didina efektyvumą, sutelkiant dėmesį tik į vertę kuriančias užduotis. Dažnai naudojama kartu su „Agile“.
   https://www.pmi.org/learning/library/lean-project-management-7364
6. Kanban (Flow-Based Approach) / Kanban (srauto pagrindu paremta metodika)
   (2000 - Dabar) Pritaikyta iš „Lean“ gamybos ir „Toyota“ gamybos sistemos. „Kanban“ vizualizuoja darbo eigą lentose (fizinėse arba skaitmeninėse), siekiant valdyti vykdomus darbus ir optimizuoti srautą. Dėmesys skiriamas darbo eigos apribojimui, siekiant sumažinti kliūtis. Aukštas užduočių būklės ir pažangos matomumas, nuolatinis užduočių įgyvendinimas, lengvai pritaikoma be drastiškų pokyčių esamuose procesuose. Mažiau struktūros ir gali trūkti prognozuojamumo bei detalių planavimo, kaip „Scrum“ ar „Waterfall“ metoduose. Geriausiai veikia projektuose, kuriuose reikalingas nuolatinis užduočių srautas, o ne etapai, paremti etapų užbaigimu.
   https://www.atlassian.com/agile/kanban
7. Hybrid Methodologies (e.g., Waterfall-Agile, Agile-Stage-Gate)
   (2010-Dabar) Sukurtos siekiant spręsti vienos metodikos ribotumus, susijusius su sudėtingais, moderniais projektais. Hibridinės metodikos derina „Waterfall“ struktūrizuotą planavimą su „Agile“ lankstumu. Pavyzdžiui, „Agile-Stage-Gate“ metodika apjungia iteracinę plėtrą su etapų patvirtinimais, leidžiančiais „Agile“ komandoms atitikti reguliavimo ar aukšto lygio planavimo reikalavimus. Suteikia „Agile“ lankstumą kartu su „Waterfall“ struktūra, todėl yra pritaikomos pramonės šakose, kuriose būtina laikytis griežtų reguliavimo ar atitikties reikalavimų. Sudėtinga valdyti ir reikalauja kruopštaus planavimo, siekiant užtikrinti tinkamą pusiausvyrą tarp struktūros ir lankstumo.
8. Scaled Agile Frameworks (SAFe, LeSS, Disciplined Agile)
   (2010-Dabar) Sukurti, kai įmonės pradėjo taikyti „Agile“ metodiką didesniu mastu, atsirado poreikis karkasams, galintiems koordinuoti kelias „Agile“ komandas. Išplėstiniai „Agile“ karkasai suteikia struktūrą, skirtą didelių komandų valdymui per kelis projektus, daugiausia dėmesio skiriant projekto tikslų suderinimui su organizacijos tikslais. SAFe („Scaled Agile Framework“) yra vienas populiariausių rėmų, pritaikantis „Agile“ principus visai įmonei. Leidžia didelėms organizacijoms taikyti „Agile“ principus dideliu mastu, išlaikant lankstumą ir koordinuojant komandų pastangas. Sudėtingesnis ir reikalauja daug pastangų diegiant. Gali atrodyti pernelyg griežtas komandoms, įpratusioms prie „Agile“ lankstumo.
   https://scaledagileframework.com/#overview
   https://www.atlassian.com/agile/agile-at-scale/what-is-safe
   https://less.works/
   https://www.pmi.org/disciplined-agile/
12. DevOps and MLOps (Integration with Operations)
    (2010-Dabar) DevOps atsirado iš poreikio pagerinti bendradarbiavimą tarp programinės įrangos kūrimo ir IT operacijų komandų, ypač augant nuolatinės integracijos ir diegimo (CI/CD) poreikiui. DevOps orientuojasi į programinės įrangos kūrimo ciklo automatizavimą ir geresnį bendradarbiavimą tarp kūrimo ir operacijų komandų. MLOps yra pritaikytas variantas, skirtas AI/ML projektams, daugiausia dėmesio skiriant modelių diegimo, stebėjimo ir nuolatinio tobulinimo automatizavimui. Pagerina pristatymo greitį ir patikimumą, skatina nuolatinę integraciją ir pristatymą, gerina komandų bendradarbiavimą. Reikalauja aukšto automatizavimo lygio ir nuolatinio stebėjimo, gali būti sunkiai įgyvendinamas be stipraus komandų bendradarbiavimo ir pažangios infrastruktūros.
    https://ml-ops.org/

## Pagalba/skaitymas

* Haller, K. (2022). Managing AI in the Enterprise. Succeeding with AI Projects and MLOps to Build Sustainable AI Organizations
  * Puslapiai 49-56
* Project Management Institute. (2017). A guide to the Project Management Body of Knowledge (PMBOK guide) (6th ed.). Project Management Institute.
  * Puslapiai: 219, 42-49
* Burkov, A. Machine Learning Engineering. https://www.mlebook.com/wiki/doku.php
  * Puslapiai: 18-19
	







## Praktinė dalis

Šios knygos - https://www.mlebook.com/wiki/doku.php - antro skyriaus susisteminimas. Turite perskaityti ir medžiagą bei mintis perteikti diagramos pavidalu. Atliktą užduotį įkelti į Moodle/Atsiųsti/Github
