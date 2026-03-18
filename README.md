## 🇵🇹 Versão em Português

# CP Train Tracker

Uma aplicação de monitorização de comboios da **Comboios de Portugal (CP)**, com dados em tempo real e horários planeados.

Este projeto recolhe, normaliza e visualiza dados dinâmicos e estáticos dos comboios da CP através de APIs *não oficiais*, apresentando‑os num mapa interativo e numa interface web.

> ⚠️ **Aviso**: Este projeto utiliza endpoints *não oficiais* da CP. Não é afiliado nem apoiado pela Comboios de Portugal.

https://comboios.ruicosta.pt/

---

## ✨ Funcionalidades

* 🚆 Localização e estado dos comboios em tempo real
* 🕒 Atrasos, ETAs e ETDs em tempo real
* 🗺️ Visualização em mapa interativo
* 🛤️ Lista completa de paragens por comboio
* 📊 Métricas agregadas de atraso por tipo de serviço

---

## 🧱 Stack Tecnológica

### Frontend

* **Vue 3** (Composition API)
* **Vite**
* **MapLibre GL**
* **Stadia Maps** (tiles do mapa)

### Backend

* **Node.js / TypeScript**
* **MariaDB**

---

## 🗺️ Renderização do Mapa

* Baseado em **MapLibre GL**
* Tema escuro via Stadia Maps
* Comboios renderizados como marcadores dinâmicos
* Atualizações de estado em tempo real

---

## 📊 Métricas de Atraso

As estatísticas de atraso são agregadas por tipo de serviço:

* Atraso mínimo (comboio)
* Atraso máximo (comboio)
* Atraso médio
* Número de comboios ativos

---

## 🚧 Limitações Conhecidas

* As APIs da CP são não oficiais e podem mudar a qualquer momento
* Alguns serviços podem reportar dados incompletos de forma intermitente
* A precisão dos dados históricos depende da disponibilidade do tempo real da CP

---

## 🙏 Créditos

* Comboios de Portugal (fonte de dados)
* MapLibre GL
* Stadia Maps

---

## 💬 Notas

Este projeto foi desenvolvido principalmente para aprendizagem, experimentação e transparência em torno dos dados de transporte público em Portugal.

Contribuições, issues e discussões são bem‑vindas.

---


## 🇬🇧 Version in English

# CP Train Tracker

A real‑time and scheduled **Comboios de Portugal (CP)** train tracking application.

This project collects, normalizes, and visualizes live and static train data from CP’s unofficial APIs and presents it on an interactive map and UI.

> ⚠️ **Disclaimer**: This project uses *unofficial* CP endpoints. It is not affiliated with or endorsed by Comboios de Portugal.

---

## ✨ Features

* 🚆 Live train positions and statuses
* 🕒 Real‑time delays, ETAs, and ETDs
* 🗺️ Interactive map visualization
* 🛤️ Full stop lists per train
* 📊 Aggregated delay metrics per service type

---

## 🧱 Tech Stack

### Frontend

* **Vue 3** (Composition API)
* **Vite**
* **MapLibre GL**
* **Stadia Maps** (map tiles)

### Backend

* **Node.js / TypeScript**
* **MariaDB**

---

## 🗺️ Map Rendering

* Powered by **MapLibre GL**
* Dark theme via Stadia Maps
* Trains rendered as live markers
* Marker state updates in real time

---

## 📊 Delay Metrics

Delay statistics are aggregated per service type:

* Min delay (train)
* Max delay (train)
* Average delay
* Active train count

---

## 🚧 Known Limitations

* CP APIs are unofficial and may change
* Some services may intermittently report missing or partial data

---

## 🙏 Credits

* Comboios de Portugal (data source)
* MapLibre GL
* Stadia Maps

---

## 💬 Notes

This project is primarily built for learning, experimentation, and transparency around public transport data in Portugal.

Contributions, issues, and discussions are welcome.

---


