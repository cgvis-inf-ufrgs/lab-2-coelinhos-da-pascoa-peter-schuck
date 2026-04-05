# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: 587553
- **Nome**: Pedro Schuck de Azevedo

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

- Localizar o comando de criação de janela e substituir o nome desta;
- Encontrar a função que desenha os objetos da cena (coelho e esfera);
- Aplicar uma matriz de escalamento na esfera, testando valores até ela estar menor que o coelho e com formato oval;
- Colocar a função de desenho dos coelhos dentro de um for para multiplicar o número de coelhos;
- Alterar a posição do far plane para facilitar a visualização da cena completa;
- Solicitar que um agente de IA faça os coelhos se movimentarem em um círculo ao redor da origem;
- Pedir para o agente que todos os coelhos estejam sempre olhando para o centro do círculo, enquanto se movimentam;
- Requisitar ao agente que a posição no eixo Y dos coelhos se altere conforme eles percorrem o círculo, como se estivessem em uma função seno;
- Fazer novas solicitações para refinar o último passo até atingir o resultado desejado;
- Pedir que 4 coelhos igualmente separados rotacionem em torno de seu eixo Z local, como se estivessem dando uma cambalhota;
- Requisitar que todos os coelhos tenham 2 ovos (esferas escalonadas) rotacionando ao redor de seus eixos X locais;
- Refinar o último passo com mais pedidos, para garantir que os ovos se mantenham de pé durante a rotação;
- Fazer ajustes numéricos manuais (como nos raios dos círculos ou velocidades de rotação) até obter o resultado esperado;

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

- Descrever corretamente para o agente de IA o movimento "para cima e para baixo" dos coelhos ao redor do círculo;
- Fixar com o auxílio do agente o "pico" de altura dos coelhos em determinada posição (x, z) do círculo;
- Fazer com que mudanças manuais no código não fossem apagadas pela próxima iteração do agente de IA;
- Detalhar suficientemente bem para o agente o movimento de "cambalhota" que certos coelhos realizam;
- Instruir o agente para que os ovos permanecessem sempre de pé, seguindo o eixo Y global;

## Você acha que conseguiu resolver o problema de forma adequada?

Sim, creio que meu resultado se assemelha bastante com o vídeo disponibilizado, cometendo, possivelmente, apenas pequenas disparidades na velocidade dos movimentos, rotações e comprimento do raio refente ao círculo que os coelhos percorrem. 

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

O agente de IA utilizado em questão foi o Github Copilot.

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

Talvez fosse mais interessante realizar a atividade depois da aula sobre animação.
