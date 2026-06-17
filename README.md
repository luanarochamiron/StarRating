# Star Rating Widget - CodingNepal

Um componente de avaliação interativo (Star Rating Widget) minimalista, elegante e totalmente responsivo desenvolvido exclusivamente com HTML5 e CSS3. O projeto apresenta o clássico sistema de classificação por cinco estrelas, utilizando seletores avançados para gerenciar estados de seleção e preenchimento cromático de forma leve, sem a necessidade de scripts JavaScript.

## Tecnologias Utilizadas

* HTML5: Estruturação semântica do componente através de inputs de tipo radio (`<input type="radio">`) ocultos para gerenciar a pontuação e elementos `<label>` associados para renderizar os ícones de estrelas.
* CSS3: Estilização completa, definição de formas vetoriais limpas, gerenciamento de cores e efeitos de transição.
* Animações/Transições em CSS: Utilização de efeitos sutis de escala e mudança de cor ao passar o mouse (*hover*) e ao selecionar uma nota.

## Funcionalidades e Técnicas Aplicadas

* Sistema de Avaliação Interativo em CSS Puro: Uso técnico da pseudo-classe `:checked` em combinação com o seletor irmão geral (`~`) para iluminar de forma reversa todas as estrelas anteriores à opção selecionada, garantindo a lógica clássica de preenchimento.
* Microinterações de Hover Dinâmicas: Efeito visual configurado para preencher temporariamente as estrelas à medida que o usuário passa o cursor sobre elas, oferecendo um feedback intuitivo de pré-seleção.
* Design Minimalista e Focado: Layout limpo em tons de cinza fosco para o estado inativo e dourado/amarelo brilhante para o estado ativo, posicionado sobre um plano de fundo branco puro para eliminar distrações periféricas.
* Alinhamento Simétrico com Flexbox: Distribuição horizontal contínua e perfeitamente equilibrada das cinco estrelas no centro exato da tela.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone 
