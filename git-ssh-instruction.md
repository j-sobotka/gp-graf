# Konfiguracja dostępu do git'a przez SSH

## Dla MAC OS:

- Wystarczy wykonać kroki w instrukcji
  https://docs.github.com/en/enterprise/2.13/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
- Wykonać dowolną polecenie do repo np. git clone (w celu dodania git'a do know_hosts ~/.ssh)

## Dla Windows

1. Wygenerować klucz zgodnie z instrukcją najlepiej uzywając algorytmu RSA. 
https://docs.github.com/en/enterprise/2.13/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent (Interesuje nas tylko sekjca  Generating a new SSH key)
2. Dodać swój klucz do git'a
https://docs.github.com/en/enterprise/2.13/user/articles/adding-a-new-ssh-key-to-your-github-account
3. Zainstalować w Funkcjach opcjonalnych systemu windows Klienta OPEN SSH
4. Uruchomić komędę start-ssh-agent (https://stackoverflow.com/questions/18683092/how-to-run-ssh-add-on-windows)
5. OPCJONALNIE: Wykonać dowolną polecenie do repo np. git clone (w celu dodania git'a do know_hosts ~/.ssh)

### Na Windowsie odradzam dodawanie passphrase dla naszego klucz'a :-)
