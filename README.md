
# InUppgift2-Api
Teoretiska och praktiska API

#####
1.Vad är skillnaden mellan backend och databas? Beskriv vad respektive ansvarar för.

Svar:
 
```sh
En backend är en kodbas med bland annat funktioner för att behandla data. Den kan räkna ut 
matematik eller hämta enskilda objekt från en databas. Backend innehåller alltid kod 
användaren aldrig ser. Backendkod kallas därför ofta för server-side code

En databas är ett ställe där vi förvarar datan vi använder i både frontend och backend, den kan 
innehålla objekt med användare och rättigheter, och den kan innehålla filmer och bilder. 
Ordet databas kan beteckna informationen som finns lagrad, eller den programvara (databashanterare) 
som förstår att tolka den ofta mycket komplexa datastrukturen som lagras på hårddisken.
Databasen är en låda vi lägger all information i vi har användning av i framtiden.
```
#####
2.Varför är det viktigt att vara konsekvent i sin API-design för att skapa ett användarväntligt API?

Svar:
```sh
Ett bra API underlättar t.ex för oss frontend utvecklare, detta gör det lättare att hämta och 
skicka rätt data och se till att det hamnar på rätt plats i databasen. Ett bra och konsekvent 
API “tänk” gör också att mindre fel och buggar kan förekomma då man själv kan 
bestämma hur vissa scheman ska se ut.
```
#####
3.Vad är autentisering vs auktorisering?

Svar:

```sh
Autentisering innebär att man verifierar identiteten av en användare.
Auktorisering innebär vad en användare har rättigheter att göra.
```
#####
4.Vad är skillnaden mellan "Private Cloud" och "Public Cloud". Vilka typer av 
tjänster erbjuder public cloud

Svar:

```sh
Ett privat, Pirvate cloud är ett företags egna moln av servrar där företaget själv 
ansvarar för drift och underhåll. Ett publikt, Public cloud är ett moln av servrar 
som tillhandahålls och underhålls av en Provider där man kan "hyra" in sig, såsom 
t.ex. azure, google cloud eller amazons AWS. Som consumer är gratis upp till 512gb. 
Behöver man mer utrymme får man hyra betala en slant.
```
#####
5.Varför testar vi mjukvara

Svar:

```sh
Programvarutestning är en typ av kontrollbesiktning som genomförs som ger information om 
kvaliteten på programvaruprodukten eller tjänsten som testas. Det handlar om kontroll, 
att känna till kvalitet och inga "favoriter i repris", alltså tidigare kända fel. 
För det är inte bra.
```

#####
6.Vad är fördelarna med API:er jämfört med en weblösning som går direkt mot en databas?

Svar:
```sh
Om man använder sig av API istället för en client(begränsad till det egna ex 
administrativa nätverket inom organisationen) kopplad front- och backend betyder 
det att man kan använda backenden för flera olika applikationer, t.ex. 
en webbapp och en mobilapp. Det möjliggör även att andra kan få 
tillgång till data om man väljer att göra APIet publikt.

```
#####
7.Vad innebär OAUTH

Svar:

```sh
Att användaren kan logga in via en extern tjänst, t.ex med ett Google konto, 
Facebook twitter Instagram mm. Med detta får vi tillgång till information om 
användaren från tjänsten som användes vid inloggning. Vilket innebär att 
användaren inte behöver hålla reda på ett konto och lösenord till och vi 
ej behöver spara lösenord i våran egna tjänst. 
```

#####
8.Vilka typer av managed services erbjuds av Public Cloud och vad innebär de?

Svar:

```sh
On Premises: Servrar som körs på samma fysiska plats hos företaget/eget ägande. 
Företaget står själv för all hantering och alla kostnader såsom inköp, 
kvalificerade tekniker, bevakning och underhåll.

Infrastructure as a service(IAAS): Server/servrar som tillhandahålls av någon annan som 
inriktad på en sorts hosting. Jag som mjukvarutvecklare ansvarar själv för all kod 
hantering, såsom installation, konfigurering, uppdatering, mm.

Platform as a Service(PAAS): Denna tjänst utför oftast bara en sak, 
till exempel Google App Engine. Dessa låter dig lägga upp en applikation på molnet 
och driver den sedan, du betalar oftast bara för det som "används" av servern och 
slipper tänka på server underhåll. Azure We Apps.Språk begränsningar och accsess problem.

Software as a Service(SAAS): En tjänst du använder eller tillhandahåller. Som Gmail, 
Google Maps, Dropbox eller office 365till grunden ett webbhotell som tillhandahåller 
API: er och / eller Frontends. Använder bara tjänsten. Använder vanligtvis API-nycklar 
för att få åtkomst.

```
#####
9.Vad innebär TDD och BDD?

Svar:
```sh
Testdriven utveckling: TDD (Test Driven Development) handlar om testbarhet och täckning.
Skriv tester först, sedan kod.Typ av enhetstestning som främjar full kodtäckning. 
Hjälper att dela upp problem i testbara bitar Arkitektur och konsistens som en eftertanke.

Beteendedriven utveckling. BDD (Behavior Driven Development) handlar om att kunna 
kommunicera testresultat över organisationer. En agile mjukvaruutvecklingsprocess som 
uppmuntrar samarbete mellan utvecklare, QA och icke-tekniska eller affärsdeltagare 
i ett program. Skriv tester som vanlig text som alla kan förstå. Varje textrad analyseras 
för att köra testkod.
```
