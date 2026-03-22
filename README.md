#Mikrocontroller-Implementierung_eines_einfachen_Kalkulators

Dieses Projekt implementiert einen einfach Kalkulator, bestehend aus einer PC‑Anwendung zur Eingabe mathematischer Ausdrücke und einer Mikrocontroller‑Anwendung auf Basis eines Arduino Uno R3, das die Berechnung durchführt.

---

Das Gesamtsystem besteht aus zwei zentralen Komponenten:

1. ** PC **
  - Benutzereingabe
  - UART-Sender
  - UART-Empfänger
  - Datenspeicher
  - Ergebnisanzeige

2. ** Arduino **
  - Initialisierung der seriellen Schnittstelle
  - UART-Empfänger
  - Parser
  - Recheneinheit
  - UART-Sender
