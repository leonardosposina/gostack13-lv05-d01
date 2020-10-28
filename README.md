![GoStack Bootcamp][logo]

### Level 05 - Desafio: GoRestaurant Web

[📑 Instruções do desafio][challenge]
&nbsp; | &nbsp;
[👨🏻‍🎨 Layout do Figma][layout]

---

### 📝 Instruções

1. Executar a *Fake API* com o comando abaixo:

    ```bash
    yarn json-server server.json -p 3333
    ```

2. Fake API

    | Método: | Rota: | Dados: | Descrição: |
    |---------|-------|--------|------------|
    | GET | /foods | | Lista todos os pratos do menu. |
    | POST | /foods | Body: JSON Food{} | Adiciona um prato ao menu. |
    | PUT | /foods/:id | Body: JSON Food{} | Edita um prato do menu. |
    | DELETE | /foods/:id | | Deleta um prato do menu. |

---

### ⚙ Testes

- [x] - `should be able to list all the food plates from your api`: Para que esse teste passe, sua aplicação deve permitir que sejam listados, toda os pratos de comidas que são retornadas da sua fake API.

- [x] - `should be able to add a new food plate`: Para que esse teste passe, você deve permitir que um prato de comida seja adicionado a sua api, adicionando-o também à listagem.

- [x] - `should be able to edit a food plate`: Para que esse teste passe, você deve permitir que um prato de comida seja editado na sua api, editando-o também na listagem.

- [x] - `should be able to remove a food plate`: Para que esse teste passe, você deve permitir que um prato de comida seja removido da sua api, removendo-o também da listagem.

- [x] - `should be able to update the availibility of a food plate`: Para que esse teste passe, em sua dashboard você deve permitir que o status do prato de comida seja alterado entre *Disponível* e *Indisponível*;

[logo]: https://github.com/leonardosposina/gostack13-lv01-d01/blob/master/docs/gostack-bootcamp.png?raw=true
[challenge]: https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-reactjs-crud
[layout]: https://www.figma.com/file/1lK6AVCPybtWeBLCH8B08N/GoRestaurant?node-id=0%3A1
