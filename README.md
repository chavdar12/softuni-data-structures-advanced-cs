# SoftUni Data Structures Advanced with C#

Solutions for the SoftUni Data Structures Advanced with C# course: AVL, 2-3, red-black and AA trees, hash tables and
augmented data structures. Each one has an NUnit test project next to it, all in
[Data-Structures-Advanced.slnx](Data-Structures-Advanced.slnx).

## Lectures

| #   | Lecture | Exercises |
| --- | ------- | --------- |
| 001 | B-Trees, 2-3 Trees and AVL Trees | [AVL Tree](001-B-Trees-2-3-Trees-And-Avl-Trees/AVLTree) |
| 002 | Exercise: B-Trees, 2-3 Trees and AVL Trees | [AVL](002-Exercise-B-Trees-2-3-Trees-And-Avl-Trees/AVL) · [Hierarchy](002-Exercise-B-Trees-2-3-Trees-And-Avl-Trees/Hierarchy) · [Two Three](002-Exercise-B-Trees-2-3-Trees-And-Avl-Trees/Two-Three) |
| 003 | Red-Black Trees and AA Trees | [Red Black Tree](003-Red-Black-Trees-And-Aa-Trees/RedBlackTree) |
| 004 | Exercise: Red-Black Trees and AA Trees | [AA Tree](004-Exercise-Red-Black-Trees-And-Aa-Trees/AATree) · [Red Black Tree](004-Exercise-Red-Black-Trees-And-Aa-Trees/RedBlackTree) |
| 005 | Hash Tables, Sets and Maps | [Hash Table](005-Hash-Tables-Sets-And-Maps/HashTable) |
| 006 | Exercise: Hash Tables, Sets and Maps | [Royale Arena](006-Exercise-Hash-Tables-Sets-And-Maps/RoyaleArena) · [Word Cruncher](006-Exercise-Hash-Tables-Sets-And-Maps/WordCruncher) |
| 007 | Data Structures Augmentation | [Collection of Persons](007-Data-Structures-Augmentation/CollectionOfPersons) |

## Run

Needs the .NET 10 SDK.

```bash
dotnet test Data-Structures-Advanced.slnx
dotnet test Data-Structures-Advanced.slnx --filter "FullyQualifiedName!~Performance"   # skip the slow performance tests, like CI
```

## License

[MIT](LICENSE)
