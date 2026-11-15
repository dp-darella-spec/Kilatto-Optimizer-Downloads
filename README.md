<p align="center"><img src="kilatto-logo.png" width="120" alt="Kilatto Optimizer"></p>

# Kilatto Optimizer

Otimizador de Windows em português, feito para quem joga. Cada ajuste pode ser desfeito.

## Baixar

**[Baixar a versão mais nova](https://github.com/dp-darella-spec/Kilatto-Optimizer-Downloads/releases/latest)** e rodar o arquivo `KilattoOptimizer-Setup-x.y.z.exe`.

- Windows 10 (1809 em diante) ou Windows 11, 64 bits.
- Depois de instalado, o Kilatto avisa sozinho quando sai uma versão nova e se atualiza.
- Se aparecer "O Windows protegeu o computador", clique em **Mais informações** e depois em **Executar assim mesmo**. O instalador ainda não tem certificado de assinatura digital.

## Conferir o arquivo (opcional)

Cada versão traz um arquivo `.sha256`. No PowerShell, dentro da pasta de Downloads:

```powershell
Get-FileHash .\KilattoOptimizer-Setup-3.1.2.exe -Algorithm SHA256
```

O resultado tem que ser igual ao número que está no `.sha256`. A atualização automática faz essa conferência sozinha.

Este repositório guarda só os instaladores.
