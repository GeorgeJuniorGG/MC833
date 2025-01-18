# MC833 - Network Laboratory

Welcome to the **MC833 Network Laboratory** repository! This repository contains implementations of **TCP** and **UDP** sockets, developed as part of the course. The code is designed to help understand and experiment with socket programming concepts.

---

## 📁 Folder Structure
- **[`TCP_socket/`](./TCP_socket/)**: Contains the implementation of a **TCP socket**, along with a `Makefile` to compile the code.
- **[`UDP_socket/`](./UDP_socket/)**: Contains the implementation of a **UDP socket**, along with a `Makefile` for compilation.

---

## 🛠️ Requirements
- **SQLite**: The implementations use SQLite for data handling. Ensure that SQLite is installed on your system before running the programs.
- **C Compiler**: A C compiler (e.g., `gcc`) is required to compile the code using the provided `Makefile`.

---

## 🚀 Getting Started
### 1. Clone the Repository
```bash
git clone https://github.com/your-username/MC833.git
cd MC833
```
### 2. 🛠️ Install Dependencies
Ensure that SQLite is installed:
```bash
sudo apt-get install sqlite3 libsqlite3-dev   # For Debian/Ubuntu
```
### 3. Compile the Code
Navigate to the desired folder (TCP_socket or UDP_socket) and run:
```bash
make
```
### 4. Run the Programs
After compiling, execute the programs as follows:
```bash
./<program_name>
```
## 📄 Details
TCP Socket: Implements a server-client model over TCP. Allows reliable communication with guaranteed delivery of messages.
UDP Socket: Implements a server-client model over UDP. Provides faster communication with minimal overhead but does not guarantee delivery or order.
Each implementation showcases:

+ Socket creation and setup
+ Data transmission between server and client
+ Proper use of SQLite for data management

## 🧰 Troubleshooting
If you encounter issues while compiling or running the code:

Verify that SQLite is installed and accessible.
Ensure the Makefile is present and configured correctly.
Check for system-specific socket or library dependencies.
## 📫 Contact
For any questions, suggestions, or issues, feel free to open an issue or contact the repository owner.
