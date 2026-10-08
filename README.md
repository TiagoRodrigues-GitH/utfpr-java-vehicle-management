# Vehicle Management System in Java

Console and Swing application that registers passenger and cargo vehicles, written to practise object-oriented design in Java.

| | |
|---|---|
| **Author** | Tiago Rodrigues · Universidade Tecnológica Federal do Paraná (UTFPR) |
| **Date** | 2026-06-01 |
| **Context** | Postgraduate Program in Java Technologies, UTFPR (Java I) |
| **Stack** | Java · Swing |
| **Other languages** | [Português](README.pt.md) · [Deutsch](README.de.md) |

> **Resumo (PT).** Sistema de gestão de veículos de passeio e de carga em Java, com interface de console e Swing; exercício de classes abstratas, herança, polimorfismo, interfaces e exceções verificadas.

## Concepts

Abstract and final classes · inheritance and polymorphism · encapsulation · checked exceptions · interfaces · arrays · Java Swing (manual GUI) · events (ActionListener).

## 🧱 Project Structure (based on the diagram)

- `Veiculo` (abstract)
- `Passeio` (final) - Passenger vehicle
- `Carga` (final) - Cargo vehicle
- `Motor`
- `Calc` (interface)
- `VeicExistException` (checked exception)
- `VelocException` (checked exception)
- `Leitura` (helper class for data input)
- `Teste` (main class with menu and GUI)

## ⚙️ Features

- Register passenger and cargo vehicles (max. 5 each)
- Duplicate license plate validation
- Maximum speed validation (80 to 110 Km/h)
- Speed conversion:
  - Passenger: Km/h → M/h (meters per hour)
  - Cargo: Km/h → Cm/h (centimeters per hour)
- Special calculation via `Calc` interface:
  - Passenger: sum of letters in String attributes
  - Cargo: sum of numeric attributes
- Search vehicle by license plate
- Print all vehicles of a given type
- GUI (Activity 08) with manual windows and "Exit" button

  
<img width="720" height="651" alt="Captura de tela 2026-06-01 144641" src="https://github.com/user-attachments/assets/e01df40f-2161-49dd-b8a7-3780e711799f" />



## ▶️ How to run

```bash
javac *.java
java Teste
```
