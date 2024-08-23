# Laboration 1
# Detta är en för detta enklare laboration som ofta har till klasser som ej är fokuserade på programmering. Ni kan istället använda den för att öva. Vi går sedan igenom svaren på lektionstid.

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
