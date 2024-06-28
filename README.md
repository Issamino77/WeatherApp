# WeatherApp

## Übersicht
WeatherApp ist eine Android-Anwendung, die aktuelle Wetterinformationen für verschiedene Städte weltweit anzeigt. Die App verwendet die WeatherAPI, um Wetterdaten in Echtzeit abzurufen und darzustellen.

## Features
- Anzeige der aktuellen Wetterbedingungen (Temperatur, Luftfeuchtigkeit, Windgeschwindigkeit, etc.)
- Vorhersage für die nächsten Tage
- Suche nach Städten
- Automatische Standorterkennung
- Benutzerfreundliche Oberfläche

## Installation
1. **Voraussetzungen**:
   - Android Studio installiert
   - WeatherAPI Schlüssel (https://www.weatherapi.com/signup.aspx)

## Benutzung
1. **Starten**: Öffne die App auf deinem Gerät.
2. **Städtesuche**: Verwende die Suchleiste, um nach einer Stadt zu suchen und die Wetterinformationen abzurufen.
3. **Automatische Standorterkennung**: Erlaube der App, deinen Standort zu verwenden, um die Wetterinformationen deines aktuellen Standorts anzuzeigen.

## API
Diese App verwendet die [WeatherAPI](https://www.weatherapi.com/), um Wetterdaten abzurufen.

## Struktur des Projekts
- `data/`: Enthält Datenmodelle und Klassen für den Datenzugriff (z.B., `LiveDataEvent.kt`, `RemoteWeatherData.kt`).
- `dependency_injection/`: Module für die Dependency Injection (z.B., `NetworkModule.kt`, `RepositoryModule.kt`).
- `fragments/`: UI-Fragmente für verschiedene App-Bereiche (z.B., `home/`, `location/`).
- `network/`: API- und Repository-Klassen für die Netzwerkintegration (z.B., `WeatherAPI.kt`, `WeatherDataRepository.kt`).
- `storage/`: Klassen für die lokale Speicherung (z.B., `SharedPreferencesManager.kt`).
- `utils/`: Hilfsklassen und -funktionen.
- `MainActivity.kt`: Hauptaktivität der App.
