# Java Lab Codes

A collection of standalone Java exercises. Java source files are kept in `src/`;
unfinished source notes that are not compilable Java are kept in `drafts/`.

## Build

From the project root on Windows:

```powershell
javac -d out src\*.java
```

Run an exercise by its class name, for example:

```powershell
java -cp out hello
```

Other exercises with `main` methods include `Abstraction`, `AgeValidation`,
`LargestNumber`, `MapDemo`, `rectangle`, `Student`, `constructor`, and
`UseCase1` through `UseCase4`. Some examples prompt for console input.

`drafts/student.txt` is preserved as a draft; it contains incomplete Java-like
code and is not included in the build.
