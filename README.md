# Simulador Visual de Fissuras

Aplicativo em um único arquivo HTML, com modelo 3D de uma edificação residencial em concreto armado e alvenaria, para vistorias e treinamentos. É puramente visual, sem cálculo estrutural: você gira o modelo, clica num elemento, escolhe a ação e as fissuras aparecem com o padrão característico, acompanhadas de legenda com a causa provável e a configuração típica.

## Como usar

1. Baixe o repositório (botão **Code → Download ZIP**, ou `git clone`).
2. Abra o `index.html` no Chrome ou no Edge.

Não precisa instalar nada, mas é necessário estar conectado à internet: o Three.js é carregado de uma CDN.

## O que tem

- **Fissuras estruturais:** recalque de fundação, flexão, cisalhamento, torção, flecha em balanço, esmagamento de pilar, pilar tracionado, corrosão de armadura e a comparação entre estrutura isostática e hiperestática.
- **Movimentações térmicas:** expansão e retração da laje.
- **Alvenaria:** fissuras escalonadas, fissuras horizontais nas juntas, falha de verga e contraverga, e risco de infiltração.
- **Interfaces:** encontro pilar–alvenaria com e sem tela/ferro-cabelo, e falha de encunhamento.
- **Revestimentos:**
  - argamassado: fissuras mapeadas e retração;
  - cerâmico: peças trincadas, descolamento/estufamento, fissura no recorte e piso oco, com corte mostrando os vazios na argamassa.
- **Teste de percussão:** som cheio ou cavo gerado no próprio navegador.
- **Controles:** intensidade de leve a severa, exagero da deformada, camadas (estrutura, alvenaria, reboco, cerâmica, umidade) e plano de corte.
- **Modo de edição:**
  - planta com grade e vista 3D;
  - inserir, mover, redimensionar e apagar pilares, vigas, paredes, lajes, balanços, pisos, portas e janelas;
  - definir pavimentos e pé-direito;
  - desfazer e refazer.
- **Arquivos:** salvar e abrir modelos em JSON.

Um sobrado de 2 pavimentos vem como exemplo inicial.
