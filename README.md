# Portfolio Aphasia project
 Naam student: Erik van der Caaij <br>
 Studentnummer: 15059421 <br>
 

 
In dit project is er gekeken naar de mogelijkeheden om mensen met Afasie te kunnen helpen met het herstellen van een hersenbloeding. Afasie is als mensen een hersenbloeding hebben gehad in het taalcentrum waardoor mensen niet goed meer kunnen praten of bepaalde fonetische fouten maken. Voor het herstellen van deze variant van de hersenbloeding gaan mensen in sessies met een begeleider oefenen. In veel gevallen zorgt deze één op één sessie voor veel stress hierdoor gaat de spraak bij de patienten nog lastiger. Onze taak in dit project is dan ook om te kijken hoe wij eventueel door het gebruikt te maken van een computer/robot deze patienten te kunnen laten oefenen zonder dat zij deze stress mee maken. Wij proberen in dit project hoe een speech2text kan helpen bij het oefenen van mensen met Afasie en proberen deze dan te ontwikkelen. <br>

In dit project wordt er gebruikt gemaakt van Scrum hierdoor weten we precies wat iedereen in het projectgroepje aan het doen is en kunnen we ook mensen erop aanspreken als bepaalde taken niet zijn uitgevoerd. Elke sprint duurt twee weken en we hebben zo'n twintig weken voor dit project.<br>

Hieronder staan een aantal screenshots van de online coursers die zijn afgerond.

<H2> Datacamp screenshot </H2> <br>
Hier heb ik de eerste tien weken aanbesteed met als resultaat dat ik python heb geleerd(<a href='https://www.scrumwise.com/scrum/#/backlog-item/3248-datacamp-python-intro-course/id-84641-10738-147'> Scrumwise ticket</a> ). Daarna heb ik dit gebruikt in het project om zo bestanden kunnen cleanen en te visualiseren. De volgende hoodstukken zijn hierbij aanbod gekomen: Intro to Pyhton for Data Science, Intermediate Python for Data Science, Customizing plots, Introduction and flat files, Writing your own functions, Python Data Science Toolbox(Part2), Data ingestion & inspection en Exploratory data. <br>


 
![datacamp](https://user-images.githubusercontent.com/42931518/45440797-96361100-b6bd-11e8-9627-4e748ec38698.jpg)<br>
Afbeelding1: Hier staan de cursussen die ik heb afgerond voor datacamp.<br>

<h2> Coursera screenshot </H2><br>
Coursera heb ik ook in de eerste tien weken van de deze minor afgerond om zo genoeg kennis te hebben voor de toets en te zorgen dat ik kennis genoeg heb en dit kan toepassen op het project van Afasie. In Coursera heb ik week1, week2, week3 en week 6 gemaakt. Hieronder staat de screenshot met bijbehorende percentages die ik gehaald heb voor de quizzen aan het einde van een bepaald hoofdstuk.<br>

![coursera](https://user-images.githubusercontent.com/42931518/49797999-760c0180-fd41-11e8-905d-271a428a70b2.png) <br>
Afbeelding2: Hier staan de cursussen die ik heb afgerond voor coursera.<br>


 <h2> Domain knowledge(Literature, jargon, evaluation, existing data sets)</h2> <br>
 
Tijdens het doen van Research naar wat Afasie was, is er gebruikt gemaakt van een aantal bronnen. Deze bronnen hebben we gebruikt om te zien wat uberhaupt Afasie is en om in te lezen in het domein.<br>

<Scrumticket> 
 
 Hieronder Staan een aantal documenten die te maken hebben met research doen naar het domein.<br>
 
 In dit document is er research gedaan naar wat afasie precies is en of het bijvoorbeeld over kan gaan etc.
 [Deskresearch Afasie_Erik.docx](https://github.com/erikos94/Portfolio/files/2667461/Deskresearch.Afasie_Erik.docx) <br>

 
 In dit document is er research gedaan naar wat fonologie, syntaxis, semantiek, antoniemen, synonimen en hypniemen zijn. Dit heeft bijgedragen aan het project, omdat hierdoor weet om welke fouten het gaat en hoe je deze termen uitelkaar kan halen en zien wat dit betekend.
 https://drive.google.com/open?id=1Oo1BrPX9Rl-q8XALkE39Kr9M3movlpzA 
 
 Hieronder staat het document waarin ik research heb gedaan naar literatuur en hoe zei bepaalde classiefiers gebruiken en hoe accuraat    die zijn en hoe dit eventueel in ons project gebruikt kon gaan worden. Dit heeft bijgedragen dat we een aantal van deze classifiers hebben gebruikt om te kijken hoe deze scoren met onze zelf gemaakt dataset.<br>
 
 https://drive.google.com/open?id=13leNNydpd_EampEnIj_HkgvUG4eO3CMx
 
<h2>Predictive Models</h2><br>
<ul>
 <li>SVM: https://drive.google.com/open?id=1bSXZBj-65xlChK22W-27ZsLZDlsUnbb-u6b9QfyC-Fs</li><br>
 
 
  
 <li>(LSTM) tensorflow</li><br>
 De LSTM is gebruikt om zinnen van het nederlands naar het nederlands te vertalen. Dit was een experiment om te zien of dit uiteindelijk   ook kon met woorden en daarna met klanken.<br> [dataset MFCC -_keras.pdf](https://github.com/erikos94/Portfolio/files/2729455/dataset.MFCC.-_keras.pdf)<br><br>
 
 Hierna heb ik geprobeerd om met woorden van nederlands naar het om te zetten en bij dit experiment gaf het aan dat het 80% accuarcy was. Hierna is het idee om van woorden naar klanken te gaan.Hieronder staat het resultaat van het experiment met de woorden naar woorden.<br> 
 
 [dataset MFCC -_Keras-Woorden (2).pdf](https://github.com/erikos94/Portfolio/files/2729459/dataset.MFCC.-_Keras-Woorden.2.pdf)

</ul>

 
 <h2>Data preperation</h2><br>
 Voor het ophalen van data en het maken van een dictionary heb ik de volgende script geschreven <br>
 https://drive.google.com/open?id=1VUCTDgCSdM5k-1H6dtcS5kZqCd24fGZdh1OkAVpnb-k<br>
 
 ook voor het cleanen van de data heb ik de volgende code gebruikt: <br>
 
 https://drive.google.com/open?id=1VWy6CvHBdHIYbUxilQucKrjDkHY8dJHigvAFRkZ2y_0
 
 <h2> Data Visualization </h2><br>
 
 We hebben eigenlijk data visualization kunnen toepassen vanaf ongeveer week 12, omdat we elke keer geen goede dataset hadden. Met geen goede dataset bedoelen we dat we geen timestamps hadden per woord. Dit kon ook niet gegenereerd worden, omdat deze vaak niet accuraat was. <br>
 
 Tijdens het project hebben zijn we een experiment gaan doen met een bepaalde pipeline. Deze pipeline zou van een fourier transfrom (FFT) over een audio signaal uitvoeren. Dus hierbij hebben we het proberen te plotten om te zien wat dit precies inhield en hoe we dit moesten interpreteren. <br>
 
![erik woorden plot fft](https://user-images.githubusercontent.com/42931518/49877233-41717600-fe25-11e8-88ac-daa86d9511de.png)<br>
 Afbeelding3: Een plot van vijf uitgesproken woorden door Erik in FFT.<br>

![koray woorden plot fft](https://user-images.githubusercontent.com/42931518/49877238-42a2a300-fe25-11e8-8e69-a33dc26265dd.png)<br>
Afbeelding4: Een plot van vijf uitgesproken woorden door Koray in FFT.<br>

Dit was wel een restultaat, omdat beide plots er anders uitzien, het lijkt op dat dit iets te maken heeft met een frequentie etc, maar dit hebben we nooit goed kunnen inschatten en zijn we verder gegaan met deze woorden te plotten op een wav-file.
Daarna heb ik deze omgezet in een audio wav, om te zien of daar bepaalde veranderingen te zien waren. <br>

Dit is voor vijf ingesproken woorden door Erik.
![wav files woorden_erik](https://user-images.githubusercontent.com/42931518/49878716-8cd95380-fe28-11e8-98ff-bb6f2c37c38f.png) <br>
Afbeelding5: Een plot van vijf uitgesproken woorden door Erik in Wav.<br>

Dit is voor vijf ingesproken woorden door Koray. 
![koray woorden wav](https://user-images.githubusercontent.com/42931518/49878714-8a76f980-fe28-11e8-8c58-c74d47b60d93.png)<br>
Afbeelding6: Een plot van vijf uitgesproken woorden door Koray in Wav.<br>

Hieraan is af te zien dat we de woorden sneller/ langzamer dan elkaar uitspreken en waarschijnlijk ook op een andere frequentie, maar kunnen we hier niet goed van interpreteren. Wat uiteindelijk het resultaat hiervan is, is dat we weten hoe je een FFT kan gebruiken over een audio file en wat je met die library kan doen.


 <h2> Data collection </h2><br>
 We zijn met de data collection vrij lang beziggeweest ,omdat we eerst dachten dat we de data van onze opdrachtgever vroeg zouden krijgen en aan de slag te kunnen gaan. Achteraf bleek de data die we hebben gekregen niet te voldoen aan de eisen om een Speech2text te maken. 
 
 We hebben veel kleine testjes gedaan met opgenomen audio waarin wij bepaalde woorden of getallen inspreken zodat we deze kunnen gebruiken om bepaalde boundaries te vinden. <b> link naar audio opnamens</b> Deze heb ik samen met Koray ingesproken.

Ook heb ik research gedaan naar een database met audio die we zouden kunnen gebruiken en hierbij kwam ik uit op de site van de UVA(universiteit van Amsterdam). http://www.fon.hum.uva.nl/IFA-SpokenLanguageCorpora/IFAcorpus/

Deze dataset is 1.8GB groot hebben we doormiddel van een scraper die Koray had gemaakt van de site afgehaald zodat we in iedergeval data hadden waarmee we aan de slag konden. 

 
 <h2> Evaluation:precision recall </h2><br>
  <h2> Diagnostics of the learning proces :learning rate, loss function, overfitting and underfitting </h2><br>
  Ik had een voorbeeld gevonden van een Seq2seq (sequence to sequence) waarin een zin in het engels werd vertaald naar het frans. Hier ben ik een beetje mee gaan spelen om te zien of dit ook gebruikt kan worden voor ons project. De resultaten waren verbazingswekkend goed. Zie hieronder: <br> In de plaatsjes is de test lijn eigenlijk de validatie. Dus in de volgende plaatjes is het train en validatie.

![acc_zinnen_nl](https://user-images.githubusercontent.com/42931518/50691690-c5d4a480-1031-11e9-8320-2bd3dff64bfc.png)<br>
Afbeelding7: EEn plot van de accuracy van het experiment van Seq2seq van nederlandse zinnen.<br>

![loss_zinnen_nl](https://user-images.githubusercontent.com/42931518/50691687-c5d4a480-1031-11e9-989f-5056d3947158.png)<br>
Afbeelding8: Een plot van de Loss van het experiment van Seq2seq van nederlandse zinnen.<br>

![output_zinnen_nl](https://user-images.githubusercontent.com/42931518/50691688-c5d4a480-1031-11e9-8205-c2cc8939fa56.png)<br>
Afbeelding9: Een plot van de output van de het LSTM model voor de Seq2seq van de nederlandse zinnen.<br>

Daarna hebben we de dataset die we hadden omgeschreven zodat er woorden worden gegenereerd. Deze hebben we als input meegegeven aan de LSTM en deze gaf ongeveer zo'n 80% goede uitkomst. <b> plaatje invoegen </b> Dat gaf dus veel hoop om dit ook te proberen met fonemen, zodat we konden kijken we zinnen in fonemen konden uitsplitten.
  
 <h2> Comunication (presentations, summaries, paper) </h2><br>
 
 <b> paper: </b>
 <b> presentations </b>

<li>Week 5: https://drive.google.com/open?id=1LTQ1qC7WCMWQCBOAMHP2-zoP1kSOJ_pJ-iCz9XHRlM4 <br></li>
<li> Week 7: https://drive.google.com/open?id=1kc2vpfFzrVpF5ZZYKZ_q40-oPAyFXuui--qmEfO9Oz8<br></li>
<li> week 9: https://drive.google.com/open?id=1DMURc9o1ilJxbFun1z4FlDX9dX4VIfMDrEaKX4mk9-E<br></li>
<li> week 14:https://drive.google.com/open?id=1QvgprRupfHHyXJjVTP4y33QZ_YZtDWr3axN3W_Eh0wc<br></li>

 
 
<h2>Link to the Python Notebooks you have finished (you can dump them to PDF)</h2>
<h2>List the tickets from the Scrum backlog that you worked on, linked to deliverables, own experiments, etc.
Add any other assignment you feel is evidence of your abilities </h2><br>

Omdat wij tijdens dit project de heletijd met zijn vieren waren hebben we er voor gezorgd dat iedereen zijn sterke punten kon benutten hierdoor heb ik meer documentatie werk gedaan dan andere. Hieronder een lijst wat ik denk dat wel toegevoegde waarde is geweest aan dit project. <br>


<ul>
 <li>Ik heb een plan van aanpak gemaakt: https://drive.google.com/open?id=1P7V9aLiVGaIaEyQCiOoEW5HxmrPvOt8m</li>
 <li>Ik heb een Interviewprotocool opgesteld: https://drive.google.com/open?id=1Tpcp2mWAdArX_iFhqvBKPpRbh99Z6bQ4rydBEV8Bbkg (<a href='https://www.scrumwise.com/scrum/#/task/5022-interview-protocol-opstellen/id-84641-10738-102'</a>) </li>
 <li> Onderzoek gedaan naar Arfabet en sampa/xsampa. Dit hebben we gedaan om eventueel zelf een paar worden te kunnen omzetten naar deze afbet, om hiermee te gaan trainen. Daarnaast gebruikte pocketsphinx ARFABET en we moesten dus weten hoe dit in elkaar zat. [Klanken samenvatting CMUSPHINX(PORTFOLIO).docx](https://github.com/erikos94/Portfolio/files/2729482/Klanken.samenvatting.CMUSPHINX.PORTFOLIO.docx)

<li>
 <li> Selecteren van audio voor Afasie. Dit heb ik gedaan omdat heel veel audio hebben gekregen van de opdrachtgever, hierin zaten alle audio bestanden, dus ook met mensen die bijna geen woord kunnen zeggen. Wij focussen ons nu op de de fonologie afwijkingen dus deze moesten we eruit filteren.https://drive.google.com/open?id=1DSQH6HAD78IJ_G9AbMLu1JIcBfVK_flhk0uPyBZaF6Q</li>
 <li> Dataset achterhaalt (gesproken corpus nederlands)</li>
 <li>speech2text met google api</li>
 <li>Ook was ik scrummaster dit hele project en heb ik de scrum sessie geleid. </li>
 <li>notuleren</li>
<ul>


 <li>Zoeken naar wetenschappelijke artikelen  </li>
<li>brainstorm sessies leiden en documenteren (voor de deelvragen)</li>

presentaties voorbereid</br>
onderzoeksvragen opgesteld</br>
eerste versie van speech to text gemaakt</br>
datacamp</br>
cousera</br>
Onderzoek gedaan naar fonologie</br>
onderzoek gedaan naar library's.</br>
Contactpersoon</br>
