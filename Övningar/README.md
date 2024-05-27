![header-fu-react](https://user-images.githubusercontent.com/54267140/144246962-b4140129-ddcf-4609-857a-eaf117a95d81.png)

# Övning 1 - Zustand
1. Skapa en ny react-applikation
2. Skapa komponenterna Counter och Buttons.
3. I Counter skriver du endast ut aktuell siffra för din counter. I Buttons lägger du in 2 knappar, en för plus och en för minus.
4. Skapa en store-mapp i src-mappen. I store-mappen skapar du filen counter-store.ts.
5. Importera Zustand och skapa upp din store. Den skall bestå av counter (som håller värdet för din counter), samt funktionerna decreaseCounter och increaseCounter. Vid anrop av funktionerna skall värdet i counter ökas/minskas. Glöm inte att typea upp din store, använd ChatGPT första gången för att se hur det bör se ut.
6. Exportera din store.
7. Importera din store i både din Counter- och din Buttons-komponent.
8. I din Counter-komponent hämtar du ut couter från din store, och i din Buttons-komponent hämtar du ut dina funktioner från din store.
9. Rendera ut värdet av din counter-tillståndsvariabel i din Counter-komponent, och lägg till funktionerna på dina knappar i din Buttons-komponent.

# Övning 2 - Zustand
Återvänd till övningen [Bokhandeln](https://github.com/MU23FRONTEND/vecka19_react/tree/main/%C3%96vningar/state%C3%B6vningar) som vi kodade upp för ett par veckor sedan. Implementera global statehantering genom att skapa en store som håller koll på antalet böcker som användaren lägger till i sin cart, istället för att ha en vanlig tillståndsvariabel som är skapad med useStae i din App.tsx, och som du sedan skickar som props.

# Övning 3 - Zustand
Skapa upp en valfri applikation som använder sig av Zustand. Använd dig gärna av ett axios.get-anrop som hämtar data och sparar ner den i en array i din store. Importera sedan datan i andra komponenter och använd den på något kul sätt.