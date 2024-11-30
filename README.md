## Latam Community - Language development
Our main repository for storing the languages ​​available on our servers and projects.

### Requirements
> Currently requeriments are not necessary here.

### Available languages
<table>
    <tr>
        <td>Language</td>
        <td>Author(s)</td>
    </tr>
    <tr>
        <td>English</td>
        <td>
            <a href="https://github.com/manucabral">ne0de</a> -
            <a href="https://github.com/larayavrs">tron1q</a>
        </td>
    </tr>
    <tr>
        <td>Spanish</td>
        <td>
            <a href="https://github.com/manucabral">ne0de</a> -
            <a href="https://github.com/larayavrs">tron1q</a>
        </td>
    </tr>
</table>

> As languages ​​are created, they will be added to the list.

### Languages in development
- [Slovak](#)

## Contributing to Latam Languages

### Clone the Repository
First of all, clone our repository using:

```sh
git clone https://github.com/LatamSAMP/languages.git latam-languages
```

### Structure of .ini files
In this repository, all language files are stored in .ini format.

```ini
[general]
welcome=Bienvenido al servidor %s.
welcome_back=Bienvenido de vuelta al servidor %s.
login_text=Esta cuenta (%s) está registrada. Por favor ingresa tu contraseña.
register_text=Bienvenido %s, puedes registrarte ingresando una contraseña aquí abajo.
short_password=La contraseña es muy corta. La longitud mínima es %d letras.
failed_login=Inicio de sesión fallido. Por favor intenta de nuevo. (%d intentos restantes).
success_login=Has iniciado sesión exitosamente.
success_register=Te has registrado exitosamente.
too_many_attempts=Expulsado del servidor por muchos intentos de inicio de sesión fallidos.
register_label=Registrar
login_label=Ingresar
cancel_label=Cancelar
success_label=Éxito
```

### Writing and Translating

#### Guidelines for Translating
- Consistency: Ensure that translations are consistent with the original meaning.

- Placeholders: Maintain placeholders (%s, %d) in the translations.
- Context: Provide translations that fit the context of the game.
- Steps for Translating:
    - Select a Language File: Choose the .ini file you want to translate.
    - Edit the File: Use a text editor to add or modify translations. Ensure each key-value pair is translated accurately.
    - Check for Errors: Validate that there are no syntax errors and placeholders are correctly placed.

### Submitting Your Translation

- Generating a Commit:

    ```sh
    git add Language.ini
    ```

- Generate a conventional commit message

    ```sh
    git commit -m "feat: [language] translation"
    ```

- Push your changes:
    ```sh
    git push
    ```

### Notes
- Make sure your translations are culturally appropriate and contextually accurate.

- If you have any questions or need clarification, feel free to open an issue on the repository.

Thank you for contributing to Latam Community, your efforts help make our server more accessible to a global audience.