<h1 style="text-align: center; font-size: 2.5em; font-weight: bold;">Lo sviluppo degli algoritmi</h1>

## Variabili e costanti
aa

## Strutture dati
aa

### Gli array
bb

### Pila e Coda

### La lista

### Gli alberi

## Strutture di controllo

### struttura di selezione if-then-else

### Struttura di iterazione for-endfor

### Strutture di iterazione repeat-until e while-endwhile

!!! danger "Algoritmo: ricerca binaria"
    ```python
    1   procedure ricbin(in N, Arr, X; out pos)
    2       first = 1
    3       last = N
    4       pos = -1
    3       while (first <= last  and  pos == -1) do
    4           m = (first+last)/2
    5           if (Arr(m) == X) then
    6               pos = m
    7           else
    8               if (X < Arr(m)) then
    9                   last = m-1
    10              else
    11                  first = m+1
    12              endif
    13          endif
    14      endwhile
    15  end procedure
    ```
