# Projekt 1 — Analiza Sprzedaży E-commerce

## Problem biznesowy
Analiza danych sprzedażowych brytyjskiego sklepu internetowego 
w celu identyfikacji najlepszych produktów i trendów przychodów.

## Dataset
- **Źródło:** UCI Machine Learning Repository — Online Retail Dataset
- **Okres:** Grudzień 2010 — Grudzień 2011
- **Rozmiar:** 541 909 transakcji, 8 kolumn

## Metodologia
1. Eksploracja i czyszczenie danych (usunięcie zwrotów, braków)
2. Inżynieria cech (kolumna Revenue = Quantity × UnitPrice)
3. Analiza Top 10 produktów według przychodu
4. Analiza miesięcznych przychodów

## Key Insights
- **Top produkt:** PAPER CRAFT, LITTLE BIRDIE — £168,470 przychodu
- **Sezonowość:** Wyraźny wzrost przychodów w Q4 (wrzesień–listopad)
- **Rekomendacja:** Analiza Pareto — 20% produktów prawdopodobnie 
  generuje 80% przychodów
- **Uwaga:** Dane z grudnia 2011 są niekompletne (tylko 9 dni)

## Technologie
- Python 3.13, Pandas, Matplotlib
- Jupyter Lab
- Git / GitHub