![bcg](/vacina_bcg2.png)

Análise dos dados de tuberculose fornecidos pelo governo brasileiro. Este projeto faz parte do Bootcamp de Data Science Aplicada da Alura, referente ao Módulo 2.

[Link do Collab](https://colab.research.google.com/drive/1CMgsApubIlmbrXDT-cYSOckqST88-IJe?usp=sharing)

## 🤿 Escopo do Projeto
---

Este projeto utiliza dados do [DataSUS](http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633&VObj=http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sih/cnv/qi), que fornece diversos dados referentes à saúde no SUS (Sistema Público de Saúde), através do aplicativo TabNet.

O objetivo é utilizar os dados da **Cobertura de Vacinação** disponibilizadas pelo SUS para formar informações sobre o imuno **BCG**, responsável por imunizar as pessoas da bactéria da **Tuberculose**. Neste projeto, foi utilizado quatro fontes de dados sobre Tuberculose, que são a Cobertura de Vacinação (CV), casos confirmados, casos filtrados por sexo e casos por faixa etária.

## 🩺 Introdução
---

A **tuberculose** é uma doença bacteriana infecciosa causada pela bactéria *Mycobacterium tuberculosis*, que afeta principalmente os pulmões e também pode atingir outros órgãos, tais como ossos, rins e sistema nervoso. Segundo a **Organização Mundial da Saúde** (OMS), em 2015 foi estimado o número de 10,4 milhões de casos e 1,4 milhões de óbitos pela doença. No mundo, é a enfermidade infecciosa que mais **mata**, e no **Brasil** ela ocupa a terceira posição. [[SBIM]](https://familia.sbim.org.br/doencas/tuberculose-tb)

A pessoa contaminada com **tuberculose** apresenta diversos sintomas graves, principalmente tosse, falta de ar, dores no peito, expectoração de sangue, entre outros. Há situações em que a pessoa contrai a doença, e não apresenta sintomas, porém ainda é possível a transmissão. Felizmente, a **tuberculose** tem cura, e se dá pelo tratamento com medicamentos durante alguns meses. [[SBIM]](https://familia.sbim.org.br/doencas/tuberculose-tb)

A forma de **prevenção** atualmente é a **vacina BCG** (bacilo de *Calmette-Guérin*), obtida através do enfraquecimento de umas das bactérias que causam a tuberculose. [[SBIM]](https://familia.sbim.org.br/vacinas/vacinas-disponiveis/vacina-bcg)

A vacinação é indicada para: [[SBIM]](https://familia.sbim.org.br/vacinas/vacinas-disponiveis/vacina-bcg)
* Crianças de até **cinco anos** de idade, e pessoas com qualquer idade
* Portadores de **hanseníase**. 

E, contraindicada para: [[SBIM]](https://familia.sbim.org.br/vacinas/vacinas-disponiveis/vacina-bcg)
* Pessoas imunodeprimidas
* Recém nascidos de mães que utilizaram medicamentos contra imunodepressão
* Crianças prematuras que tenham menos de 2 kg de peso

Um dos principais **efeitos colaterais** da vacina é uma **cicatriz** característica, no local em que foi aplicada, com um tamanho de até 1cm de diâmetro. Essa cicatriz se inicia com uma **mancha vermelha** elevada, que acaba evoluindo de tamanho e produzido secreção, e posteriormente diminuindo e formando a cicatriz. [[SBIM]](https://familia.sbim.org.br/vacinas/vacinas-disponiveis/vacina-bcg)

É importante salientar que a vacina não garante 100% de proteção na prevenção da **tuberculose pulmonar**, entretanto, a aplicação em massa na população permite a prevenção das variações mais graves da doença, como a **meningite tuberculosa** e a **tuberculose miliar**. A Organização Mundial da Saúde estima que, em países que há a **vacinação** constante nas **crianças**, previne-se mais de **40 mil** casos por ano da **meningite tuberculosa**. [[SBIM]](https://familia.sbim.org.br/vacinas/vacinas-disponiveis/vacina-bcg)

## 📑 Referências
---

[[1] Vacina BCG - SBIM](https://familia.sbim.org.br/vacinas/vacinas-disponiveis/vacina-bcg)

[[2] Tuberculose - SBIM](https://familia.sbim.org.br/doencas/tuberculose-tb)

[[3] O DATASUS](http://www2.datasus.gov.br/DATASUS/index.php?area=01)

[[4] TabNet](http://www2.datasus.gov.br/DATASUS/APRESENTACAO/TABNET/Tutorial_tabNet_FINAL.pptx_html/html/index.html#2)
