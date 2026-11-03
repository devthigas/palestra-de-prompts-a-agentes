# De Prompts a Agentes: A Nova Era da IA

Material completo, roteiro pedagógico e apresentação interativa para a palestra executiva e técnica sobre a evolução dos modelos de linguagem e a transição para agentes autônomos de inteligência artificial.

**Palestrante:** Prof. Thiago  
**Público-alvo:** Estudantes, desenvolvedores, gestores de tecnologia e profissionais de negócios  
**Demonstração Online:** [Acessar Apresentação de Slides (GitHub Pages)](https://devthigas.github.io/palestra-de-prompts-a-agentes/)

---

## Estrutura do Repositório

- `index.html` e `apresentacao_de_prompts_a_agentes.html`: Apresentação interativa de slides autossuficiente desenvolvida em HTML5, CSS3 moderno (tema claro e suporte a modo escuro) e JavaScript puro.
  - Relógio digital em tempo real no rodapé.
  - Navegação via teclado (setas, espaço, home, end) e botões táteis.
  - Painel retrátil de notas do palestrante com cronometragem sugerida por slide.
  - Totalmente responsivo para navegadores desktop, tablets e smartphones.
- `slides_de_prompts_a_agentes.md`: Roteiro de slides com estrutura tópica, citações históricas, dados de mercado e notas completas para condução em palco.
- `palestra_de_ia_terca_feira.md`: Guia aprofundado da palestra contendo fundamentação teórica, análises históricas, contextualização de segurança, arquitetura técnica e roteiro para live demos.
- `imagens/`: Acervo de imagens históricas e técnicas em alta definição utilizadas na apresentação:
  - `pintura_oleo.jpg`: A Mona Lisa (1503-1506) de Leonardo da Vinci e o modelo artesanal de ateliê.
  - `louis_daguerre.jpg` e `daguerre_1838.jpg`: Louis Daguerre e a primeira fotografia de silhueta humana no Boulevard du Temple (1838).
  - `camera_kodak.jpg`: A câmera Kodak Brownie (1900) e o nascimento do snapshot familiar com George Eastman (*"You press the button, we do the rest"*).
  - `smartphone_camera.jpg`: A fotografia moderna e a escala de mais de 5 bilhões de fotos diárias.
  - `ibm_7090.jpg`: Mainframe militar da década de 1960 para cálculos de balística e defesa aérea durante a Guerra Fria.
  - `google_translate.png`: A IA estatística utilitária e acessível na década de 2010.
  - `facial_recognition.jpg`: Redes neurais convolucionais (CNNs) e visão computacional na borda.

---

## Síntese Temática da Apresentação

### 1. A Evolução Histórica da Imagem e o Contraste com a IA
Traça um paralelo contínuo entre a história da arte visual e a inteligência artificial:
- **Do Ateliê à Tinta Pronta:** O trabalho artesanal de moer minérios e a química pesada no ateliê versus a programação imperativa linha a linha dos primórdios da computação.
- **O Daguerreótipo (1839) e o Pânico da Substituição:** O temor dos pintores diante da máquina que desenha com luz e o subsequente florescimento de movimentos artísticos mais abstratos (Impressionismo, Surrealismo).
- **A Democratização com a Kodak (1888/1900):** Como George Eastman transformou o retrato de luxo aristocrático em patrimônio das famílias comuns pelo conceito de *"Você aperta o botão, nós fazemos o resto"* — o precursor histórico do Prompt.
- **Dos Smartphones aos Agentes:** A passagem da ferramenta que auxilia o disparo para o agente autônomo que orquestra todo o processo de ponta a ponta.

### 2. A Trajetória da Inteligência Artificial
- **Década de 1960:** Aplicações militares na Guerra Fria, cálculo de alcance e trajetória de mísseis intercontinentais e processamento de radar pelo Projeto SAGE.
- **Décadas de 1990 e 2000:** Reconhecimento facial por redes convolucionais, detecção biométrica e filtragem estatística.
- **Década de 2010:** A IA cotidiana e invisível através de tradutores automáticos, corretores semânticos e sistemas de recomendação.
- **A partir de 2020:** Modelos de Linguagem de Grande Porte (LLMs), a arquitetura Transformer e a emergência da IA Generativa multimodal.

### 3. A Transição Paradigmática: De Prompts a Agentes
- **Limitações do Chat Tradicional:** O operador humano como intermediário que copia, cola e valida respostas soltas.
- **Arquitetura de Agentes Autônomos:** Ciclos de raciocínio (ReAct), planejamento prévio, reflexão, memória e execução com uso de ferramentas (Terminal, Bash, Web, APIs, Manipulação de Arquivos).
- **Equipes de Agentes Especializados:** Decomposição de tarefas complexas em agentes coordenados com papéis definidos (pesquisa, arquitetura, redação, testes).

### 4. Economia Prática e Casos Reais
- **Monetização Além do Código:** Modelos de negócios com ferramentas No-Code, agências de automação de WhatsApp para negócios locais, catálogos virtuais para e-commerce e localização de conteúdo.
- **Caso Real — Bruno César (Eleições 2026):** Desenvolvedor de 20 anos, estudante da UFRN, que faturou R$ 100 mil em um único dia com investimento de R$ 3 mil ao utilizar *vibe coding* para consumir em tempo real a API pública do TSE e exibir apuração eleitoral com velocidade superior à grande mídia.

### 5. Laboratório ao Vivo e Prática
- Roteiro com 4 cenários práticos:
  1. Padronização e higienização de planilhas desorganizadas via Python.
  2. Construção de dashboard analítico a partir de banco SQLite cru.
  3. Aplicação de conversação em idioma estrangeiro com processamento fonético.
  4. Automação local de triagem e organização de documentos fiscais.

---

## Como Executar Localmente

Como a apresentação foi construída com padrões web puros, não há necessidade de instalação de gerenciadores de pacotes ou compiladores:

1. Clone o repositório:
   ```bash
   git clone https://github.com/devthigas/palestra-de-prompts-a-agentes.git
   cd palestra-de-prompts-a-agentes
   ```
2. Abra o arquivo `index.html` em qualquer navegador:
   ```bash
   xdg-open index.html   # No Linux
   open index.html       # No macOS
   start index.html      # No Windows
   ```

### Atalhos de Teclado na Apresentação
- **Seta Direita / Espaço / Page Down:** Próximo slide
- **Seta Esquerda / Page Up:** Slide anterior
- **Home / End:** Ir para o primeiro ou último slide
- **Tecla N:** Alternar exibição do painel de notas do palestrante
- **Tecla T:** Alternar entre tema claro e escuro
