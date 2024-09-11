## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

## Learnings:

## The Expression problem:
    1. Types: Adding operations is a problem where you have to write operation for the base class as it is abstract and implement that operation for every type there is. Which means I have to ovveride the new abstract method for every class. Which mean editing for every class. 
    2. Operations: Adding types is a problem where you have modify every function there in existance to write conditions for that type
## The Visitor pattern:
    It allows you to extend operations without modifying or writing a unique code for the existing classes, by introducing a new layer of abstraction. Now I can add operations without changing the code and putting conditions in every function for the new type.
## Pretty Printing:
    Converting a tree to a string is sort of the opposite of a parser, and is often called “pretty printing” when the goal is to produce a string of text that is valid syntax in the source language.