# PureORM-AIX

**Generate customised SQLite ORM extensions for visual Android development.**

Developed by **Claudio Olivera — OzDroid Software**

## Overview

PureORM-AIX is an Android wizard that generates Java source code for customised SQLite database extensions.

Designed for developers using **Niotron, Kodular and AndroidBuilder**, it simplifies database access by providing ready-to-use methods for common database operations.

No Java programming is required to generate the source code.

## Features

- Four-step wizard for selecting databases, tables and columns.
- Customised Java source generation.
- Database import and connection management.
- CRUD operations: Create, Read, Update and Delete.
- Automatic primary-key discovery.
- Support for SQLite databases.
- Compatible with Niotron, Kodular and AndroidBuilder.

## How It Works

1. Select an existing SQLite database.
2. Choose the tables to include.
3. Select the required columns.
4. Generate the Java source file.
5. Compile the source using the Niotron Extension IDE.
6. Import the resulting AIX extension into your Android project.

## Generated Extension API

| Method | Description |
|---|---|
| `ImportFromUri` | Import a SQLite database |
| `DatabasePath` | Get the database file path |
| `OpenDatabase` | Open a database |
| `CloseDatabase` | Close the database |
| `GetRecords` | Retrieve table records |
| `GetRecordById` | Retrieve a record by primary key |
| `InsertRecord` | Insert a record |
| `UpdateRecord` | Update a record |
| `DeleteRecord` | Delete a record |

## Download

Download the latest APK and the illustrated User Guide from the repository's **Releases** section.

The User Guide includes installation instructions, screenshots, examples, troubleshooting and the complete API reference.

## Platform Compatibility

PureORM-AIX v1.0 has been successfully tested on:

- Niotron
- Kodular
- AndroidBuilder

Other App Inventor-compatible platforms have not yet been verified.

## Documentation

**PureORM-AIX User Guide — Version 1.0**

55 pages covering the complete workflow, from selecting a database to compiling and using the generated extension.

Available as a PDF in the GitHub release assets.

## Author

**Claudio Olivera**  
OzDroid Software

*Version 1.0 — November 2026*
