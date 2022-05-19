# Teste para vaga de Estagiário Dev Web

O objetivo deste teste é entender o candidato, sua experiência e sua capacidade de resolução de problemas com dúvidas e detalhes que serão exigidos no dia-a-dia como Estagiário em Desenvolvimento Web.
O teste é baseado em questionamentos e problemas a serem resolvidos.

### Como será feito o teste?

O teste é dividido em 2 etapas:

- Questões teóricas.
- Projeto prático, quer seja correção de bug ou criação do mesmo.

O candidato precisa criar um repositório próprio com a seguinte estrutura:

- No README serão respondidas as questões teóricas (pergunta e resposta), de forma organizada e explicada.
- No próprio repositório estará o projeto prático, corrigido e/ou criado.

Após a finalização, o candidato deve enviar um e-mail para suporte@b7web.com.br com o link do repositório original ([este](https://github.com/suporteb7web/0522-estagiowebdev)) bem como o link do repositório pessoal com a resolução.

-------------------------------------------------------------------------

## Questões Teóricas

1. Qual a função do "head" no HTML?

    É o cabeçalho, serve para informar detalhes como o título da página, metadados e links, por exemplo.

2. Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?

    Não, deve-se usar o design responsivo para que ela adapte-se aos vários tipos de tela.

3. O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem?

   Não

4. Qual a função das tags H (h1, h2, h3, etc) no HTML?

   São usadas em títulos e subtítulos nas páginas web.

5. O que é SEO e como funciona?

   São técnicas usadas para a otmização do mecanismo de busca, para buscar melhor posicionamento nos buscadores como o Google, por exemplo.

6. O uso de media query é obrigatório em todas as páginas?

    Não, geralmente é usada apenas quando se faz necessário ajustes de responsividade.

7. Qual a diferença entre CSS Inline e CSS em um arquivo?

   O CSS em um arquivo deixa o código mais limpo e organizado, além de facilitar a manutenção.

8. Como criar animações no CSS? Dê um exemplo.

    Primeiro se cria os frames da animação, depois aplica-se a animação a um elemento.

    ```
    // criando os frames

    @keyframes Animation {
        from {background-color: red;}
        to {background-color: yellow;}
    }

    // aplicando a animação no elemento

    div {
        width: 100px;
        height: 100px;
        background-color: red;
        animation-name: example;
        animation-duration: 4s;
    }
    ```

    exemplo retirado do [w3schools](https://www.w3schools.com/css/css3_animations.asp)

9. Qual a diferença entre class e ID no CSS?

    Vários elementos podem possuir a mesma class, equanto O ID deve pertencer a apenas um elemento.

10. Quais os diferentes tipos de seletores CSS?

    tags, class (.), Id (#)

---------------------------------------------------------------------------------------

## Projeto prático

O candidato deve criar a página da imagem a seguir:
![Layout](https://i.ibb.co/Bydq2FZ/screencapture-spotify-br-2022-05-10-15-13-17.png)

Algumas observações importantes:

- Fazer a página responsiva não é obrigatório, mas a apresentação dos elementos deve ser o mais próximo possível da imagem.
- Todas as imagens necessárias estão neste repositório, na pasta "assets".
- Efeitos de hover não são obrigatórios, mas são um plus.

O candidato deve estar atento para obedecer principalmente as cores corretas e tamanhos aproximados.
