Essa planilha é utilizada para controlar as máquinas da empresa e ter uma breve noção dos problemas da máquina, como também de quem a utiliza. O método abordado na medição dos problemas da máquina foi uma soma de pesos numéricos que calcula o quanto a máquina possui problemas e não sua qualidade em geral.

## Colunas

**Funcionário** - O nome da pessoa que está utilizando
**Id da Máquina** - Um valor que identifica aquela máquina em específico
**Tipo de Computador** - Se é um Notebook ou Desktop
**Modelo** - O modelo da máquina para facilitar busca de drivers
**Número de Série** - O número que identifica aquela máquina pelo fabricante
**Configuração** - As especificações da máquina em ordem: processador, armazenamento e memória
**Sistema** - O sistema operacional e sua versão
**Periféricos** - Os itens da empresa fora o computador em si
**Tem defeito?** - A lista de defeitos encontrados na máquina, caso tiver

### Colunas de Avaliação de Defeitos

São as colunas que pontuam os defeitos de acordo com o que for observado ou relatado pelo funcionário. São eles:

**Bateria** - 0%, >0%, >25%, >50%, >75% ou Desktop
**Internet** - Sem Internet, Cabo, Wifi, Wifi+Cabo, Cabo Desktop ou Problema Wifi
**Mouse** - Não, Mal funcionamento ou Funcionando
**Teclado** - Não, Mal funcionamento ou Funcionando
**Tela** - Não Funcionando, Problema Severo, Problema Leve ou Funcionando
**Velocidade (RPS = RAM, Processador, Sistema)** - 3 Problemas, 2 Problemas, 1 Problema ou Nenhum Problema
**Temperatura** - Esquentando Muito, Esquentando, Normal
**Áudio/Microfone** - Nenhum, Só Áudio, Só Microfone, Normal, Problema Áudio, Problema Microfone
**Armazenamento** - Falha Total, Cheio, Disco Lento, Normal
**Câmera** - Não Funciona, Funciona, Desktop
**Fonte** - Não Funciona, Mal Contato, Funciona

### Colunas de Controle

São as últimas colunas para controlar as manutenções

**Somatório** - A somatória dos valores da avaliação de defeitos
**Data última manutenção** - Dia em que foi alterado ou consertado algo naquela máquina
**Última Descrição** - Descrição da última manutenção

## Formulário de Manutenção

Esse formulário serve para gravar as alterações das manutenções e mudanças de máquinas. Os campos a serem preenchidos são:

**Id** - Id da Máquina
**Descrição** - Descrição do que foi realizado
**Tipo de Manutenção** - Se foi de Software ou de Hardware
**Data** - Data em que a manutenção foi realizada ou finalizada
**Horário** - Horário em que a manutenção foi finalizada