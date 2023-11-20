# Jogo do Número Secreto
![image](https://github.com/htadmg/numero-secreto/assets/124289385/c5659858-7788-4575-9642-cebc474458d4)

Este é um jogo simples em JavaScript onde o jogador tenta adivinhar um número secreto entre um intervalo definido.

## Funcionalidades

- Geração aleatória de um número secreto entre valores pré-definidos.
- Reconhecimento de voz para inserção dos palpites do jogador.
- Validação dos palpites inseridos.
- Feedback visual sobre a aproximação do palpite em relação ao número secreto.
- Opção para jogar novamente.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript

## Como Jogar

1. Abra o arquivo `index.html` no seu navegador.
2. O jogo irá indicar o intervalo em que o número secreto está localizado.
3. Utilize o reconhecimento de voz para dar seu palpite sobre o número.
4. O jogo fornecerá feedback se o palpite é maior, menor, ou se acertou o número secreto.
5. Ao acertar, você terá a opção de jogar novamente clicando no botão fornecido.

## Estrutura do Projeto

- `index.html`: Contém a estrutura da página web.
- `style.css`: Arquivo de estilos CSS para a aparência do jogo.
- `app/sortearNumero.js`: Lógica para gerar o número secreto aleatório.
- `app/reconhecimentoDeVoz.js`: Implementação do reconhecimento de voz.
- `app/validacao.js`: Funções de validação dos palpites e tratamento de resultados.

## Como Contribuir

Se deseja contribuir com melhorias, correções de bugs ou implementação de novas funcionalidades, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch com a sua feature: `git checkout -b minha-feature`.
3. Faça commit das suas alterações: `git commit -m 'Implementação da minha feature'`.
4. Faça push para a branch: `git push origin minha-feature`.
5. Abra um Pull Request.

## Autor

Agata Domingues Farias

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).
