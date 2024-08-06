---
# Minicurso: **CURSO DE APLICAÇÕES DE SATÉLITE PARA NOWCASTING**
---
**OBJETIVO:** A parte prática do curso tem como objetivo ensinar a utilização dos dados
e produtos de satélite para monitoramento em tempo real e nowcasting
(previsão dentro de um período de 0-6 horas).

---

**EMENTA**: Será abordado os seguintes tópicos

1. Download dos dados do sensor ABI e GLM do GOES-16
2. Transformação da projeção satélite para retangular
3. Plotar imagens em escala de cinza
4. Plotar imagens em escala colorida
5. Gerar imagem do IR combinado com o total de flashes
6. Gerar imagem do IR combinado com a densidade de flashes
7. Rastreamento manual de tempestade e evolução temporal da temperatura de bilho do IR e flashes
---

**DADOS:**
- A parte prática do curso utilizará como informações de entrada os dados do sensor Advanced Baseline Imager (ABI) e Geostationary Lightning Mapper (GLM) abordo do satélite Geostationary Operational Environmental Satellite - 16. O período de dados é referente aos desastres naturais que ocorreram no estado do Rio Grande do Sul entre 26 de abril e 5 de maio de 2024. O INMET registrou para o mês de Maio um total de 617,1 mm, o que indicou uma chuva acima da média no valor de `480,5 mm`. Em adição, a estação pluviômétrica do CEMADEN localizada em Santa Maria (RS) registrou `236 mm` no dia 30 de abril. Os desastres afetaram 2.390.556 pessoas e provocaram a morte de 172 pessoas. 

- Maiores detalhes sobre o evento pode ser encontrado na Nota Técnica emitida pelo [INMET-Eventos Extremos de Março de 2024 no Brasil](https://github.com/evmpython/minicurso_nowcasting_CPAM2024/blob/main/docs/EventosExtremos-Brasil-Maio-2024.pdf) e [CEMADEN - Boletim de Impactos de Extremos de Origem Hidro-Geo-Climático em Atividades Estratégicas para o Brasil – 14/05/2024 ANO 07 Nº 66](https://www.gov.br/cemaden/pt-br/assuntos/monitoramento/boletim-de-impactos/copy4_of_boletim-de-impactos-de-extremos-de-origem-hidro-geo-climatico-em-atividades-estrategicas-para-o-brasil-2013-17-01-2024-ano-07-no-62). 


---

**PROCEDIMENTO REALIZADO:** Os seguintes procedimentos serão realizados nesse código:
1. 1° Passo: Verificações preliminares
2. 2° Passo: Instalando bibliotecas
3. 3° Passo: Download de arquivos auxiliares
4. **Script 01** - Baixando Dados da Nuvem - AWS
5. **Script 02** - Projeção Retangular e Imagem em Níveis de Cinza
6. **Script 03** - Projeção Retangular com Imagem Colorida
7. **Script 04** - Imagem IR + Total de Flashes do GLM
8. **Script 05** - Imagem IR + Densidade de Flashes do GLM
9. **Script 06** - Evolução Temporal da Temperatura de Brilho do IR e Flashes
---

**OBSERVAÇÕES IMPORTANTES**:
1. Este código foi desenvolvido para ser processado no [Google Colaboratory](https://colab.research.google.com/).
2. Os dados estão disponíveis no [github do curso](https://github.com/evmpython/minicurso_nowcasting_CPAM2024).

---

**Equipe:**

Palestrantes/Tutores:
 - Diego Souza - INPE: diego.souza@inpe.br / https://github.com/diegormsouza

 - Thiago Souza Biscaro - INPE: thiago.biscaro@inpe.br / https://github.com/tsbiscaro

 - Douglas Uba - INPE: douglas.uba@inpe.br / https://github.com/uba

 - Enrique Vieira Mattos - UNIFEI: enrique@unifei.edu.br / https://github.com/evmpython

 - Vito Galligani - CONICET/UBA/Argentina: vito.galligani@gmail.com

Colaboradores:
 - Flávio Augusto - UNIFEI: augustoflaviobob@gmail.com
---
