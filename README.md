# 🌦️ Automação Climática Inteligente com Python

Este projeto em Python utiliza a API gratuita do **OpenWeather** para obter informações climáticas em tempo real de qualquer cidade do mundo. Ele interpreta os dados e simula **ações automatizadas**, como alertas de calor ou chuva — ideal para aplicações futuras em **automação residencial** e **monitoramento de plantas**. 🌱

---

## 🚀 Funcionalidades

- 🔍 Consulta do clima atual via OpenWeather API
- 🌡️ Exibição de temperatura, sensação térmica e condição do tempo
- ⚠️ Alertas automatizados para calor excessivo ou chuva
- 🧠 Base para expansão com sensores físicos no futuro

---

## 📈 Futuras Expansões (Roadmap)

| Etapa | Descrição |
|-------|-----------|
| ✅ **Fase 1** | Integração com API climática (concluído) |
| 🔜 **Fase 2** | Simulação de sensores de umidade, luz e temperatura |
| 🔜 **Fase 3** | Conexão com sensores reais via Arduino ou ESP32 |
| 🔜 **Fase 4** | Sistema de irrigação automatizado baseado em sensores |
| 🔜 **Fase 5** | Envio de notificações via WhatsApp |
| 🔜 **Fase 6** | Painel de visualização em tempo real (com Flask) |

---

## 🛠️ Tecnologias Utilizadas

- **Python** – linguagem principal
- **OpenWeather API** – dados de clima em tempo real
- **requests** – biblioteca para requisições HTTP
- *(futuro)* Arduino, ESP32, sensores de umidade/luz
- *(futuro)* Telegram Bot API, Flask, banco de dados

---

## 💡 Exemplo de Uso

```bash
$ python main.py
Digite o nome da cidade: São Paulo

🌦️ Clima em São Paulo:
Temperatura: 32°C
Sensação térmica: 35°C
Condição: céu limpo

⚠️ alerta: está muito quente, ative o resfriamento!
