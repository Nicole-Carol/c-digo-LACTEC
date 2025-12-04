Microprocessador para Monitoramento de Temperatura e Umidade em Tempo Real

Este projeto tem como objetivo desenvolver um sistema embarcado capaz de medir temperatura e umidade em tempo real, enviando esses dados para um servidor na nuvem.
O servidor utilizado para visualização e armazenamento das informações é o ThingSpeak.

🧩 Funcionalidades

📍 Leitura contínua de temperatura e umidade

🌐 Conexão com rede Wi-Fi

☁️ Envio automático dos dados ao ThingSpeak

⏱️ Atualização dos gráficos do servidor a cada 20 segundos

📊 Visualização dos dados em gráficos diretamente na plataforma

🛠️ Componentes e Tecnologias Utilizadas

Item	Descrição

Microprocessador/Microcontrolador:	ESP32

Sensor: DHT22 

Plataforma IoT	ThingSpeak

Conexão	Wi-Fi

Linguagem de Programação	C/C++ 

🔌 Funcionamento

Ao ser ligado, o microprocessador realiza a conexão com o Wi-Fi configurado.

O sensor realiza as medições de temperatura e umidade do ambiente.

Esses valores são enviados para um canal do ThingSpeak configurado previamente.

O ThingSpeak atualiza os gráficos automaticamente a cada 20 segundos, permitindo monitoramento em tempo real.

📈 Visualização dos Dados

Todos os dados enviados podem ser visualizados por meio de gráficos no próprio painel do ThingSpeak.
Isso permite acompanhar variações climáticas rapidamente, de qualquer lugar com acesso à internet.

🚀 Possíveis Melhorias Futuras

Armazenamento local dos dados para redundância

Envio de alertas por e-mail ou notificação quando atingir certos limites

Inclusão de outros sensores (ex.: pressão, qualidade do ar)

Dashboard mais personalizado (ex.: Blynk, Grafana, Node-RED)

📎 Objetivo Geral

Criar uma solução IoT simples e eficiente para monitoramento ambiental contínuo, permitindo análises e tomada de decisão baseada em dados coletados em tempo real.

---

## 👥 Equipe

Projeto desenvolvido como parte do curso na **UNIBRAS – Modelo de Documento para projetos**   
Disciplina: Arquitetura e Organização de computadores
Professor: Francismar Alves Martins Junior

- Jonas Evangelista  
- Nicole caroline 
- kahuã Oliveira  
- Patricía  


