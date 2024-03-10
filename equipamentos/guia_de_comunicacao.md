[Voltar para a página anterior](../horarios/README.md#entendendo-o-cadastro-de-horário)

Sejam muito bem-vindos ao **guia de comunicação** para os equipamentos DIXI. Aqui, você aprenderá como realizar a comunicação/sincronização de informações entre o sistema e nossos aparelhos mais utilizados, como o **IREP**, **SINDNOX** e **COLETOR FACIAL**.

Antes de seguirmos para as configurações essenciais e a ordem cronológica dos procedimentos necessários, é válido apresentar nossos equipamentos, aqueles que estabelecem comunicação direta com o WEBDIXI.

# INTRODUÇÃO

### **— EQUIPAMENTOS**

## IREP

> Equipamento biométrico, com batida de ponto também pela matrícula e/ou crachá.

**Descrição:** O equipamento apresenta versões nas portarias **671** e **1510**, destacando-se por suas funcionalidades biométricas. É capaz de realizar a identificação facial e leitura das impressões digitais do funcionário, o número de série localiza-se abaixo do teclado numérico.

Os procedimentos devem ser executados diretamente no equipamento físico ou alternativamente, a comunicação pode ser realizada por meio do web server, uma interface web que facilita a interação e configuração. [Clique aqui para saber mais.](###)

## SINDNOX

> Equipamento biométrico, com batida de ponto também pela matrícula e/ou crachá.

**Descrição:** O SINDNOX é um equipamento semelhante ao IREP, dispondo de versões nas portarias **373** e **671**. Também biométrico, permitindo a identificação facial e a leitura das impressões digitais dos funcionários. Número de série abaixo do teclado numérico, a comunicação pode ser feita através do equipamento físico ou então pelo web server. [Clique aqui para saber mais.](###)

## COLETOR FACIAL

> Equipamento facial.

**Descrição:** Este dispositivo, enquadrado na portaria 671, tem sua principal função voltada para a marcação de ponto dos funcionários. Diferencia-se pela simplicidade operacional, uma vez que não demanda a impressão de comprovantes. É importante notar que o Coletor Facial não possui capacidade de conexão Wi-Fi. [Clique aqui para saber mais.](###)

💡 **Vantagem:** O Coletor Facial destaca-se pela sua facilidade na instalação, uma vez que o cliente já recebe o equipamento *“comunicando”* com o sistema, oferecendo uma solução direta e eficiente para essa finalidade específica.


# PRIMEIROS PASSOS 🐾

> Os cadastros dos relógios IREP e SINDNOX são muitos parecidos, então vamos começar aprendendo como cadastrá-los no sistema e depois partiremos para os procedimentos de comunicação.

## 1. FOTOS DO EQUIPAMENTO

💡 Para cadastrarmos um equipamento no sistema, precisamos de algumas informações dele, e a forma mais simples e eficiente de conseguirmos essas informações é através de fotos do relógio, sendo elas:

**1. Tela inicial do equipamento:** Essa foto informa se o equipamento tem ou não a impressora, indicando se é **IREP** ou **SINDNOX**;

**2. Tela de versão e informações adicionais:** Informa qual é a versão do equipamento, identificando a portaria **671** ou **1510**;

**3. Tela de comunicação:** Essa foto informa o **IP LOCAL** e **MAC,** também informa como estão as **configurações atuais de comunicação no equipamento**, inclusive se o equipamento está conectado via **cabo de rede** ou **WI-FI**;

**4. Número de fabricação:** Essa foto informa o identificador do equipamento. (informando qual portaria o relógio pertence)

#### Como pedir essas fotos? Clone:
```
1. Foto da tela inicial do equipamento;
2. Foto do número de fabricação (ele se localiza abaixo do teclado numérico);
3. Clique no símbolo de internet na tela (será um ícone de wi-fi ou de globo) e me envie uma foto das informações;
4. Na tela inicial, clique no ícone que está no canto inferior esquerdo da tela e também me envie uma foto.
```

-- 4 FOTOS DO EQUIPAMENTO

🔍 Clique duas vezes para ampliar a foto acima.

## 2. CADASTRO NO SISTEMA

> Após conseguir todas as fotos necessárias para realizar a comunicação, partimos para o cadastro do equipamento, que também tem diversas configurações para serem feitas, vamos começar definindo cada campo que você terá que preencher para cadastrar um equipamento do modelo **SINDNOX** ou **IREP**.

### **DESCRIÇÃO DO EQUIPAMENTO**

ℹ️ Aqui você irá preencher com um **nome** para o equipamento, não fará nenhuma diferença na comunicação, é apenas para **identificar o equipamento** dentro do sistema.

### **EMPRESA**

ℹ️ Esse será o campo onde você irá definir qual a empresa que ficará **vinculada ao relógio**, lembrando que deve ser a mesma empresa que os funcionários estão cadastrados.

### **SITUAÇÃO DO CADASTRO**

ℹ️ Esse campo define qual o status atual do equipamento, **Ativo** ou **Inativo**, no caso de um cadastro, defina o como **Ativo**!

### **MODELO DO EQUIPAMENTO**

ℹ️ Ambos os equipamentos podem variar seu modelo (para **IREP** ou **SINDNOX**), entre portaria **1510** ou portaria **671**, para definir qual o modelo correto, segue algumas especificações:

### **Modelos**

- **IREP:** Único relógio da DIXI que possui impressora
    - **IREP - Port. 671** na [foto 2]() o **`Id.Software`** deve ser acima de `3.0.0.0`
    - **IREP - Port. 1510** na [foto 2]() o **`Id.Software`** deve ser abaixo de `2.0.0.44`
    
- **SINDNOX:** Será aquele relógio que **NÃO** possui a **impressora**
    - **SINDNOX - Port. 671** na [foto 2]() o **`Id.Software`** deve ser acima de `3.0.0.0`
    - **SINDNOX - Port. 373** na [foto 2]() o **`Id.Software`** deve ser abaixo de `2.0.0.44`
    
💡 OBS: Caso fique com dúvidas, consulte novamente as [fotos do equipamento]().

### TIPO DE BIOMETRIA

ℹ️ Esse campo define o tipo de biometria do equipamento, que no momento, temos apenas 2 utilizadas, **`Embarcada`** ou **`Facial`.**

### FUSO HORÁRIO

ℹ️ Aqui você seleciona qual será o fuso horário do equipamento, por enquanto, no dia que estou fazendo esse documento, temos apenas o **`Brasil`**.

### MODO DE CONEXÃO DO RELÓGIO

ℹ️ Aqui nós iremos manter sempre como **`Cliente`**.

### **IP**

ℹ️ Essa opção vai variar de equipamento para equipamento, mas você pode verificar na [foto 3]() qual o `IP` do equipamento.

### **PORTA**

ℹ️ Ambos os equipamentos podem ter uma variação da porta, entre elas: **3000** ou **3671.** para definir qual a porta correta, é bem simples:

**– PORTA 3671:** Será para aqueles da portaria `671`

**– PORTA 3000:** Será para aqueles da portaria `1510`

### **NÚMERO DE SÉRIE**

ℹ️ Campo onde deve ser preenchido com o número de série do equipamento, encontrado na [foto 4]().

### **MAC**

ℹ️ O endereço MAC consiste em uma combinação de números e letras que permite a comunicação eficiente entre os dispositivos em uma rede local, você pode obtê-lo através da [foto 3]().

### **ÚLTIMO NSR**

ℹ️ Esse valor não é definido pelo usuário, o sistema define ele automaticamente com base no último [NSR]() coletado pelo relógio, então no momento de cadastrar o equipamento, defina-o como **`0`**, que é o seu valor inicial.

### **NÃO VALIDAR EMPRESA**

ℹ️ Caso ativa essa opção, o sistema não fará a validação da empresa do equipamento, enviando as marcações para o funcionário independente de ser a mesma empresa do relógio ou não.

### **USUÁRIO**

ℹ️ Campo responsável por definir qual o usuário da comunicação, **SEMPRE** defina-o como **“teste fabrica”**.

### **SENHA**

ℹ️ Campo responsável por definir a senha do usuário de comunicação, **SEMPRE** defina-o como **“111111”**.

## 3. PROCEDIMENTOS

> Chegando nos procedimentos para comunicar o equipamento, temos que nos atentar que há **2** maneiras diferentes de realizar a comunicação**:**

### **COMUNICAÇÃO ATRAVÉS DO WEB SERVER**

💡 Acessível somente quando o aparelho está conectado a um cabo de rede. [Saiba mais.]()

💡 O computador deve estar na **mesma rede** que o equipamento, essa verificação pode e deve ser confirmada pelo responsável da rede ou pelo *T.I.*
FOTO WEB SERVER

> Após atender ambos os requisitos [💡], passamos para os procedimentos necessários, então aqui está uma ordem cronológica das informações que devem ser verificadas e também os procedimentos que serão executados.
> 

1. O primeiro passo é acessar o ***web server*** do equipamento. Para isso, no seu navegador, vá na barra de pesquisa e digite o **“IP”**, localizado na ***FOTO 3***, **sem os zeros a esquerda**, segue exemplo:

    FOTO ENTRANDO WEB SERVER IP

2. Depois disso, você irá se deparar com a tela de login. Para acessar, as credenciais padrões tanto para o **IREP** quanto para o **SINDNOX**, será:
    
    > **Usuário:** teste fabrica

    > **Senha:** 111111

    ⚠️ Antes de entrar, verifique se não há espaços antes ou depois dos valores.

3. No terceiro passo, nos deparamos com o **Menu** principal do `web server`. Vale ressaltar que nesse manual, o foco será apenas a **COMUNICAÇÃO**, outras configurações que temos no **`web server`** serão deixadas de lado por enquanto. 

    Inicie clicando em **`Configurações`** para acessar as configurações internas de comunicação.

    FOTO WEB SERVER
    

4. Na tela de **`Configurações`** aparecerão as mesmas informações que podemos obter nas fotos do equipamento, porém as mais importantes serão: 

- **Identificador do software**
- **Número do REP** (número de série do equipamento) 
- **Eventos** ([NSR]() do equipamento).

    **Nesta tela, é recomendado salvar essas informações para caso precise futuramente.**

    FOTO WEB SERVER
    
5. Clicando na lateral esquerda em **`Comunicação`** você verá essa tela, é aqui que nós faremos a comunicação do equipamento, explicaremos abaixo como você irá preencher cada campo, mas sem especificações técnicas.

    FOTO WEB SERVER

## CONFIGURAÇÕES COMUNICAÇÃO WEB SERVER

### Tipo de comunicação

> Sempre deixaremos `Tcp/Ip` selecionado.

### IP

> Esse é o endereço de IP local do relógio, é o que você usa para acessar o web server, recomendamos que NÃO troque.

### Porta TCP

> Porta de comunicação com o servidor, esse valor pode variar, mas para saber corretamente qual a porta, [clique aqui]().

### Máscara de sub-rede

> Por padrão, esse valor será definido automaticamente, mas caso todas as outras configurações estejam corretas e o equipamento não comunique, vale ressaltar que esse campo influencia. [Clique aqui para saber mais.]()

### Endereço MAC

> Esse é um identificador do equipamento, não irá impactar diretamente na conexão com o sistema, mas pode impactar no acesso do equipamento à rede de internet.

### Gateway

> Assim como a máscara de rede, por padrão ele vai vir configurado corretamente, mas caso não esteja, irei te mostrar abaixo como conseguir cada valor. [Clique aqui para saber mais.]()

### Endereço DNS

> Nunca iremos usar esse número, ele não irá interferir na comunicação, então deixe como está.

### DHCP

> Ele é responsável por selecionar um `IP` disponível na rede, para que o relógio se conecte sem problemas na rede de internet local (onde o relógio está localizado).

### TCP Mode

> Sempre usaremos `Modo Cliente`.

### Endereço Servidor

> Para o servidor do WEB DIXI, esse campo será `003.093.251.124`.

### Porta Servidor

> Porta de comunicação com o servidor, esse valor pode variar, mas para saber corretamente qual a porta, [clique aqui]().

### Usar DNS

> Sempre deixaremos `Desabilitado`, lembre-se disso.

### Timeout client

> Sempre deixaremos no valor padrão: `3`.

### Endereço Servidor

> Neste campo abaixo, deixaremos vazio.

📢 Após preencher todas as informações corretamente no *web server* e **salvar**, o seu equipamento já estará comunicando com o ***WEB DIXI*.**

### **COMUNICAÇÃO DIRETO NO EQUIPAMENTO**

> Nesse formato iremos analisar a **[FOTO 3]()** para identificar se o equipamento está ou não conectado via cabo de rede. Verifique essa informação observando o campo **`ETH`** na foto em questão, caso esteja a mensagem **“Sem rede”**, significa que não há cabo de rede conectado, então teremos que comunicá-lo via WIFI.

💡 Caso esteja conectado com cabo, recomendamos fortemente que comunique-o pelo web server utilizando o procedimento acima.

Comunicando via WIFI teremos que fazer os procedimentos diretamente no equipamento físico, então nessa seção vamos passar os procedimentos de como proceder nesse caso:

1. Inicialmente, na tela inicial de seu relógio clique na **`engrenagem`** no centro da tela ou então em **`MENU`** no teclado ao lado do numérico.
2. Depois disso, colocamos a senha padrão: **`111111`** e o CPF padrão **`265`** para acessarmos o painel de configurações.

    FOTO RELÓGIO

3. Na sequência, clique no **`número 3`** do teclado numérico ou na própria tela em **`3- Comunic.`** para acessarmos as configurações de comunicação do equipamento.

4. Temos 2 caminhos diferentes de configurações, o caminho para configurarmos as opções de quando o equipamento está conectado no cabo de rede e também a etapa para o WIFI, então nesse passo, vamos escolher a opção **`2- WiFi`** clicando direto na tela ou apertando o **`número 2`** no teclado numérico.

5. Antes de configurarmos a rede que conectará no equipamento, vamos modificar as configurações de comunicação indo em **`5- Avançado`** clicando diretamente na tela ou então apertando o **`número 5`** no teclado numérico.

6. Na próxima tela, temos diversas configurações de comunicação, mas por enquanto, vamos clicar nas 2 setas para conseguir chegar na opção do **`modo cliente`**, que é onde iremos realizar todas as mudanças.

7. Nessa etapa, é importante lembrarmos que para modificar o ***IP do servidor, PORTA e desativar o DNS***, temos que ir no **`9- modo cliente`**.

    > Não tem muito o que explicar por aqui, apenas seguirmos esses próximos passos

🚧 Caso o modo cliente esteja **ativo**, temos que desativá-lo e depois ativá-lo novamente para entrarmos nas configurações desejadas, então caso ele esteja ativo, clique nele, depois clique no **botão verde** para desativar e em seguida, clique em **`Modo Cliente`** **novamente**.

1. A primeira mensagem que aparecerá é: **“Usar DNS?”**, aqui é importante lembrar que o **DNS DEVE ESTAR DESATIVADO**, então clique no **“X”** vermelho para não utilizar.

2. Depois disso será necessário colocar o IP do servidor, **atenção** para não errar esse número. [Como saber o IP do servidor?]()

3. Na sequência, aparecerá outra pergunta: **“Usar Reconexão Imediata?”**. Aqui sempre deixaremos como **SIM**, então aperte no **VERDE**.

4. Na **PORTA**, é importante dizer que ambos os equipamentos podem ter uma variação da porta, entre elas: **3000** ou **3671.** para definir qual a porta correta, é bem simples:
    1. **Equipamentos da portaria 671:** Porta **03671**.
    2. **Equipamentos da portaria 1510:** Porta **03000**.
5. A próxima etapa é o “**Tempo”**, que por padrão, iremos sempre deixar **“03”** e apertar no **VERDE**.
6. Prontinho! A configuração do modo cliente estará finalizada com sucesso quando aparece a mensagem **“Sucesso ao salvar”**.

***MANUAL EM DESENVOLVIMENTO, TREINAMENTO PRONTO***

[— Coletor Facial](https://www.canva.com/design/DAF0U925HNg/7fGyu6YxZ9bNDiOo844H0Q/edit)

[Continue sua integração]()