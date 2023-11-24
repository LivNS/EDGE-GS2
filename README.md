# MedPlan - Envio de lembretes de medicamentos via WhatsApp

## Descrição

O projeto MedPlan visa auxiliar na administração de medicamentos por meio do envio automatizado de lembretes via WhatsApp. Este código em particular faz uso da API do CallMeBot para enviar mensagens para um número específico, lembrando sobre a hora de tomar medicamentos.

## Descrição do Problema

No contexto médico, um desafio crítico é a gestão precisa das prescrições de
medicamentos, especialmente quando lidamos com pacientes idosos. O esquecimento
e a confusão na administração de medicamentos são questões recorrentes, levando a
erros nas datas e medicações adequadas. Isso gera riscos à saúde do paciente e pode
comprometer o sucesso do tratamento.

## Pré-requisitos
<li>Placa ESP32 ou similar compatível com a biblioteca WiFi.h e HTTPClient.h</li>
<li>Acesso a uma rede Wi-Fi</li>
<li>Número de telefone para o qual serão enviados os lembretes via WhatsApp</li>
<li>Chave de API fornecida pelo CallMeBot para uso da API do WhatsApp</li>

## Configuração

<li>Configure as credenciais da rede Wi-Fi:</li>
<li>ssid: Nome da rede Wi-Fi</li>
<li>password: Senha da rede Wi-Fi</li>
<li>Configure as variáveis para o envio da mensagem:</li>
<li>Número de telefone do destinatário (no formato internacional, incluindo código do país)</li>
<li>apiKey: Sua chave de API fornecida pelo CallMeBot</li>

## Uso

<li>Conecte a placa ESP32 à alimentação.</li>
<li>Aguarde até que o dispositivo se conecte à rede Wi-Fi.</li>
<li>Após a conexão bem-sucedida, a mensagem será enviada automaticamente para o número especificado no código, com o texto "Hora de se medicar!!!!".</li>
<li>O código pode ser ajustado no método sendMessage para personalizar o texto da mensagem ou ser integrado a um sistema mais complexo para gerenciar horários específicos de medicamentos.</li>

## Referência 

https://www.callmebot.com/blog/free-api-whatsapp-messages/

