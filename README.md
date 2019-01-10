# Portfolio Afasie project
 Naam student: Erik van der Caaij <br>
 Studentnummer: 15059421 <br>
 

 
In dit project is er gekeken naar de mogelijkheden om mensen met Afasie te kunnen helpen met het herstellen van een hersenbloeding. Afasie is als mensen een hersenbloeding hebben gehad in het taalcentrum waardoor mensen niet goed meer kunnen praten of bepaalde fonetische fouten maken. Voor het herstellen van deze variant van de hersenbloeding gaan mensen in sessies met een begeleider oefenen. In veel gevallen zorgt deze één op één sessie voor veel stress hierdoor gaat de spraak bij de patiënten nog lastiger. Onze taak in dit project is dan ook om te kijken hoe wij eventueel door het gebruikt te maken van een computer/robot deze patiënten te kunnen laten oefenen zonder dat zij deze stress mee maken. Wij proberen in dit project hoe een speech2text kan helpen bij het oefenen van mensen met Afasie en proberen deze dan te ontwikkelen. <br>

In dit project wordt er gebruikt gemaakt van Scrum hierdoor weten we precies wat iedereen in het projectgroepje aan het doen is en kunnen we ook mensen erop aanspreken als bepaalde taken niet zijn uitgevoerd. Elke sprint duurt twee weken en we hebben zo'n twintig weken voor dit project.<br>

Hieronder staan een aantal screenshots van de online courses die zijn afgerond. Door deze cursussen heb ik kennis verkregen over python en machine learning. 

<H2> Datacamp screenshot </H2> <br>
Hier heb ik de eerste tien weken aanbesteed met als resultaat dat ik python heb geleerd(<a href='https://www.scrumwise.com/scrum/#/backlog-item/3248-datacamp-python-intro-course/id-84641-10738-147'> Scrumwise ticket</a> ). Daarna heb ik dit gebruikt in het project om zo bestanden kunnen cleanen en te visualiseren. De volgende hoofdstukken zijn hierbij aan bod gekomen: Intro to Python for Data Science, Intermediate Python for Data Science, Customizing plots, Introduction and flat files, Writing your own functions, Python Data Science Toolbox(Part2), Data ingestion & inspection en Exploratory data. <br>


 
![datacamp](https://user-images.githubusercontent.com/42931518/45440797-96361100-b6bd-11e8-9627-4e748ec38698.jpg)<br>
Afbeelding1: Hier staan de cursussen die ik heb afgerond voor datacamp.<br>

<h2> Coursera screenshot </H2><br>
Coursera heb ik ook in de eerste tien weken van de deze minor afgerond om zo genoeg kennis te hebben voor de toets en te zorgen dat ik kennis genoeg heb en dit kan toepassen op het project van Afasie(<a href='https://www.scrumwise.com/scrum/#/backlog-item/4405-coursera-maken/id-84641-13599-0'>Scrumwise ticket </a>). In Coursera heb ik week1, week2, week3 en week 6 gemaakt. Hieronder staat de screenshot met bijbehorende percentages die ik gehaald heb voor de quizzen aan het einde van elk hoofdstuk.<br>

![coursera](https://user-images.githubusercontent.com/42931518/49797999-760c0180-fd41-11e8-905d-271a428a70b2.png) <br>
Afbeelding2: Hier staan de cursussen die ik heb afgerond voor coursera.<br>


 <h2> Domain knowledge(Literature, jargon, evaluation, existing data sets)</h2> <br>
 
Tijdens het doen van Research naar wat Afasie is heb ik gebruikt gemaakt van een aantal bronnen. Deze bronnen heb ik gebruikt om te zien wat überhaupt Afasie is en om in te lezen in het domein.<br>

 
 Hieronder Staan een aantal documenten die te maken hebben met research doen naar het domein.<br>
 
 In dit document is er research gedaan naar wat Afasie precies is en of het bijvoorbeeld over kan gaan. Daarnaast heb ik gekeken of er bepaalde woorden zijn waar Afasie vaker bij optreed.  (<a href='https://www.scrumwise.com/scrum/#/backlog-item/3224-deskresearch-afasie/id-84641-10738-18'> Scrumwise ticket </a>).
[Deskresearch.Afasie_Erik (1).pdf](https://github.com/erikos94/Portfolio/files/2744856/Deskresearch.Afasie_Erik.1.pdf)
 <br>
 
 
Ik heb in het onderstaande document onderzoek gedaan naar wat fonologie, syntaxis, semantiek, antoniemen, synoniemen en hyponiemen zijn. Dit heb ik met de rest van de groep gedeeld, omdat deze begrippen veel worden gebruikt in dit domein.In(<a href='https://www.scrumwise.com/scrum/#/backlog-item/3323-in-hoeverre-kan-er-via-bestaande-stt-drie-types-fouten-worden-opgelostsemantic/id-84641-10884-56'>Scrumwise ticket </a>). Dit heeft bijgedragen aan het project, omdat ik hierdoor weet om welke fouten het gaat en hoe je deze termen uit elkaar kan halen en zien wat dit betekend.
[Research deelvragen Erik(concept) (1).pdf](https://github.com/erikos94/Portfolio/files/2744870/Research.deelvragen.Erik.concept.1.pdf) <br>
 
Hieronder staat het document waarin ik research heb gedaan naar classifiers. Hierbij heb ik gekeken naar hoe ik bepaalde classifiers kan gebruiken en hoe accuraat deze zijn. Hiervoor heb ik wetenschappelijk artikelen gebruikt. Daarnaast heb ik de link gelegd om te zien of we deze classifiers uit de literatuur konden gebruiken voor ons project. We hebben uit de literatuur de hoogst scorende classifiers gehaald en deze hebben wij toegepast op ons project.(<a href='https://www.scrumwise.com/scrum/#/backlog-item/3692-research-classificatie-algoritmes-voor-clasificere-van-diphone-clasifier/id-84641-11576-9'>Scrumwise ticket </a>). <br>
 [Research voor classifier en phoneme boundary.pdf](https://github.com/erikos94/Portfolio/files/2744877/Research.voor.classifier.en.phoneme.boundary.pdf)
 
<h2>Predictive Models</h2><br>
Hieronder staan een aantal predictive models die ik heb geprobeerd om te zien of deze werkten voor ons project.
<ul>
 <li>SVM(<a href='https://www.scrumwise.com/scrum/#/backlog-item/3851-classifier-trainen-met-10-zinnen-van-foxvorge-data/id-84641-12037-7'>Scrumwise ticket </a>):[SVM.pdf](https://github.com/erikos94/Portfolio/files/2744881/SVM.pdf)</li><br>
 Ik heb SVM(Support Vector Machine) gebruikt om een classifier te maken voor de Phoneme Boundary classifier van Koray. Na het testen van deze SVM zagen we dat accuracy, precision en recall niet goed waren(helaas, is hier geen screenshot, omdat de dataset is gewijzigd). Dit hebben we toen overlegd en uiteindelijk was Koray zijn classifier beter en zijn we niet verder gegaan met de SVM. 
 <br>
 
  
 <li>(LSTM) Keras</li><br>
 
 Ik heb het LSTM model in Keras gebruikt om een Sequence2Sequence model te maken. De LSTM is gebruikt om zinnen van Nederlands naar het Nederlands te vertalen. Dit was een experiment om te zien of dit uiteindelijk ook kon met MFCC Features -> klanken. Dit was namelijk ons uiteindelijke doel.(<a href='https://www.scrumwise.com/scrum/#/backlog-item/4406-lstm-en-fra-bekijken-en-toepassen-op-nl-nl-zinnen/id-84641-13599-10'> Scrumwise ticket </a>).<br> [dataset MFCC -_keras.pdf](https://github.com/erikos94/Portfolio/files/2729455/dataset.MFCC.-_keras.pdf)<br><br>
 
 Hierna heb ik geprobeerd om met woorden van Nederlands naar het om te zetten en bij dit experiment gaf het aan dat het 80% accuracy was. Hierna is het idee om van woorden naar klanken te gaan. Hieronder staat het resultaat van het experiment met de woorden naar woorden.<br> 
 
 [dataset MFCC -_Keras-Woorden (2).pdf](https://github.com/erikos94/Portfolio/files/2729459/dataset.MFCC.-_Keras-Woorden.2.pdf)

</ul>

 
 <h2>Data preparation</h2><br>
 Voor het ophalen van data en het maken van een dictionary heb ik het volgende script geschreven. Deze dictionary was nodig voor PocketSphinx.  <br>
 [lijst maken van woorden voor dictonary.pdf](https://github.com/erikos94/Portfolio/files/2744891/lijst.maken.van.woorden.voor.dictonary.pdf)<br>
 
 Voor het cleanen van de data heb ik de volgende code gebruikt: <br>
 
[code voor cleanen woordfile.pdf](https://github.com/erikos94/Portfolio/files/2744899/code.voor.cleanen.woordfile.pdf)
 
 <h2> Data Visualization </h2><br>
 
 We hebben eigenlijk data visualization kunnen toepassen vanaf ongeveer week 12, omdat we elke keer geen goede dataset hadden. Met geen goede dataset bedoelen we dat we geen timestamps hadden per woord. Dit kon ook niet gegenereerd worden, omdat deze vaak niet accuraat was. <br>
 
 Tijdens het project hebben we een experiment gaan doen met een pipeline. Deze pipeline zou van een fourier transfrom (FFT) over een audio signaal uitvoeren. Dus hierbij hebben we het proberen te plotten om te zien wat dit precies inhield en hoe we dit moesten interpreteren.(<a href='https://www.scrumwise.com/scrum/#/backlog-item/3772-voorbeeld-creeren-visualisatie-van-fft-en-mfcc/id-84641-11988-34'>Scrumwise ticket </a>) <br>
 
![erik woorden plot fft](https://user-images.githubusercontent.com/42931518/49877233-41717600-fe25-11e8-88ac-daa86d9511de.png)<br>
 Afbeelding3: Een plot van vijf uitgesproken woorden door Erik in FFT.<br>

![koray woorden plot fft](https://user-images.githubusercontent.com/42931518/49877238-42a2a300-fe25-11e8-8e69-a33dc26265dd.png)<br>
Afbeelding4: Een plot van vijf uitgesproken woorden door Koray in FFT.<br>

Dit was wel een resultaat, omdat beide plots er anders uitzien, het lijkt op dat dit iets te maken heeft met een frequentie etc, maar dit hebben we nooit goed kunnen inschatten en zijn we verder gegaan met deze woorden te plotten op een WAV-file.
Daarna heb ik deze omgezet in een audio WAV, om te zien of daar bepaalde veranderingen te zien waren. <br>

Dit is voor vijf ingesproken woorden door Erik.
![wav files woorden_erik](https://user-images.githubusercontent.com/42931518/49878716-8cd95380-fe28-11e8-98ff-bb6f2c37c38f.png) <br>
Afbeelding5: Een plot van vijf uitgesproken woorden door Erik in Wav.<br>

Dit is voor vijf ingesproken woorden door Koray. 
![koray woorden wav](https://user-images.githubusercontent.com/42931518/49878714-8a76f980-fe28-11e8-8c58-c74d47b60d93.png)<br>
Afbeelding6: Een plot van vijf uitgesproken woorden door Koray in Wav.<br>

Hieraan is af te zien dat we de woorden sneller/ langzamer dan elkaar uitspreken en waarschijnlijk ook op een andere frequentie, maar kunnen we hier niet goed van interpreteren. Wat uiteindelijk het resultaat hiervan is, is dat we weten hoe je een FFT kan gebruiken over een audio file en wat je met die library kan doen.


 <h2> Data collection </h2><br>
 We zijn met de data collection vrij lang bezig geweest ,omdat we eerst dachten dat we de data van onze opdrachtgever vroeg zouden krijgen en aan de slag te kunnen gaan. Achteraf bleek de data die we hebben gekregen niet te voldoen aan de eisen om een Speech2text te maken. 
 
 We hebben veel kleine testjes gedaan met opgenomen audio waarin wij bepaalde woorden of getallen inspreken zodat we deze kunnen gebruiken om bepaalde boundaries te vinden. <b> link naar audio opnames</b> Deze heb ik samen met Koray ingesproken.

Ook heb ik research gedaan naar een database met audio die we zouden kunnen gebruiken en hierbij kwam ik uit op de site van de UVA(universiteit van Amsterdam). http://www.fon.hum.uva.nl/IFA-SpokenLanguageCorpora/IFAcorpus/

Deze dataset is 1.8GB groot hebben we doormiddel van een scraper die Koray had gemaakt van de site afgehaald zodat we in ieder geval data hadden waarmee we aan de slag konden. 

 
<h2> Diagnostics of the learning process :learning rate, loss function, overfitting and under fitting </h2><br>
 Ik had een voorbeeld gevonden van een Seq2seq (sequence to sequence) waarin een zin in het Engels werd vertaald naar het frans(<a href='https://www.scrumwise.com/scrum/#/backlog-item/4407-seq2seq-bekijken-en-zien-hoe-we-dit-kunnen-toepassen-op-afasie/id-84641-13599-17'>Scrumwise ticket </a>). Hier ben ik een beetje mee gaan spelen om te zien of dit ook gebruikt kan worden voor ons project. De resultaten waren verbazingwekkend goed. Zie hieronder: <br> In de plaatsjes is de test lijn eigenlijk de validatie. Dus in de volgende plaatjes is het train en validatie.

![acc_zinnen_nl](https://user-images.githubusercontent.com/42931518/50691690-c5d4a480-1031-11e9-8320-2bd3dff64bfc.png)<br>
Afbeelding7: EEn plot van de accuracy van het experiment van Seq2seq van Nederlandse zinnen.<br>

![loss_zinnen_nl](https://user-images.githubusercontent.com/42931518/50691687-c5d4a480-1031-11e9-989f-5056d3947158.png)<br>
Afbeelding8: Een plot van de Loss van het experiment van Seq2seq van Nederlandse zinnen.<br>

![output_zinnen_nl](https://user-images.githubusercontent.com/42931518/50691688-c5d4a480-1031-11e9-8205-c2cc8939fa56.png)<br>
Afbeelding9: Een plot van de output van de het LSTM model voor de Seq2seq van de Nederlandse zinnen.<br>

Daarna hebben we de dataset die we hadden omgeschreven zodat er woorden worden gegenereerd. Deze hebben we als input meegegeven aan de LSTM en deze gaf ongeveer zo'n 80% goede uitkomst. <b> plaatje invoegen </b> Dat gaf dus veel hoop om dit ook te proberen met fonemen, zodat we konden kijken we zinnen in fonemen konden uitsplitsten.
  
 <h2> Communication (presentations, summaries, paper) </h2><br>
 
 <b> paper: </b>
 <b> presentations </b>

<li>Week 5: [Kopie van Aphasia week5.pdf](https://github.com/erikos94/Portfolio/files/2744916/Kopie.van.Aphasia.week5.pdf) <br></li>
<li> Week 7:[_Aphasia week7.pdf](https://github.com/erikos94/Portfolio/files/2744917/_Aphasia.week7.pdf)<br></li>
<li> week 9: [Kopie van Aphasia week 9.pdf](https://github.com/erikos94/Portfolio/files/2744918/Kopie.van.Aphasia.week.9.pdf)<br></li>
<li> week 14:[Aphasia week 14.pdf](https://github.com/erikos94/Portfolio/files/2744919/Aphasia.week.14.pdf)<br></li>

 
 
<h2>Link to the Python Notebooks you have finished (you can dump them to PDF)</h2>
<h2>List the tickets from the Scrum backlog that you worked on, linked to deliverables, own experiments, etc.
Add any other assignment you feel is evidence of your abilities </h2><br>

Omdat wij tijdens dit project de hele tijd met zijn vieren waren hebben we er voor gezorgd dat iedereen zijn sterke punten kon benutten hierdoor heb ik meer documentatie werk gedaan dan andere. Hieronder een lijst wat ik denk dat wel toegevoegde waarde is geweest aan dit project. <br>


<ul>
 <li>Ik heb een plan van aanpak gemaakt: 
[Plan van aanpak_AfasieDEF.pdf](https://github.com/erikos94/Portfolio/files/2744938/Plan.van.aanpak_AfasieDEF.pdf) (<a href='https://www.scrumwise.com/scrum/#/backlog-item/3266-pva-maken/id-84641-10790-7'> Scrumwise ticket </a>)</li>
 <li>Ik heb een Interviewprotocool opgesteld: [Interviewprotocol - AfasieExpert.pdf](https://github.com/erikos94/Portfolio/files/2744943/Interviewprotocol.-.AfasieExpert.pdf) (<a href='https://www.scrumwise.com/scrum/#/task/5022-interview-protocol-opstellen/id-84641-10738-102'> Scrumwise ticket</a>) </li>
 <li> Onderzoek gedaan naar Arfabet en sampa/xsampa. Dit hebben we gedaan om eventueel zelf een paar worden te kunnen omzetten naar deze afbet, om hiermee te gaan trainen. Daarnaast gebruikte pocketsphinx ARFABET en we moesten dus weten hoe dit in elkaar zat. [Klanken samenvatting CMUSPHINX(PORTFOLIO).docx](https://github.com/erikos94/Portfolio/files/2729482/Klanken.samenvatting.CMUSPHINX.PORTFOLIO.docx) (<a href='https://www.scrumwise.com/scrum/#/backlog-item/3523-find-out-more-about-phonemes-the-origin-and-how-they-work/id-84641-11280-0'> Scrumwise ticket </a>)

<li>
 <li> Selecteren van audio voor Afasie. Dit heb ik gedaan omdat heel veel audio hebben gekregen van de opdrachtgever, hierin zaten alle audio bestanden, dus ook met mensen die bijna geen woord kunnen zeggen. Wij focussen ons nu op de de fonologie afwijkingen dus deze moesten we eruit filteren.[Schema welke goed.pdf](https://github.com/erikos94/Portfolio/files/2744945/Schema.welke.goed.pdf)</li>
 <li> Dataset achterhaalt (gesproken corpus Nederlands)</li>
 <li>speech2text met google api [Api google code.docx](https://github.com/erikos94/Portfolio/files/2736965/Api.google.code.docx)</li>
<ul>

