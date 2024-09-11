# Puram Sai Rama Raju 
### Volleyball
I love volleyball because it’s fast, fun, and keeps me on my toes. The **teamwork** and connection with others on the court make every game **exciting** and **rewarding**.

---
### Top Volleyball Players
1. Pawel
2. Ajith
3. Sanju
### Places to play
- Beach
- Court
- Grass

[Check out my favorite dish!](MyDish.md)

---

## Favorite Quotes
> "I told my wife she was drawing her eyebrows too high. She looked surprised."
>
> *Tim Vine*

> "Why don't skeletons fight each other? They don't have the guts."
>
> *Bravis*

---

### How to find Intersection using Dart source code
Finds elements that exist in two lists
'''
main() {
  final lists = [
    [1, 2, 3, 55, 7, 99, 21],
    [1, 4, 7, 65, 99, 20, 21],
    [0, 2, 6, 7, 21, 99, 26]
  ];

  final commonElements =
      lists.fold(
        lists.first.toSet(), 
        (a, b) => a.intersection(b.toSet()));

  print(commonElements);
}
'''
[Source](https://stackoverflow.com/questions/59431806/extract-common-elements-from-lists-in-dart)
