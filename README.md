# WinForm Hasher (HashApp)

A simple Windows Forms application built in C# to calculate data hashes and verify integrity for text, hex strings, and files.

## Features

The application supports three input modes and three common hashing algorithms:

*   **Input Formats:**
    *   Text: Standard plain text.
    *   Hex: Hexadecimal strings (includes validation for valid string length).
    *   File: Reads file content via a file picker dialog, supporting both Text and Hex modes.
*   **Supported Algorithms:** MD5, SHA-1, and SHA-256 (implemented using System.Security.Cryptography).

## Built With

*   C# (.NET)
*   Windows Forms

## Getting Started

### Prerequisites
*   Windows OS
*   Visual Studio with .NET SDK

### How to Run
1. Clone or download this repository.
2. Open `HashApp.sln` in Visual Studio.
3. Press F5 or click Start to run the application.

## How to Use

1. Select the input format using the dropdown menu (Text, Hex, or File).
   * Note: Choosing "File" opens a dialog to select a file. You will then need to choose whether the file content is Text or Hex.
2. Enter your data in the input box (or select a file path).
3. Check the boxes for the algorithms you want to use (MD5, SHA-1, SHA-256).
4. Click the "Calculate" button to view the generated lowercase hex hashes in the output fields.
