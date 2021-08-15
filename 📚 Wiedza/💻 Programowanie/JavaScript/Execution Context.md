To abstrakcyjny koncept środowiska w którym **interpretowany i wykonywany jest kod [[🎖️ JavaScript]]**. Za każdym razem gdy uruchamiamy kod JS, dzieje się to w [[Execution Context]]

Wyróżniamy trzy rodzaje kontekstu wykonania: 
- Globalny - istnieje tylko jeden w programie [[🎖️ JavaScript]]
- Funkcyjny - tworzony jest w chwili wykonania funkcji. Każda funkcja posiada swój kontekst wykonania.
- Eval - kod wykonywany wewnątrz funkcji Eval również posiada swój kontekst.

Konteksty wykonania przechowywane są w tzw. [[Execution Stack]] do którego domyślnie trafia Globalny kontekst a następnie według zasady LIFO (last in, first out), pozostałe konteksty zostają do niego dodawane oraz usuwane. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/Hb0RG60gwh8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>