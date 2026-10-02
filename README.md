# Guia Digital da Rede de Atenção Psicossocial do Distrito Federal

Projeto de Extensão Curricularizada — Centro Universitário IESB
Tema norteador 2026/2: **Saúde Mental**
Grande área: Tecnologia e Inovação
Autor: Yuri Victor de Oliveira e Silva — Ciência da Computação

---

## Sobre o projeto

O Brasil consolidou, a partir da Reforma Psiquiátrica, da Lei nº 10.216/2001 e da
Portaria nº 3.088/2011, uma rede pública e gratuita de cuidado comunitário em saúde
mental: a Rede de Atenção Psicossocial (RAPS). A rede existe. O que a literatura
aponta como barreira persistente é o desconhecimento da população sobre quais
serviços a compõem, o que cada um oferece e como acessá-los.

O problema, portanto, não é a ausência de política pública, mas a distância entre a
política existente e quem precisa dela. É uma lacuna de informação — e é aí que a
Ciência da Computação pode contribuir.

Este projeto desenvolve uma **plataforma web mobile-first**, construída a partir de
dados públicos oficiais, que organiza por região administrativa os pontos de atenção
da RAPS no Distrito Federal e explica, em linguagem simples, o que cada serviço faz e
como chegar até ele.

## Questão de pesquisa

> De que forma uma plataforma web mobile-first, construída a partir de dados públicos
> oficiais, pode ampliar o conhecimento da população do Distrito Federal sobre os
> serviços da Rede de Atenção Psicossocial e facilitar o acesso a eles, respeitando os
> requisitos de acessibilidade digital e de proteção de dados sensíveis?

## Objetivo geral

Desenvolver uma plataforma web mobile-first que organize e torne acessível à população
do Distrito Federal a informação sobre os serviços da RAPS, reduzindo as barreiras
informacionais de acesso ao cuidado em saúde mental.

## Objetivos específicos

1. Identificar, na literatura e em documentos técnicos, as principais barreiras de
   acesso aos serviços da RAPS no Brasil.
2. Levantar, em fontes oficiais (CNES, Secretaria de Saúde do DF), os pontos de atenção
   da RAPS no território e suas informações de funcionamento.
3. Caracterizar o público-alvo e suas dificuldades de acesso à informação, por meio de
   escuta junto à comunidade parceira.
4. Descrever os requisitos funcionais e de acessibilidade da plataforma, com base nas
   diretrizes WCAG e na Lei Brasileira de Inclusão.
5. Desenvolver a plataforma, organizando os serviços por região administrativa.
6. Avaliar a usabilidade e a utilidade percebida junto a usuários da comunidade parceira.
7. Verificar a conformidade da solução com a LGPD.

## Limites éticos

> Este projeto **não** realiza triagem, diagnóstico, acolhimento, acompanhamento
> psicológico ou qualquer atividade privativa de profissionais legalmente habilitados.
> Ele organiza informação pública e encaminha as pessoas aos serviços competentes.

Essa delimitação segue o item "Da Reflexão à Ação" da cartilha do tema norteador e é
reforçada pela literatura, que registra expansão acelerada de aplicativos de saúde
mental sem evidência de eficácia proporcional.

## ODS relacionados

| ODS | Metas | Relação com o projeto |
|-----|-------|------------------------|
| 3 — Saúde e Bem-Estar | 3.4, 3.8 | Promoção da saúde mental e acesso a serviços essenciais |
| 5 — Igualdade de Gênero | 5.2 | Visibilidade de serviços de apoio a mulheres em situação de violência |
| 16 — Paz, Justiça e Instituições Eficazes | 16.10 | Acesso público à informação como condição do direito à saúde |

## Estrutura do repositório

```
.
├── docs/            Documentos do projeto (introdução, fichamento, mapa)
├── referencias/     Artigos e documentos técnicos consultados
├── diagnostico/     Registros da escuta à comunidade e levantamento do território
├── dados/           Dados dos pontos de atenção da RAPS/DF
├── prototipo/       Protótipos de interface
└── src/             Código-fonte da plataforma
```

## Documentos

| Documento | Caminho |
|-----------|---------|
| Introdução (ABNT) | `docs/introducao.docx` |
| Fichamento dos achados | `docs/fichamento-dos-achados.docx` |
| Mapa do projeto | `docs/mapa-do-projeto.png` |

## Principais referências

- AMARANTE, Paulo. *Loucos pela vida: a trajetória da Reforma Psiquiátrica no Brasil.*
  2. ed. Rio de Janeiro: Fiocruz, 1995.
- BRASIL. **Lei nº 10.216, de 6 de abril de 2001.** Dispõe sobre a proteção e os
  direitos das pessoas portadoras de transtornos mentais.
- BRASIL. Ministério da Saúde. **Portaria nº 3.088, de 23 de dezembro de 2011.**
  Institui a Rede de Atenção Psicossocial (RAPS).
- IBGE. *Pesquisa Nacional de Saúde 2019: percepção do estado de saúde, estilos de
  vida, doenças crônicas e saúde mental.* Rio de Janeiro: IBGE, 2020.
- PATEL, Vikram et al. The Lancet Commission on global mental health and sustainable
  development. *The Lancet*, v. 392, n. 10157, p. 1553-1598, 2018.
  <https://doi.org/10.1016/S0140-6736(18)31612-X>
- SAMPAIO, Mariá Lanzotti; BISPO JÚNIOR, José Patrício. Rede de Atenção Psicossocial:
  avaliação da estrutura e do processo de articulação do cuidado em saúde mental.
  *Cadernos de Saúde Pública*, v. 37, n. 3, e00042620, 2021.
  <https://doi.org/10.1590/0102-311X00042620>
- WHO. *World mental health report: transforming mental health for all.* Geneva: WHO,
  2022. <https://www.who.int/publications/i/item/9789240049338>

## Status

Em desenvolvimento — disciplina de Projeto de Extensão, 2º semestre de 2026.

---

**Em caso de sofrimento psíquico, procure ajuda.** O Centro de Valorização da Vida (CVV)
atende 24 horas pelo telefone **188**. Em emergência, procure a UPA mais próxima ou
ligue para o SAMU (**192**).
