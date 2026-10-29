# Atividades técnicas — Unidade II

Este índice apresenta a versão revisada em 29/10/2026, com foco em infraestrutura, redes, ambientes virtuais, software livre e mediação pedagógica.

## Sete pacotes H5P

Os pacotes estão em [`revisao-tecnica/`](./revisao-tecnica/).

| Atividade | Tipo H5P | Arquivo |
|---|---|---|
| 1. Evolução do hardware e das redes na EaD | Accordion | [`01-evolucao-hardware-redes-ead.h5p`](./revisao-tecnica/01-evolucao-hardware-redes-ead.h5p) |
| 2. Vocabulário técnico de ambientes virtuais | Dialog Cards | [`02-vocabulario-tecnico-ambientes-virtuais.h5p`](./revisao-tecnica/02-vocabulario-tecnico-ambientes-virtuais.h5p) |
| 3. Infraestrutura do ensino híbrido | Interactive Video | [`03-infraestrutura-ensino-hibrido.h5p`](./revisao-tecnica/03-infraestrutura-ensino-hibrido.h5p) |
| 4. Parametrização do marco regulatório | Drag and Drop | [`04-parametrizacao-marco-regulatorio.h5p`](./revisao-tecnica/04-parametrizacao-marco-regulatorio.h5p) |
| 5. Interfaces e distância transacional | Fill in the Blanks | [`05-interfaces-distancia-transacional.h5p`](./revisao-tecnica/05-interfaces-distancia-transacional.h5p) |
| 6. REA em STEM | Course Presentation | [`06-rea-stem-apresentacao-interativa.h5p`](./revisao-tecnica/06-rea-stem-apresentacao-interativa.h5p) |
| 7. Simulador de decisão tecnológica | Branching Scenario | [`07-simulador-decisao-tecnologica.h5p`](./revisao-tecnica/07-simulador-decisao-tecnologica.h5p) |

O vídeo da atividade 3 é um MP4 H.264 de 40 segundos, criado para este material e incorporado ao pacote. Não depende de URL ou vídeo externo. Tem quatro pausas com questões de múltipla escolha.

Na atividade 4, os rótulos simulam dois registros acadêmicos: Engenharia semipresencial e BCT a distância. São exemplos de configuração por modalidade, não dados de cursos reais.

## Atividade 8 — Moodle Workshop

A oitava proposta não é H5P: é uma oficina de avaliação entre pares usando a atividade **Laboratório de Avaliação (Workshop)** do Moodle. A configuração, instruções e rubrica sugerida estão em [`revisao-tecnica/atividade-8-laboratorio-moodle.md`](./revisao-tecnica/atividade-8-laboratorio-moodle.md).

## Importação no Moodle

1. No curso, abra o **Banco de conteúdo** e envie o arquivo `.h5p` desejado.
2. Se o Moodle solicitar a instalação ou atualização de bibliotecas H5P necessárias, confirme ou peça ao administrador para habilitar o tipo de conteúdo.
3. Crie uma atividade H5P no curso e selecione o conteúdo enviado.
4. Ao substituir um conteúdo já usado por uma atividade, edite essa atividade ou crie uma nova; enviar outra cópia ao Banco de conteúdo não troca automaticamente o conteúdo antigo.

Os sete pacotes revisados não dependem da biblioteca personalizada `H5P.Unidade2Theme`. Se quiser aplicar o visual personalizado, o campo **CSS personalizado** nas configurações de H5P do Moodle é o local apropriado: copie o conteúdo de [`theme.css`](./theme.css) sem tags `<style>`.

## Referência e escopo

O fascículo fornece os conceitos-base de EaD, TDIC, LMS/AVA, ensino híbrido, formatos de oferta e educação aberta. Exemplos de nuvem, banda, conectividade e ferramentas STEM são contextualizações técnicas para as atividades — não afirmações de que todo LMS precisa estar na nuvem nem de que todo recurso localizado no GitHub tem licença aberta.

Este repositório contém apenas o conjunto técnico revisado; os pacotes da versão anterior não foram incluídos.
