# Konfiguracja środowiska dla aplikaji z Polymer 2.0

Node - wersja nie nowsza niż 11.15.0
Bower - najnowsza wersja (npm install -g bower)
Polymer 1.6.0 (npm install -g polymer-cli@1.6.0)

# Uruchomienie projektu

Dla projektów tylko z Polymer 2.0
wchodzimy w folder trunk dla danego projektu następnie:
bower i
polymer serve

Dla projektów LitHtml + Polymer 2.0

| #   | npm                         | yarn                  |
| --- | --------------------------- | --------------------- |
| 1   | bower i                     |                       |
| 2   | npm i                       | yarn install          |
| 3   | npm run dev / npm run start | yarn dev / yarn start |

Projekt domyślnie uruchamia się na http://127.0.0.1:8080/

## Przydatne oprogramowanie

Pozwala na zainstalowanie więcej niż jednej wersji node'a. https://github.com/coreybutler/nvm-windows

## Dokumentacja

- Polymer 2.0 - https://polymer-library.polymer-project.org/2.0/docs/devguide/feature-overview
- VaadinComponents - https://vaadin.com/components
