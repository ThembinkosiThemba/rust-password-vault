# Password vault with Rust

## 1. Introduction <a name="introduction"></a>

Rust Password Vault is a command-line password management tool written in Rust. It allows users to securely store and manage their passwords for various services. The manager uses JSON files to store password entries.

## 2. Features <a name="features"></a>

- Add new password entries with service name, username, and password.
- List all stored entries.
- Search for entries based on service name.
- Securely stores passwords in a JSON file.

## 3. Usage <a name="usage"></a>

To run the program, simply run :
```bash
cargo run
```

### Menu Options <a name="menu-options"></a>

1. **Add Entry**: Allows the user to add a new password entry by providing the service name, username, and password.
2. **List Entries**: Displays a list of all stored password entries.
3. **Search**: Allows the user to search for entries based on the service name.
4. **Quit**: Exits the program.
