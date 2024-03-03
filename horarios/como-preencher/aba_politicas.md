## Como Preencher a Aba '```Período```'

[Voltar para a Aba anterior](./aba_periodo.md)

<p align="left">
  <img src="../../imagens/foto aba politicas.png" alt="Imagem Aba Políticas">
</p>

## Aplicar Padrão CLT
Essa opção irá configurar automaticamente alguns campos para o padrão previsto na Consolidação das Lei de Trabalho.

### Efeitos do Padrão CLT:
- **Aba Geral:**
    - **Tolerância Geral:** 00:10 (10 minutos).
- **Aba Política Noturno:**
    - **Início Noturno:** 22:00 (10 horas da noite);
    - **Fim Noturno:** 05:00 (5 horas da manhã);
    - **Uma Hora em Noturno:** 52:30 (52 minutos e 30 segundos).
- **Aba Política de Intervalo:**
    - **Tempo Mínimo de Intervalo:** 01:00 (1 hora).
- **Aba Extra de Interjornada:**
    - **Interjornada:** 11:00 (11 horas).

## Aba Geral

### Seção Geral
 - **Nome da Política:** Define o nome da política. Servirá para reutilizar essas configurações em políticas futuras.

 - **Situação Cadastro:** Escolha entre ```Ativo``` e ```Inativo```, por padrão ele será **Ativo**, caso selecione **Inativo**, o horário será desconsiderado.

 - **Hora do Fechamento da Marcação:** Por padrão é ```00:00```, esse horário define quando o sistema irá considerar a troca de um dia para o outro, ou seja, caso o colaborador bata o ponto às 23:00 do dia 22/01 e depois bata novamente às 01:00 do dia 23/01, a marcação irá aparecer no dia 23/01. [Clique aqui para melhor entendimento.](./para-melhor-entendimento/hora_do_fechamento_da_marcacao.md)

### Seção Tolerância
 - **Tipo de Tolerância:** Sempre deixaremos como ```Diário```.
 - **Tolerância Geral:** Tempo máximo de tolerância por dia, ou seja, caso definada para 10 minutos ```00:10```, o sistema não tolerará extras ou atrasos acima desse tempo.
 - **Considerar Integral:**
    - Ativado: Desta forma, todo atraso ou extra que ultrapassar a tolerância geral será considerado.
    - Desativado: Desta forma, o sistema irá subtrair a tolerância do atraso ou extra, ou seja, se tiver ```15 minutos``` de atraso e ```10 minutos``` de tolerância, o colaborador vai ficar com ```5 minutos``` de atraso.

### Seção Falta
Esta é uma seção mais avançada e esse conteúdo ainda não foi feito, por enquanto, ignore-a.

## Aba Política de Noturno

### Observações
Por enquanto, vou limitar as configurações apenas nos pontos mais importantes e inicias, as configurações mais avançadas vamos deixar para depois.

### Funções Essenciais
- **Início Noturno:** Valor que indica o horário que o sistema irá começar a considerar o início do ```adicional noturno```.

- **Fim Noturno:** Valor que indica o horário que o sistema irá parar de considerar as horas como ```adicional noturno```.

- **Uma Hora em Noturno:** Esse é o valor que irá indicar quantas horas o sistema precisa para considerar 1 hora de extra noturno, no exemplo da foto, a cada ```52 minutos e 30 segundos``` o sistema irá adicionar ```1 hora``` de adicional noturno para o colaborador.

- **Separar extra noturno:** Caso ativo, o sistema irá considerar o ```Extra Noturno``` (horas feitas entre o início e fim do noturno) separado do ```Extra``` convencional.

## Aba DSR

### Definição DSR
```Descanso Semanal Remunerado```, é o período de descanso remunerado concedido ao trabalhador após uma semana de trabalho. <br>Exemplo: Um funcionário que trabalha de segunda a sexta-feira tem direito a um dia de descanso remunerado no sábado ou domingo, conforme as regulamentações trabalhistas. Esse período de descanso é pago, garantindo equilíbrio entre trabalho e lazer.

#### Deixe essa parte com as configurações padrões por enquanto.

## Aba Política de Intervalo

- **Tempo mínimo de Intervalo:** O tempo mínimo que o colaborador deve fazer de intervalo.

- **Extra de intervalo:** Caso ativo e o funcionário faça menos tempo de intervalo do que deveria, o sistema irá considerar esse período como ```extra```.

- **Separar extra de intervalo:** Caso ativo, o sistema irá considerar que as horas extras feitas relacionadas ao intervalo, serão consideradas ```Extra de Intervalo``` ao invés de apenas ```Extra```.

- **Intervalo variável:** Caso ativo, o intervalo será variável, ou seja, mesmo que você tenha definido o horário de intervalo para ```12:00``` às ```13:00```, o colaborador poderá bater o ponto das ```14:00``` às ```15:00```.

## Aba Compensação

Deixe essa parte com as configurações padrões por enquanto.

## Aba Extra Interjornada

Deixe essa parte com as configurações padrões por enquanto.

Após finalizar essas configurações, clique em ```Finalizar Políticas```.

[Ir para a próxima Aba](./aba_vincular_funcionarios.md)