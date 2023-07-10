Przykładowe wiadomości najczęściej w pliku messages.yml

### Przykład 1
```yaml
testowe-wiadomosci:
  chat: Wyświetlam się na czacie
  actionbar: Wyświetlam się na actionbar
  title:
    title: Wyświetlam tytuł
    subtitle: Wyświetlam podtytuł
    fade-in: 10
    stay: 20
    fade-out: 10
  bossbar:
    name: Wyświetlam się na bossbarze
    color: GREEN
    overlay: PROGRESS
    progress: 0.5
    stay: 20
```

---

### Przykład 2 - Wiadomość tekstowa
```yaml
# Przykładowa wiadomość
przyklad: Jakaś tam wiadomość wyświetlana na czacie

# Lista wiadomości
przyklad-listy:
- To jest wiadomość 1
- To jest wiadomość 2
- itd...
  
# Przykład wyświetlanej wiadomości tylko dla konsoli 
przyklad:
  console: true
  message: To jest wiadomość tylko dla konsoli
```

### Przykład 3 - Wiadomości + dźwięk
```yaml
# Wiadomość tylko na czacie z dzwiękiem
test-dzwieku-tylko-czat:
  chat: Cześć, pojawiam się na czacie i wysyłam dźwięk :)
  sound:
    name: minecraft:ui.button.click
    source: MASTER
    volume: 1.0
    pitch: 1.0

# Wiadomość na czacie, actionbarze i title z dzwiękiem
test-dzwieku-tylko-czat:
  chat: Cześć, pojawiam się na czacie i wysyłam dźwięk :)
  actionbar: Hejka, dźwięk klikniętego przycisku
  title:
    title: Uwaga
    subtitle: Wysłałem dźwięk klikniętego przycisku
    fade-in: 10
    stay: 20
    fade-out: 10
  sound:
    name: minecraft:ui.button.click
    source: MASTER
    volume: 1.0
    pitch: 1.0
```
