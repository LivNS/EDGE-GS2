# MedPlan - Agenda Médica Fácil

## Descrição do Problema:

No campo médico, a gestão precisa das prescrições de medicamentos, especialmente com pacientes idosos, é um desafio crítico. O esquecimento e a confusão na administração de medicamentos levam a erros nas datas e medicações apropriadas, representando riscos à saúde do paciente e ao sucesso do tratamento.

## Proposta de Solução:

O MedPlan é um programa de simulação de agenda médica desenvolvido para enfrentar esse desafio. Ele permite aos médicos registrar prescrições de medicamentos para os pacientes, juntamente com datas de início e término da administração dos remédios. Isso simplifica o controle das prescrições e viabiliza uma gestão mais eficiente das terapias medicamentosas.
Para isso, desenvolvemos um Relógio utilizando o ESP32 que, futuramente, planejamos melhorar e, com isso, transformar em algo mais acessivel como uma notificação/alarme push em dispositivos smart watchs e phones.

## Detalhes do Código:
O código utiliza as bibliotecas WiFi.h e LiquidCrystal_I2C.h para a conexão Wi-Fi e controle do display LCD I2C.

## Funcionalidades Principais:

<li>Conexão Wi-Fi: Estabelece conexão com a rede Wi-Fi fornecida.</li>
<li>Obtenção do Tempo: Utiliza um servidor NTP para sincronização e obtenção da hora atual.</li>
<li>Exibição no Display: Mostra a hora e a data obtidas do servidor NTP no display LCD.</li>

## Configuração do Código:

O código pode ser configurado para se conectar a uma rede Wi-Fi específica, fornecendo o SSID e a senha correspondentes na função WiFi.begin(). Além disso, é possível ajustar o servidor NTP utilizado para obter a hora atual alterando a constante NTP_SERVER no código.

## Instruções de Uso:

<li>Carregar o código em um microcontrolador compatível.</li>
<li>Certificar-se de fornecer as credenciais corretas da rede Wi-Fi na função WiFi.begin().</li>
<li>Conectar o display LCD conforme especificado na biblioteca LiquidCrystal_I2C.h.</li>
<li>Observar a exibição da hora e data no display LCD após a conexão bem-sucedida à rede Wi-Fi.</li>

## Imagem:
![Captura de tela 2023-11-24 203109](https://github.com/LivNS/EDGE-GS2/assets/118857876/b79497de-ade7-4486-8760-8c00ca748c2d)

## Acesso ao Wokwi:

https://wokwi.com/projects/382321204553326593

## Autoras:

Débora da Silva Amaral RM 550412 
Lívia Namba Seraphim RM 97819
