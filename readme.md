## Pierwsze zajęcia:
### Przygotowanie stanowiska do pracy:
  - pobranie obrazu systemu ubuntu
  - instalacja systemu na stacji roboczej
### Pierwsze kroki z terminalem:
```
1. ls                      //wypisuje w postaci listy zawartość katalogu
2. ls --help               //wyswietla pomoc dla podprogramu ls
3. ls -la                  //wyswietla zawartość katalogu z plikami ukrytymi, z prawami dostepu
4. pwd                     //wyswietlenie sciezki do obecnego katalogu
5. clear                   //czyszczenie konsoli
```
### Poruszanie sie po strukturze katalogow
```
6. cd Desktop              //polecenie cd przejscie do katalogu
7. cd /Pulpit
8. cd Pulpit               //przejscie na pulpit
9. mkdir LukaszKu          //tworzenie nowego katalogu
```
### Przygotowanie katalogu pod repozytorium oraz instalacja git
```
10. git                    //"git" wyswietla dodtkowe komendy
11. cd LukaszKu
12. sud apt install git    
13. sudo apt install git   //instalacja git z uprawnieniami administratora
14. git help               //pomoc dla polecenia git
```
### Wykonanie pierwszego pliku oraz dodanie do repozytorium na github
```
15. touch test.txt         //touch z argumentem tworzy (jeżeli jeszcze nie istnieje) 
                           nowy plik o takiej jak argument nazwie
16. ls
17. nano test.txt          //polecenio nano edytuje dany plik
18. ls -la
19. nano test.txt
20. ls -la
21. git init               //inicjalizacja git
22. ls -la
23. git status             //sprawdzenie statusu modyfikacji plikow
24. git add test.txt       //rozpoczyna sledzenie zmian pojedynczego pliku
25. git status
26  git add .              //rozpoczyna sledzenie zmian wszystkich plikow
27. git commit             //dodawanie wykonanych zmian do repozytorium
```
### Polaczenie konta z na github z gitem w lokalnym repozytorum
```
28. git config --global user.email "lukaszkurasz2@gmail.com"  
29. git config --global user.name "LukaszKur"
30. git commit
31. git log                //wyswietlenie zmian w repozytorium
32. ls
33. git status
34. git log
35. git commit -m "nowy plik"
36. git log
37. nano test.txt
38. git status
39. git add . 
40. git status
41. git log
42. nano test.txt
43. git status
44. git add . 
45. git log
46. git commit -m "druga zmiana"
47. git log
48. nano test.txt
49. git status
50. git commit -m "trzecia zmiana"
51. git add . 
52. git commit -m "trzecia zmiana"
53. git log
54. git remote add origin https://github.com/LukaszKur/LukaszKu.git   //dodanie sciezki do repozytorium na github
55. git push -u origin master                                         //inicjalizacja polaczenia
56. git log
57. git status
58. git push -u origin master
59. nano ~/.gitconfig                                 //sprawdzenie pluku konfiguracji git
60. nano test.txt
61. git status
62. git add .
63. git commit -m "Czwarta zmiana"
64. git log
65. git push                                         //wyslanie wyszystkiego do repozytorium na github
```
### 66. history >readme.md                           //przekazanie histori strumieniem do pliku
