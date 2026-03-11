# 🛠️ Maker Tool v7.7.0

A high-performance CLI utility for encoding scripts into binary `.mkr` files and executing them across different environments (Java & Python) with built-in local hosting.

## 🚀 Quick Install
1. Clone this repository.
2. Run `install_maker.bat` (Windows).
3. Open a new terminal and type `maker`.

## 📖 Features
- **Binary Encoding:** Convert plain text code into `.mkr` binary files.
- **Smart Runner:** Automatically detects if a file is Java or Python using `.inf` metadata.
- **Java Import:** Convert existing `.java` files into the Maker ecosystem.
- **Local Hosting:** Quickly host your project folder on a local port.
- **Logging:** Full audit trail of actions in `log.txt`.

## ⌨️ Command Reference
| Command | Description |
| :--- | :--- |
| `maker --file [name] --text [code] --extension [py/java]` | Create new binary script |
| `maker --run [file].mkr` | Execute script (Auto-detects type) |
| `maker --import` | Convert a .java file to .mkr |
| `maker --list` | List all local .mkr and .inf files |
| `maker --host [port]` | Start a local web server |
| `maker --delete [name]` | Remove script and metadata |
| `maker --version` | Show current version (7.7.0) |

## 🛠️ Requirements
- Python 3.x
- Java JDK (for Java execution)
