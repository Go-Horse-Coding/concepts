# 📦 O que são métodos?

Um *método* é um bloco de código **nomeado** que implementa alguma ação ou cálculo que pode ser executado.

Métodos são declarados da seguinte forma:
```C#
void MyMethod()
{
    // Executa ção ou cálculo...
}
```

Os métodos também podem retornar valores, basta atribuir o **tipo** do valor a ser retornado ao método.
```C#
int MyAge()
{
    return 25;
}

string MyName()
{
    return "Felipe";
}
```

E no exemplo a seguir, atribuimos o valores dos métodos `MyAge` e `MyName` as váriaveis `age` e `name`:
```C#
int age = MyAge();

string name = MyName();
```

# Referência
* [Methods](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/language-specification/classes#methods)