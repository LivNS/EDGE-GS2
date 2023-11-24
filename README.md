## MedPlan - Envio de lembretes de medicamentos via WhatsApp
Descrição
O projeto MedPlan visa auxiliar na administração de medicamentos por meio do envio automatizado de lembretes via WhatsApp. Este código em particular faz uso da API do CallMeBot para enviar mensagens para um número específico, lembrando sobre a hora de tomar medicamentos.

Pré-requisitos
Placa ESP32 ou similar compatível com a biblioteca WiFi.h e HTTPClient.h
Acesso a uma rede Wi-Fi
Número de telefone para o qual serão enviados os lembretes via WhatsApp
Chave de API fornecida pelo CallMeBot para uso da API do WhatsApp
Configuração
Configure as credenciais da rede Wi-Fi:

ssid: Nome da rede Wi-Fi
password: Senha da rede Wi-Fi
Configure as variáveis para o envio da mensagem:

phoneNumber: Número de telefone do destinatário (no formato internacional, incluindo código do país)
apiKey: Sua chave de API fornecida pelo CallMeBot
Uso
Conecte a placa ESP32 à alimentação.
Aguarde até que o dispositivo se conecte à rede Wi-Fi.
Após a conexão bem-sucedida, a mensagem será enviada automaticamente para o número especificado no código, com o texto "Hora de se medicar!!!!".
O código pode ser ajustado no método sendMessage para personalizar o texto da mensagem ou ser integrado a um sistema mais complexo para gerenciar horários específicos de medicamentos.
