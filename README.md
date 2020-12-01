# Szablon do sprawozdań
Szablon przygotowany jest pod sprawozdania na AGH, jednak jedyne co wiąże ten dokument z uczelnią to wykorzystane logo.

# Przygotowanie projektu
Na wstępie należy uzupełnić brakujące informacje
## raport.tex
Jest to główny plik projektu. Należy w nim zdefiniować:
- [Tytuł](https://github.com/robgal519/AGHraportTemplate/blob/master/raport.tex#L4)
- [Pod tytuł](https://github.com/robgal519/AGHraportTemplate/blob/master/raport.tex#L5)
- [Autor](https://github.com/robgal519/AGHraportTemplate/blob/master/raport.tex#L6)
- [Data](https://github.com/robgal519/AGHraportTemplate/blob/master/raport.tex#L7)

## Ustawienie tytułu oraz autora w metadanych dokumnetu
Aby ustawić wspomniane parametry należy uzupełnić deklarację ```\hypersetup``` w pliku [documentTemplate.tex](https://github.com/robgal519/AGHraportTemplate/blob/master/documentTemplate.tex#L26-L30)

# Zastosowanie szablonu

Zachęcam do korzystania z derektywy ```\include``` do wklejania dokumentów .tex

Każdy rozdział powinien być w swoim pliku .tex
