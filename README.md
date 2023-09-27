# Markdown

## Table of Contents

- [Markdown Beispiel](#markdown-beispiel)
  - [Table of Contents](#table-of-contents)
  - [Überschriften](#überschriften)
    - [Unterüberschrift 1](#unterüberschrift-1)
      - [Unterüberschrift 2](#unterüberschrift-2)
        - [Unterüberschrift 3](#unterüberschrift-3)
  - [Trennstriche](#trennstriche)
  - [Hervorhebungen](#hervorhebungen)
  - [Aufzählungen](#aufzählungen)
  - [Links](#links)
  - [Quellcode](#quellcode)
  - [Tabellen](#tabellen)
    - [Tabellen mit unterschiedlicher Textausrichtung:](#tabellen-mit-unterschiedlicher-textausrichtung)
  - [Bilder](#bilder)
  - [Blockzitate](#blockzitate)
  - [Fußnoten](#fußnoten)
  - [Durchgestrichene Absätze](#durchgestrichene-absätze)
  - [Task Listen](#task-listen)
  - [Text Highlighting](#text-highlighting)
  - [Hochgestellte und Tiefgestellte Zeichen](#hochgestellte-und-tiefgestellte-zeichen)
  - [Deaktivierte URL-Verknüpfungen](#deaktivierte-url-verknüpfungen)
  - [Footnotes](#footnotes)


## Überschriften

### Unterüberschrift 1

#### Unterüberschrift 2

##### Unterüberschrift 3

<h5> Unterüberschrift 4 Alt. </h3> 

## Trennstriche

---

## Hervorhebungen

*Dieser Text ist kursiv.*

**Dieser Text ist fett.**

***Dieser Text ist kursiv und fett.***

__Dieser Text ist ebenfalls fett.__

## Aufzählungen

- Erster Punkt
- Zweiter Punkt
  - Unterpunkt 1
  - Unterpunkt 2
    1. Geordneter Unterpunkt
    2. Noch ein geordneter Unterpunkt

## Links

[Markdown Guide](https://www.markdownguide.org)

## Quellcode

Einfacher Codeblock:

print("Hello, World!")

python
Copy code

Codeblock mit Syntaxhighlighting (Python):

```python
def greet(name):
    print(f"Hello, {name}!")

greet("Alice")
```

## Tabellen

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Alter</th>
      <th>Stadt</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Max Mustermann</td>
      <td>30</td>
      <td>Wien</td>
    </tr>
    <tr>
      <td>Lisa Schmidt</td>
      <td>25</td>
      <td>Salzburg</td>
    </tr>
  </tbody>
</table>

		
### Tabellen mit unterschiedlicher Textausrichtung:

| Linksbündig     | Zentriert       | Rechtsbündig    |
| :-------------- | :-------------: | ---------------: |
| Dies ist links  | Dies ist zentriert | Dies ist rechts |
| Links ausgerichteter Text  | Zentriert ausgerichteter Text | Rechts ausgerichteter Text |
| Hier ist mehr links  | Hier ist mehr zentriert  | Hier ist mehr rechts  |


## Bilder

![Vault Boy](vaultBoy.png)

## Blockzitate

> Dies ist ein Blockzitat.
> 
> Es kann über mehrere Zeilen gehen.

## Fußnoten

Das ist ein Satz mit einer Fußnote[^1].

## Durchgestrichene Absätze

~~Dieser Text ist durchgestrichen.~~

## Task Listen

- [x] Task 1 - Dieser Task ist abgeschlossen
- [ ] Task 2 - Dieser Task muss noch erledigt werden
- [ ] Task 3 - Dieser Task muss auch noch erledigt werden

## Text Highlighting

<mark style="background-color: #8A2BE2">Dieser Text ist hervorgehoben.</mark>

## Hochgestellte und Tiefgestellte Zeichen

Hochgestelltes: 2<sup>3</sup>

Tiefgestelltes: H<sub>2</sub>O

## Deaktivierte URL-Verknüpfungen

Dies ist eine URL ohne Verknüpfung: [https://www.example.com]()


## Footnotes

[^1]: Hier ist der Text der Fußnote.
