# Trajetória da Aprendizagem

Painel interativo das cinco avaliações de 2026 do Ensino Fundamental — Anos Finais do **PEI Santo Dias da Silva**.

Prova Paulista do 1º, 2º e 3º bimestres, Avaliação Diagnóstica de Entrada do 2º semestre e Simulado SARESP aplicado em 19 de outubro. 474 estudantes, 13 turmas, 130 questões do simulado classificadas por Aprendizagem Essencial nos seis componentes.

## Como abrir

É um arquivo único, sem build. Abra `index.html` no navegador, ou acesse a versão publicada pelo GitHub Pages.

Para publicar: **Settings → Pages → Deploy from a branch → `main` / `(root)`**. O painel responde em `https://<usuário>.github.io/<repositório>/`.

## As três camadas

O painel segue a hierarquia de decisão da escola. Os filtros do topo — segmento, componente e turma — valem para as três camadas ao mesmo tempo.

**Camada 1 · Estratégica — direção e gestão.** Proporção de estudantes em Adequado ou Avançado, trilha das cinco medidas, curva do ano, as duas comparações principais, distribuição por nível, panorama dos seis componentes e as turmas que exigem intervenção.

**Camada 2 · Tática — coordenação pedagógica.** Aprendizagens Essenciais do Simulado da mais frágil à mais consolidada, habilidades BNCC mobilizadas, habilidades do Mapa SARESP medidas pela Diagnóstica, Plano de Ensino × Diagnóstica e variação por componente entre pares de medidas.

**Camada 3 · Operacional — professor e sala de aula.** Mapa de calor questão a questão por turma, itens abaixo de 40% com o distrator mais marcado, grupos de recuperação e a tabela completa de estudantes com busca, filtro por nível e ordenação.

## Componentes

O filtro abre os seis: Língua Portuguesa, Matemática, Ciências, História, Geografia e Língua Inglesa, além da visão conjunta. A leitura padrão é Língua Portuguesa + Matemática.

A Prova Paulista cobre os seis componentes nos três bimestres. A Diagnóstica de Entrada avaliou apenas Língua Portuguesa e Matemática, então as seções que dependem dela ficam indisponíveis nos demais recortes — o painel avisa quando isso acontece.

## Leitura dos dados

O corte dos itens e habilidades é **60% de acerto**; abaixo de 40% o item entra como crítico. Os níveis seguem as faixas da rede: Abaixo do Básico 0–25%, Básico 26–50%, Adequado 51–75%, Avançado 76–100%.

As cinco provas **não são equivalentes**. A série da Prova Paulista é a única plenamente comparável: mesma origem, mesmo formato, três aplicações. O Simulado tem apenas 5 questões de LP e 5 de Matemática no 6º, 7º e 8º ano (10 e 10 no 9º), então cada acerto desloca o componente em 20 pontos percentuais naqueles anos — leia a direção, não a magnitude. No 6º e no 7º ano o Livro 1 da Diagnóstica é mais acessível que a Prova Paulista, e parte do ganho nesse segmento é efeito do instrumento.

## Dados pessoais

O painel identifica os estudantes pelo nome, ao lado de notas individuais, nível de proficiência e habilidades a recuperar. A publicação está amparada no termo de autorização de uso de nome e imagem mantido pela escola.

O repositório inclui `robots.txt` e o cabeçalho `noindex` na página para evitar indexação por buscadores. Isso não restringe o acesso de quem tiver o endereço: convém combinar com a gestão por onde o link circula.

O `.gitignore` mantém fora do versionamento as planilhas, tabulações e PDFs de origem — aqui vai apenas a página publicada.

## Origem

Gerado a partir dos resultados da Prova Paulista por turma, da tabulação do Simulado SARESP, do Relatório da Diagnóstica de Entrada e do Guia do Currículo Priorizado AF 2026, que fornece as Aprendizagens Essenciais e os códigos BNCC. Os arquivos de origem ficam fora deste repositório.
