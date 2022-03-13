# temperaCura - zadanie 3

Podejście bazujące na wykładniczej średniej kroczącej - najnowsze pomiary instrumentów są najważniejsze, jednak uwzględniamy także pomiary historyczne (do godziny). Dodatkowo, aby zmiejszyć wymiarowość, usuwamy te atrybuty, które są najbardziej skorelowane z innymi. Do finalnego modelowania, rzecz jasna, nie wykorzystujemy temperatury jako atrybutu.

Uczenie modelu to XGboost i 10-foldowa kroswalidacja.

# użycie

Najłatwiej uruchomić program w R z użyciem Rstudio - ma on pełne wsparcie dla R notebooks. Uwaga: trenowanie modelu trwa kilka godzin. Do folderu datasets/contest należy wrzucić rozpakowane archiwum konkursowe, nie trzeba rozpakowywać plików gz, program sam rozpakuje. W pierwszym kroku należy poustawiać odpowiednie wartości boolean.