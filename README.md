# Model-Ekonometryczny
# Prosty Model Predykcyjny na Przykładowych Danych

## Opis projektu
Projekt ma na celu przeprowadzonej prostej analizy danych i predykcji w Excelu. Wykorzystano regresję wieloraką oraz analizę trendów do określenia istotnych czynników wpływających na populację bażantów.

## Dane wejściowe
Dane obejmują:
- **Y**: Liczba bażantów w Polsce (w tysiącach)
- **X1**: Liczba odstrzelonych bażantów
- **X2**: Powierzchnia obszarów prawnie chronionych (ha)
- **X3**: Powierzchnia pożarów łąk i pastwisk (ha)
- **X4**: Powierzchnia zasiewów roślin zbożowych (ha)
- **X5**: Powierzchnia lasów (ha)

Dane pochodzą z oficjalnych statystyk GUS i obejmują okres kilku dekad.

## Modelowanie
1. **Regresja krokowa**: Przeprowadzono selekcję zmiennych metodą regresji krokowej, wybierając najbardziej istotne predyktory.
2. **Regresja wieloraka**: Ostateczny model ma postać:
   \[
   Y = -0.0009X1 + 0.0005X2 - 0.0024X3 + 0.0016X4 + 0.00001X5 - 5102.89
   \]
3. **Testy**: Przeprowadzono test Goldfelda-Quandta, White'a, Reset, Durbina-Watsona, Jarque-Bera do analizy heteroskedastyczności, liniowości i rozkładu.
4. **Analiza trendów**: Badano trendy hiperboliczne i paraboliczne zmiennych, aby określić ich wpływ na populację bażantów.




