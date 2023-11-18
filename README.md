# Prva laboratoriska vezba po Mobilni Platformi i Programiranje(MPIP)
## Dimitar Jovanovski 203099

### MainActivity
Sodrzi 3 kopcinja i TextView. Kopcinjata se:
* kopce za start na ExplicitActivity(explicit intent)
* kopce za start na ImplicitActivity(implicit intent)
* kopce za otvaranje na slika(korisnikot bira koja i default aplikacija na uredot na otvara)

### ExplicitActivity
Se startuva samo so explicit intents.  
Sodrzi tekst pole za vnes i kopcinja: 
* "Vo red" - go nosi korisnikot nazad na MainActivity, no negovoto TextView se azurira so teksot vnesen vo ova activity  
* "Otkazi" - se vrakja nazad

### ImplicitActivity
Se povikuva pri akcija mk.ukim.finki.mpip.IMPLICIT_ACTION
Activity-to sodrzi TextView vo koe se izlistani iminjata na klasite na site registrirani Activities vo Android OS so:
* kategorija android.intent.category.LAUNCHER
* akcija android.intent.action.MAIN
