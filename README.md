# Working with Files in Java

In this module, I studied how to read and write files in Java, as well as how to manipulate directories and file paths.

The focus was on understanding how Java handles file input and output using different classes and approaches.

## Topics Covered
- `File` class (file and directory representation)
- Reading files with `Scanner`
- Reading files with `FileReader` and `BufferedReader`
- Writing files with `FileWriter` and `BufferedWriter`
- `IOException`
- `try` / `catch` / `finally`
- Try-with-resources
- Creating and listing directories
- Handling file paths and extracting information

## Key Concepts
- The `File` class is used to represent files and directories in Java.
- `Scanner` can be used to read text files line by line.
- `BufferedReader` is more efficient for reading large files.
- `BufferedWriter` improves performance when writing files.
- `try-with-resources` automatically closes resources, avoiding memory leaks.
- File operations often throw `IOException`, which must be handled.
- It is possible to create directories and list files programmatically.

## Exercises
The exercises were focused on reading and writing files in real scenarios.

One of the main exercises involved reading a `.csv` file containing product data and generating a new file with calculated values.

- Read file with product name, price and quantity
- Calculate total value (price * quantity)
- Create a new file (`summary.csv`) inside a subfolder
- Write processed data into the new file

This exercise helped reinforce file reading, writing and basic data processing in Java.

---

## 📌 Resumo (Português)

Neste módulo estudei como trabalhar com arquivos em Java, incluindo leitura, escrita e manipulação de pastas.

Aprendi a usar classes como File, Scanner, FileReader, BufferedReader, FileWriter e BufferedWriter, além de entender a importância do tratamento de exceções com IOException.

Também vi na prática o uso do try-with-resources para fechar arquivos automaticamente.

O exercício principal consistiu em ler um arquivo CSV com dados de produtos, processar essas informações e gerar um novo arquivo com os valores calculados, o que ajudou a consolidar o uso de leitura e escrita de arquivos.
