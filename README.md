# Interprozesskommunikation

**Victor Gandsha (1393033)**  
**Abgabe: 27.06.2022**

Diese Dokumentation beschreibt die Implementierung eines Echtzeitsystems mit vier Prozessen, die über verschiedene Methoden kommunizieren und sich synchronisieren.

## 📌 Kernaspekte
- **Kommunikationsmethoden**:
  - **Pipes**: Einfache Datenweitergabe zwischen Prozessen.
  - **Message Queues**: Nachrichtenbasiertes Kommunikationssystem.
  - **Sockets**: Kommunikation über Netzwerkgrenzen hinweg.
  - **Shared Memory mit Semaphoren**: Effiziente Datenteilung mit Synchronisation.

## 🔧 Implementierte Features
- **Zufallszahlen-Generierung und Speicherung**
- **Berechnung von Summen und Mittelwerten**
- **Synchronisation durch Semaphoren**

## 🚀 Fazit
Shared Memory war die komplexeste Implementierung, während Sockets als moderne und einfachere Lösung betrachtet wurde. Pipes, Message Queues und Sockets synchronisieren sich selbst, während Shared Memory zusätzliche Steuerung durch Semaphoren benötigt.

## 📚 Literaturverweise
- Verschiedene technische Dokumentationen und Online-Ressourcen (z. B. Stack Overflow, Linux Man Pages)
