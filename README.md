# Laboratório: Ferramentas Azure Speech Studio e Language Studio - DIO

## Descrição

Este repositório tem como finalidade documentar a prática com as ferramentas Azure Speech Studio e Language Studio, explorando recursos voltados à análise de fala e linguagem natural.

Durante o laboratório, foram utilizados os seguintes recursos:
- **Tradução de Fala:** Transcrição e tradução automática de um áudio em inglês.
- **Análise de Sentimentos e Opiniões:** Identificação de sentimentos e avaliação de opiniões a partir de diferentes textos.

Assim, demonstrando como essas ferramentas da Microsoft Azure podem ser aplicadas em cenários reais de processamento de linguagem natural e inteligência artificial.

-----

## Atividades Realizadas

### Azure Speech Studio - Tradução de Fala
- Upload de um arquivo de áudio em inglês (música: _God's Plan_ - Drake)
- Detecção automática do idioma original
- Transcrição rápida da fala
- Tradução em tempo real do áudio (Inglês → Português) com baixa latência
- Visualização do conteúdo transcrito em diferentes formatos:
    - Texto original
    - Texto traduzido
    - Estrutura em JSON

#### Insights:
- A ferramenta oferece uma transcrição eficiente, mas a qualidade pode ser afetada por fatores como ruído no áudio e velocidade da fala
- A tradução para o português é clara e compreensível, embora possam ocorrer pequenas perdas de contexto em frases mais complexas
- Altamente personalizável, útil para atividades específicas

---

### Language Studio - Análise de Sentimentos e Opiniões:
- Inserção de diferentes frases e opiniões em inglês para análise automatizada. Frases presente no [Laboratório - Microsoft Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
- Classificação precisas das avaliações como:
    - Positivo
    - Neutro
    - Negativo
- Identificação de confiança (score) atribuída a cada sentimento detectado
- Extração de opiniões específicas dentro de textos mais longos
- Visualização dos resultados em diferentes formatos, incluindo JSON

#### Insights:
- A análise se mostrou eficaz na interpretação de sentimentos simples e diretos
- Em frases com ambiguidade, o modelo pode apresentar incertezas ou classificações imprecisas
- A pontuação de confiança é útil para avaliar a segurança do modelo em cada resposta

---

## Conclusão

Através das atividades realizadas nesse laboratório, foi possível aprofundar meus conhecimentos sobre Inteligência Artificial aplicada ao Processamento de Linguagem Natural (PLN). As ferramentas da Microsoft Azure se mostraram acessíveis, intuitivas e eficazes, mesmo para quem não possui experiência prévia na área. Além disso, a praticidade na interface e a variedade de funcionalidades demonstram o grande potencial dessas soluções em aplicações reais de IA e análise de linguagem.
