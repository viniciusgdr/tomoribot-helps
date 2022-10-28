# TomoriBOT WhatsApp - Comandos
Ajuda de Comandos da TomoriBOT WhatsApp

# Documentação

## DEBUG

* #### Sugerir Comandos
```
    /sugerir [texto]
```
Sugestão de Comandos ou Funções
| Tipo       | Descrição                                   |
| :--------- | :------------------------------------------ |
| `texto` | **Obrigatório**. Sugestão desejada |



* ####  Status do BOT

```
    /ping
```
Retorna o Status do BOT

<details><summary><b>Tipos de Retornos</b></summary>

1. Retorno (Success) - Type: Button:

    ```sh
    Tempo de Resposta: X Segundos
    ```
</details>

## Utilitários
Nenhum dos comandos de "Utilitários" requer administrador.

<details><summary><b>Funções</b></summary>

* #### Recursos do Grupo
```
    /recursos
```
Retorna as funcionabilidades ativas ou desativadas do grupo.

* #### Descrição do Grupo
```
    /desc
```
Retorna a Descrição do Grupo

* #### Ranking
```
    /ranking
```
Retorna os tops rankings do grupo em relação do maior para o menor.

* #### Saldo
```
    /saldo
```
Checar seu Saldo
</details>

## Administração
Os comandos de "Administração" requer administrador.

<details><summary><b>Funções</b></summary>


* #### Fechamento / Abrimento de Grupos
```
    /grp
```

* #### Link do Grupo
```
    /linkgrp
```
* #### Mudar nome do Grupo
```
    /mudarnome [nome]
```
| Tipo       | Descrição                                   |
| :--------- | :------------------------------------------ |
| `nome` | **Obrigatório**. Novo nome do grupo |

* #### Mudar descrição do Grupo
```
    /mudarnome [descricao]
```
| Tipo       | Descrição                                   |
| :--------- | :------------------------------------------ |
| `descricao` | **Obrigatório**. Novo nome do grupo |

* #### Zerar dados do BOT no Grupo
```
    /zerartudo
```
Esta ação apaga todos os dados do grupo, assim tudo será desligado e os membros terão XP, level, etc. zerados.

* #### Banir Usuários
```
    /banir @menção
```
O Usuário será banido do grupo.
| Tipo       | Descrição                                   |
| :--------- | :------------------------------------------ |
| `menção` | **Obrigatório**. Mencionar o usuário que deseja |

* #### Atualizar Admins
```
    /atualizar-admins @menção
```
O Usuário será Promovido/Rebaixado de Administrador
| Tipo       | Descrição                                   |
| :--------- | :------------------------------------------ |
| `menção` | **Obrigatório**. Mencionar o usuário que deseja |

* #### Apagar Mensagem
```
    /atualizar-admins [menção]
```
A Mensagem marcada será deletada
| Tipo       | Descrição                                   |
| :--------- | :------------------------------------------ |
| `menção` | **Obrigatório**. Mencionar a mensagem |


</details>

## Utilitários de Administradores
Funções para moderação do grupo ou aprimoramentos

<details><summary><b>Lista de Funções</b></summary>

* #### Auto Sticker
    ```sh
    /autosticker
    ```

* #### Auto Texto
    ```
    /autotexto
    ```

* #### NSFW
    ```
    /nsfw
    ```
Banimento de imagens/videos inapropriádos.
* #### Anti Fake
    ```
    /antifake
    ```

* #### Anti Link
    ```
    /antilink
    ```

* #### Ativação de Conteúdo +18
    ```
    /porn
    ```
* #### Boas Vindas
    ```
    /welcome
    ```
Anunciar as Boas-vindas ao entrar no Grupo.

<details><summary><b>Customizações</b></summary>

1. Anexar Mensagens
    ```sh
    /setwelcome
    ```

    | Tipo       | Descrição                                   |
    | :--------- | :------------------------------------------ |
    | `texto`  | **Obrigatório**. Mensagem desejada |

2. Desafixar Mensagens
    ```sh
    /delwelcome
    ```
</details>
</details>


## Ghosts

* #### Lista Ghosts
```
    /listaghost [dias?]
```
Retorna todos os Ghosts do Grupo
| Exemplo | Tipo       | Descrição                                   |
|:---------| :--------- | :------------------------------------------ |
| 5| `dias` | (não obrigatório) Dias desejados para começar a contar |

## Diversão

* #### Sorteio de Usuários
```
    /sortear
```
