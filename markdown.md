# Básico de Markdown (com exemplos)
(2x Enter) Quebra de linha com espaçamento maior.
<br>
<br>
("\\" ou dois espaços vazios no final da frase e apertar Enter) Quebra de linha com espaçamento menor.
<br>
<br>
(#) -> Título de nível 1
<br>
<br>
(** ou __) -> Negrito\
**Essa frase está em negrito.**
<br>
<br>
(* ou _) -> Itálico\
*Essa frase está em itálico*
<br>
<br>
(~~) -> Tachado / Riscado\
~~Essa frase está tachada~~
<br>
<br>
(##) -> Título de nível 2
## Esse é um título de nível 2!
<br>

(###) -> Título de nível 3
### Esse é um título de nível 3!
<br>

(####) -> Título de nível 4
#### Esse é um título de nível 4!
<br>

(#####) -> Título de nível 5
##### Esse é um título de nível 5!
<br>

(######) -> Título de nível 6 (máximo)
###### Esse é um título de nível 6!
<br>

(__*) -> Negrito em itálico\
__*Exemplo de negrito em itálico.*__
<br>
<br>

("1." ; "2". ; "3." ; ...) -> Lista numerada (adicione três espaços antes para um subitem, sempre os subitens começando com 1)
1. Primeiro item
   1. Primeiro subitem do primeiro item
2. Segundo item
3. Terceiro item
   1. Primeiro subitem do terceiro item
   2. Segundo subitem do terceiro item
      1. Primeiro subitem do segundo subitem do terceiro item
<br>
    
( * ou - ) -> Lista demarcada (antes de cada item; adicione três espaços para subitens)
* Teste 1
* Teste 2
   * Teste 2.1
* Teste 3
<br>

(- [ ] ou - [x]) -> Lista de tarefas
- [ ] Eu não fiz isso ainda.
- [x] Eu fiz isso.
<br>

( - ) -> Adiciona uma linha em baixo e deixa tudo que está sem quebra de linha maior (2x Enter) como título de nível 2

Exemplo: Ao adicionar ( - ) logo na linha abaixo
Tudo o que está em cima se tornará um título de nível 2
-
<br>

( = ) -> Adiciona uma linha em baixo e deixa tudo que está sem quebra de linha maior (2x Enter) como título de nível 1

Exemplo: Ao adicionar ( = ) logo na linha abaixo
Tudo o que está em cima se tornará um título de nível 1
=
<br>

(sinal de crase) -> Linha simples de código\
`print('Linha de código simples usando Markdown!')`
<br>
<br>

(sinal de crase triplo)

<img width="169" height="79" alt="image" src="https://github.com/user-attachments/assets/0c2f9063-af90-4c08-b022-9f1db493f14f" />

```python
a1 = float(input())
print(f'O número digitado foi {a1}')
# Você consegue copiar o código facilmente e, inclusive, comentá-lo!
```
<br>
<br>
Estrutura para a criação de uma tabela básica.
<br>
<img width="176" height="71" alt="image" src="https://github.com/user-attachments/assets/fc34f329-ef73-4cd7-af35-ce6e74aacd80" />

| ID | Nome | Nota
---|---|--
001|Carlos|8.9
<br>

(\<br>) -> Quebra a linha de forma forçada (coloque no início de uma linha)
<br>
<br>

( :nome_do_emoji: ) -> Exibe o emoji se o nome for válido.\
Sunglasses (😎)
Handshake (🤝)
<br>
<br>

(\>) ->  Quote Reply
> Será que hoje vai chover?

Acho que não.
