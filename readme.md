# Laboration 1
## LÄS DETTA FÖRST
**Deadline**: 2024/04/03 (Onsdag 3e april 23:59)

**Deadline Komplettering 1**: 2024/04/10 (Onsdag 10e april 23:59)

**Deadline Komplettering 2**: 2024/04/15 (Måndag 15e april 23:59)

**Betyg**: U, G, VG - Du kan inte få VG på kompletteringar. VG fås genom att du genomfört samtliga uppgifter, samt båda VG-delarna på ett självsäkert sätt med välformaterad, pythonic kod.


## Inlämning
Ta bort alla onödiga filer, din kod bör vara på den huvudsakliga branchen "main" eller "master".
Se till att du körde git clone på din EGEN repository för labben.
Feedback ges via en speciell branch som skapas automatiskt, mer information om detta får du av utbildaren.

## Regler
Laborationen är individuell, och du ska inte använda AI-assisterad hjälp för att lösa uppgiften. Öva istället på att googla dig fram till svaret. Chattbottar / LLM-modeller likt chatGPT får endast användas att beskriva enskilda koncept. Att däremot skicka in en hel uppgift och be om en lösning är strikt förbjudet - detta hjälper dig inte träna på egen problemlösning, eftersom du deligerar tänkandet till någon annan. Jag märker väldigt enkelt när svar är AI-genererade!

## Beskrivning:
Du ska svara på frågorna. Du kommer antingen behöva svara med text, kod eller båda samtidigt. 
Du kan utnyttja kommentarer i python för att skriva text med # (hashtag-symbolen)
Eller så kan du skapa ett markdown-block och sedan skriva text.
För att sedan lägga till kod kan du skriva 

\```python 

Kod här inne

\```

# Exempelfråga & Exempelsvar:

Vad är en lista, och varför är den viktig? Svara med text och kod.

Svar:
Listor är användbara eftersom vi kan gruppera data på ett logiskt sätt. Utan listor hade vi behövt spara allt i enskilda variabler, vilket inte är skalbart för en applikation. Vad händer om vi exempelvis har 100000 studenter och alla behöver en variabel?

```python
# Idiotiskt:
student_1 = "Tobias"
student_2 = "Alfred"
student_3 = "Elina"
student_4 = "Jessica"

# Bra
students = ["Tobias", "Alfred", "Elina", "Jessica"]
student_1 = students[0]
```
