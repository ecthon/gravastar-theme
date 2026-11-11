# Gravastar — tema escuro para Visual Studio Code

O Gravastar foi criado para quem passa horas lendo e escrevendo código e quer uma interface escura, colorida e organizada sem depender de cores agressivamente saturadas. O fundo arroxeado profundo dá unidade ao ambiente, enquanto uma paleta fria e acentos bem dosados ajudam a distinguir rapidamente as partes importantes do código.

Mais do que trocar o fundo do editor, o tema estende a mesma linguagem visual à interface do VS Code: seleções, sugestões, abas, terminal, realces, diferenças do Git e estados de diagnóstico. O resultado é uma experiência consistente, feita para manter o foco no trabalho.

## O que torna o Gravastar diferente

- **Hierarquia de sintaxe clara:** roxo destaca palavras-chave e fluxo de controle; ciano identifica tipos e componentes; rosa evidencia funções; verde marca strings; âmbar diferencia números e constantes.
- **Cor com propósito:** variáveis e texto permanecem em tons claros e discretos. Os acentos são reservados para categorias específicas, reduzindo a competição visual entre elementos.
- **Interface coesa:** editor e áreas ao redor compartilham a mesma paleta, incluindo seleção, sugestões, minimapa, terminal, notificações e indicadores do Git.
- **Informação de estado legível:** erros, avisos e informações têm cores próprias, e os realces de bracket ajudam a acompanhar estruturas aninhadas.
- **Realces semânticos:** quando a linguagem fornece essa informação, classes, interfaces, funções, parâmetros e propriedades recebem distinção adicional.
- **Pronto para diferentes tarefas:** inclui estilos para TypeScript/JavaScript, HTML/JSX, CSS, JSON, Markdown, SQL, shell e outros escopos comuns do VS Code.

## Paleta

| Papel | Cor |
| --- | --- |
| Fundo principal | `#181826` |
| Texto principal | `#D8D6E8` |
| Roxo — palavras-chave e foco | `#B18CF2` |
| Ciano — tipos e componentes | `#7FCDEA` |
| Rosa — funções e seletores | `#E68AD2` |
| Verde — strings e inserções | `#8FD6A8` |
| Âmbar — números e avisos | `#F2B076` |
| Vermelho — erros e remoções | `#F0728F` |

A paleta procura equilibrar contraste e distinção entre categorias; a percepção pode variar conforme monitor, iluminação, linguagem e preferências pessoais. O tema não é um produto médico e não promete prevenir ou tratar fadiga visual.

## Instalação

1. No VS Code, abra **Extensions** (`Ctrl+Shift+X`).
2. Pesquise por **Gravastar** e instale a extensão.
3. Abra **Preferences: Color Theme** (`Ctrl+K Ctrl+T`) e selecione **Gravastar**.

### Executar a partir do código-fonte

1. Abra esta pasta no VS Code.
2. Pressione `F5` para iniciar o Extension Development Host.
3. Na janela de teste, abra **Preferences: Color Theme** e selecione **Gravastar**.
4. Para conferir mudanças no tema, edite `themes/gravastar-color-theme.json` e recarregue a janela de teste.

## Uma pausa também faz parte do fluxo

Temas podem contribuir para uma experiência visual agradável, mas não substituem pausas nem ajustes do ambiente. Uma orientação ergonômica conhecida é a regra **20-20-20**: a cada 20 minutos, olhar por 20 segundos para algo a cerca de 6 metros de distância. Ao programar à noite, experimente reduzir o brilho da tela e manter uma iluminação ambiente indireta; evite que o monitor fique muito mais luminoso que o ambiente.

Essas práticas são recomendações gerais, não uma garantia de conforto ou benefício clínico. Ajuste-as às suas necessidades e procure orientação profissional se o desconforto persistir.

## Avaliação qualitativa

Na avaliação subjetiva que acompanhou o desenvolvimento do tema, o Gravastar recebeu **8,8/10** no geral. Os destaques foram a paleta (**9,5/10**), o contraste do código (**9,5/10**), a hierarquia visual (**9,2/10**) e a consistência da interface (**9,2/10**). A legibilidade de elementos secundários recebeu **7,5/10**, um ponto que pode variar conforme o contexto e que merece atenção em testes pessoais.

Essas notas expressam uma avaliação de design, não resultados de estudos clínicos ou testes científicos de usabilidade. Experimente o tema em ambientes claros e com iluminação reduzida: não existe uma polaridade ou paleta universalmente confortável para todas as pessoas.

## Referências

- [TFOS Lifestyle: Impact of the digital environment on the ocular surface (2023)](https://doi.org/10.1016/j.jtos.2023.04.004) — revisão científica sobre o ambiente digital e a superfície ocular.
- [American Academy of Ophthalmology — Computers, Digital Devices and Eye Strain](https://www.aao.org/eye-health/tips-prevention/computer-usage) — orientações gerais sobre uso de dispositivos e fadiga ocular.
- [Cochrane — Blue-light filtering spectacle lenses (2023)](https://www.cochrane.org/evidence/CD013244_blue-light-filtering-spectacle-lenses-visual-performance-macular-back-part-eye-protection-and) — revisão sistemática sobre lentes com filtro de luz azul.
- [W3C — Web Content Accessibility Guidelines (WCAG) 2.2](https://www.w3.org/TR/WCAG22/) — critérios de acessibilidade, incluindo contraste. As diretrizes WCAG são voltadas a conteúdo web e não certificam este tema.
- [Documentação do VS Code — Color Theme](https://code.visualstudio.com/api/extension-guides/color-theme) — referência para desenvolvimento de temas.

## Desenvolvimento

As cores da interface ficam em `colors` e as regras de sintaxe em `tokenColors` no arquivo `themes/gravastar-color-theme.json`. O tema também usa `semanticTokenColors` para linguagens que oferecem tokens semânticos.

## Licença

Distribuído sob a licença [MIT](./LICENSE).
