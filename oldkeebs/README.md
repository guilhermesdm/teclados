# Oldkeebs

Teclado mecânico **split**, totalmente **handwired**, com firmware **ZMK** rodando em controladores **nRF52840**.

Projeto focado em ergonomia, portabilidade, baixo consumo e controle total sobre hardware e firmware.

---

## 🔧 Especificações

- **Layout:** 6x4 + 3 teclas por lado (54 teclas no total)
- **Firmware:** ZMK (Dongle dedicado)
- **Controladores:** 3 × nRF52840  
  - 1 × Lado esquerdo  
  - 1 × Lado direito  
  - 1 × Dongle USB  
- **Montagem:** 100% handwired (matriz com diodos)
- **Estrutura:** Impressa em 3D (PLA)
- **Alimentação:** 2 × baterias LiPo 300mAh (4mm × 25mm × 30mm)
- **Conectividade:**  
  - BLE entre as metades  
  - Dongle USB para conexão estável ao PC  

---

## 🧱 Materiais Utilizados

| Quantidade | Item | Observações |
|-------------|------|-------------|
| **1kg** | Filamento PLA | Impressão da case, keycaps e dongle |
| **6** | Insertos M3x6 | Para fixação da case |
| **6** | Parafusos M3x6 | Compatíveis com os insertos |
| **3** | nRF52840 | Um para cada metade e um para o dongle |
| **54** | Keycaps low profile | KLP Lame Keycaps (PLA) |
| **54** | Switches low profile Redragon (Red) | Lineares |
| **54** | Diodos 1N4148 | Para matriz de teclas |
| **2** | Baterias LiPo 300mAh | 4mm × 25mm × 30mm |
| **2** | Botão Reset 6x6x4.3mm | 2 terminais, preto |
| **2** | Slide switch | Liga/Desliga bateria |
| **XX** | Fio de cobre 16 AWG | Estrutura / barramento principal |
| **XX** | Fio de cobre 28 AWG | Ligações da matriz |
| **XX** | Tubo termo retrátil | Isolamento e acabamento |
| **1** | Cabo USB-C (dados) | Para conexão do dongle ao PC |

---

## 🔋 Sistema de Alimentação

Cada metade possui:

- 1 × Bateria LiPo 300mAh (3.7V)
- 1 × Slide switch (controle físico de energia)
- 1 × Botão reset dedicado

## ⚡ Autonomia Estimada

Considerando consumo médio BLE otimizado com ZMK:

- Segundo https://zmk.dev/power-profiler é de 6 months 3 weeks (±2 months)

*A autonomia real depende de polling rate, recursos ativos e intensidade de uso.*

---

## 🛠️ Firmware (ZMK)

Recursos utilizados:

- Dongle central
- Multi-device pairing
- Hold-Tap
- Combos
- Layers
- Deep Sleep automático

## Imagens

| Vista superior |
|----------------|
| ![Imagem1](images/img1.png) |
| ![Imagem2](images/img2.png) |
| ![Imagem3](images/img3.png) |
| ![Imagem4](images/img4.png) |
| ![Imagem5](images/img5.png) |

---