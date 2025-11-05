# UtilidadesBiblioteca

Biblioteca em C# para geração de relatórios JSON a partir de listas genéricas.  
Ideal para projetos que precisam exportar dados de forma simples, rápida e reutilizável.

---

## 📦 Instalação

Via NuGet Package Manager:
https://www.nuget.org/packages/UtilidadesBiblioteca

Via NuGet Package Manager:

```powershell
Install-Package UtilidadesBiblioteca

dotnet add package UtilidadesBiblioteca

✅ Esse formato usa **bloco de código com linguagem**, assim o GitHub exibe com destaque correto.

---

### Agora, para continuar o README, cole também a próxima parte:

```md
---

## ✅ Exemplo de Uso

```csharp
using UtilidadesBiblioteca;

class Program
{
    static void Main(string[] args)
    {
        var dados = new List<object>
        {
            new { Nome = "Maria", Idade = 30 },
            new { Nome = "João", Idade = 25 }
        };

        var gerador = new GeradorDeRelatorio();
        gerador.GerarRelatorio(dados, "relatorio.json");

        Console.WriteLine("Relatório gerado com sucesso!");
    }
}




