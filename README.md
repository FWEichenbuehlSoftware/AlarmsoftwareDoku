# AlarmsoftwareDoku

## Übersicht

|Icon|Name|
|------|---|
|🏠| [Home](README.md) |
|ℹ️| [Stichwörter](Stichwörter.md) |
|🎨| [Farben](Farben.md) |

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
D --> B
```

## Vereinfachte Übersicht der Alarmfunktion der Feuerwehr Eichenbühl

### Alarmempfang

```mermaid
graph LR

Leitstelle --> AlarmSMS						--> AlarmHandy				
Leitstelle --> SDS							--> TetraControlFunkgerät	--> TetraControlSDSAlarm
Leitstelle --> ZVEI[ZVEI / 5TonFolge]		--> Bosmon
Leitstelle --> FAX							--> FritzBox

```