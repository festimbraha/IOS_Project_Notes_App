# IOS_Project_Notes_App

Aplikacioni i koduar eshte nje aplikacion per te mbajtur shenime (Notes) ku mund te ruhen Notes,  te editohen, te fshihen dhe te kerkohet nje Note specifike.
Ky eshte nje projekt ne gjuhen programuese SWIFT i koduar ne XCODE 12.1. XCODE 12.1 përfshin SDK për iOS 14.1, iPadOS 14.1, tvOS 14, watchOS 7 dhe macOS Catalina 10.15.6. ose me lart.<br>
<img src="https://img.icons8.com/color/144/000000/xcode.png"/>
## Funksionimi i Aplikacionit 


Aplikacioni permban dy Views: Njera per shfaqjen e Notes ne nje TableView ne rreshta dhe tjetra per editim te Notes pas klikimit te Notes perkates ne view-ne paraprake. Ne kete projekt eshte i implementuar kalimi nga nje View ne tjetren dhe navigimi.
### List Note View
Sic shihet edhe ne figuren e meposhtme, aty shfaqen shenimet perkatese sikurse: titulli i Note qe e kemi shkruar, kohen se kur eshte shkruar (ose perditesuar per heren e fundit) dhe mundesia qe permes swipe te fshihet (ku na shfaqet nje alert ne rast qe shenimi eshte fshire me sukses). Ne pjesen e eperme shihet pjesa e Search-it ku mund te kerkojme per nje Note specifike, ndersa ne pjesen e poshtme te View-se, na shfaqet numri i shenimeve se sa jane dhe nje Button per shkrimin e nje Note te re dhe na drejton ne View-ne tjeter. Secila Note e re e shkruar na shfaqet ne top te listes, se bashku me detajet e cekura me lart. <br>
Tek pjesa e siperme e Search, aty nevojitet te shenohet vetem titulli i Notes ose dicka qe lidhet me tekstin brenda Notes dhe menjehere do te gjendet ajo note e cila eshte kerkuar.

<p align="center">
<img width="182" alt="ios 5" src="https://user-images.githubusercontent.com/52571480/196057796-51242ee5-4390-4d85-a5c7-e16b55ea5893.png">
</p>

### Edit Note View
Ne kete View mundesohet qe te shkruajme shenimet qe deshirojme ose te perditesojme ato paraprake. Aty mund te shenohen numer i pakufizuar i karaktereve, ku pjesa e fillimit shfrytezohet si titull i asaj Note. Ne menyre qe te ruhet ky shenim, duhet vetem te shkojme back (te pjesa me shigjete < MyNotes) permes nagivigimit te zbatuar ne projekt. Pasi te ruhet shenimi dhe kthehemi ne ListView-ne, ne krye te listes shfaqet Note qe e ruajtem me detajet e saj.
<p align="center">
<img width="179" alt="IOS 2" src="https://user-images.githubusercontent.com/52571480/196058684-4c56752a-ff2f-46fb-8524-bd8933760c5a.png">
</p>

#### Fshirja e nje Note ne Aplikacion

Ne kete aplikacion gjithashtu eshte i mundesuar fshirja e ndonje prej shenimeve. Krejt cka duhet te bejme eshte te veprojme me swipe ne Note qe deshirojme t'a fshijme dhe nese eshte fshire me sukses na shfaqet mesazhi (Alert) se Notes eshte fshire dhe eshte larguar nga lista dhe pastaj ndryshon renditja e Notes tjera varesisht nga pozita.
<p align="center">
<img width="208" alt="IOS 3" src="https://user-images.githubusercontent.com/52571480/196059334-9f5c7ab2-f781-49df-b2e9-d10b408e743d.png">
</p>




