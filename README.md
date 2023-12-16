# projeto-simulador-piano
 ## Projeto de estudo construindo um Simulador de Piano com JavaScprit.
 
Esse código JavaScript cria um piano virtual em uma página da web. Aqui estão os principais pontos:

**Seleção de Elementos HTML:**

**pianoKeys:** Seleciona todas as teclas do piano no documento HTML com a classe "key" dentro de um elemento com a classe "piano-keys".
**volumeSlider:** Seleciona o controle deslizante de volume no documento HTML.
**keysCheck:** Seleciona uma caixa de seleção no documento HTML.
**Variáveis e Objeto de Áudio:

**mapedKeys:** Um array vazio que será preenchido com as teclas mapeadas.
audio: Um objeto de áudio que reproduzirá os sons das teclas, inicializado com o som "a.wav".
Função para Tocar a Nota:

**playTune:** Uma função que recebe uma tecla como parâmetro, atualiza o arquivo de áudio, reproduz o som, destaca visualmente a tecla clicada e remove o destaque após 150 milissegundos.
Evento de Clique nas Teclas Visuais:

Adiciona um ouvinte de evento de clique a cada tecla visual.
Ao clicar em uma tecla, a função playTune é chamada com a tecla associada, reproduzindo o som correspondente.
Evento de Pressionar Teclas do Teclado:

Adiciona um ouvinte de evento de tecla pressionada no documento.
Se a tecla pressionada estiver mapeada, a função playTune é chamada para reproduzir o som correspondente.
Função para Lidar com o Controle de Volume:

**handleVolume:** Atualiza o volume do objeto de áudio conforme o valor do controle deslizante de volume.
Função para Mostrar/Ocultar Teclas:

**showHideKeys:** Alterna a classe "hide" em cada tecla para mostrar ou ocultar as teclas.
Eventos de Entrada para Controle de Volume e Mostrar/Ocultar Teclas:

Adiciona ouvintes de eventos para o controle deslizante de volume e a caixa de seleção.
Quando o usuário interage com o controle deslizante, a função handleVolume é chamada para ajustar o volume.
Quando a caixa de seleção é clicada, a função showHideKeys é chamada para mostrar ou ocultar as teclas do piano.
Em resumo, o código cria uma experiência interativa onde o usuário pode tocar um piano virtual, ajustar o volume e mostrar/ocultar as teclas visuais do piano.
 [Clique aqui]().
