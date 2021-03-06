# API validadora de padrões de senhas
Este serviço deve cumprir os seguintes requisitos:

>Considere uma senha sendo válida quando a mesma possuir as seguintes definições:
>
>- Nove ou mais caracteres
>- Ao menos 1 dígito
>- Ao menos 1 letra minúscula
>- Ao menos 1 letra maiúscula
>- Ao menos 1 caractere especial
>  - Considere como especial os seguintes caracteres: !@#$%^&*()-+
>- Não possuir caracteres repetidos dentro do conjunto

### Exemplo:  

```c#
IsValid("") // false  
IsValid("aa") // false  
IsValid("ab") // false  
IsValid("AAAbbbCc") // false  
IsValid("AbTp9!foo") // false  
IsValid("AbTp9!foA") // false
IsValid("AbTp9 fok") // false
IsValid("AbTp9!fok") // true
```

> **_Nota:_**  Espaços em branco não devem ser considerados como caracteres válidos.
## Problema

Construa uma aplicação que exponha uma api web que valide se uma senha é válida.

Input: Uma senha (string).  
Output: Um boolean indicando se a senha é válida.

## Os pontos a serem destacados neste serviços serão:

Testes de unidade / integração
Abstração, acoplamento, extensibilidade e coesão
Design de API
Clean Code
SOLID

# Funcionamento da API
...
