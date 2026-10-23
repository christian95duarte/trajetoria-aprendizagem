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

## Projeção SARESP 2026

A pasta `projecao-saresp/` traz uma página à parte, no formato do boletim oficial: Nota Final por etapa, Nota Global, participação e as notas por componente do 6º ao 9º ano e da 1ª à 3ª série do EM, mais a projeção por turma. Publicada em `https://<usuário>.github.io/<repositório>/projecao-saresp/`.

A conversão para a escala do SARESP usa as próprias coortes: o boletim 2025 das turmas que hoje estão no 7º, 8º e 9º comparado com o índice de acerto delas em 2026 (Prova Paulista dos três bimestres, pesos 20%, 30% e 50%). Os cenários conservador e otimista vêm do 1º e do 3º quartis dessa relação. A Nota Global usa peso 1,5 para LP e MAT, que reproduz as Notas Globais de 2025. A página só traz médias por ano e turma, sem nomes de estudantes.

O Ensino Médio tem uma aba própria, projetada pela Prova Paulista do EM dos três bimestres (planilhas de exportação da rede, sem nomes de estudantes). A conversão usa as coortes 2ª 2026 ← 1ª 2025 e 3ª 2026 ← 2ª 2025, com fator por componente (média entre o do componente e o geral), e a Nota Global com peso 3 em LP e MAT, que reproduz as Notas Globais do EM em 2025. Na 3ª série, GEO, BIO, QUI e SOC não são aplicados na Prova Paulista e repetem a nota da coorte em 2025.

Atenção: no Simulado do 9º ano, os percentuais de CIE, HIS, GEO e LI da tabela de estudantes deste painel estão contados em dobro. A projeção corrige dividindo por dois.

## Dados pessoais

O painel identifica os estudantes pelo nome, ao lado de notas individuais, nível de proficiência e habilidades a recuperar. A publicação está amparada no termo de autorização de uso de nome e imagem mantido pela escola.

O repositório inclui `robots.txt` e o cabeçalho `noindex` na página para evitar indexação por buscadores. Isso não restringe o acesso de quem tiver o endereço: convém combinar com a gestão por onde o link circula.

O `.gitignore` mantém fora do versionamento as planilhas, tabulações e PDFs de origem — aqui vai apenas a página publicada.

## Origem

Gerado a partir dos resultados da Prova Paulista por turma, da tabulação do Simulado SARESP, do Relatório da Diagnóstica de Entrada e do Guia do Currículo Priorizado AF 2026, que fornece as Aprendizagens Essenciais e os códigos BNCC. Os arquivos de origem ficam fora deste repositório.
