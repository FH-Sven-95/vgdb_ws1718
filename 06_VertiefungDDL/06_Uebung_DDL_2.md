# Übungen

Führe das Skript [DB-Vertreter](./SQL_-_DB-Vertreter.sql) aus.

## Aufgabe 1
Lege für die Tabellen `VERTRETER`, `VERKAUF` und `ARTIKEL` Primary Key Constraints (`PK`) an.

### Lösung
```sql
ALTER TABLE Vertreter
ADD Constraint pkvert Primary Key (vnr);

ALTER TABLE Verkauf
ADD Constraint pkverk Primary Key (unr);

ALTER TABLE Artikle
ADD Constraint pkart Primary Key (anr);
```

## Aufgabe 2
Lege für die Tabelle `VERKAUF` alle notwendigen Foreign Key Constraints (`FK`) an.

### Lösung
```sql
Deine Lösung
```

## Aufgabe 3
Lösche den Foreign Key Constraint `FK_DEPTNO`. Dieser ist für die Spalte `DEPTNO` in der Tabelle `EMP` definiert.

### Lösung
```sql
ALTER Table EMP DROP Constraint FK_DEPTNO;
```

## Aufgabe 4
Lege den benötigten Foreign Key Constraint (`FK`) für die Tabelle `EMP` neu an.

### Lösung
```sql

```

