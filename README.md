# 💳 Paga Eu - V3.0 (Global Edition)

**Criação e Concepção:** * **Antônio Altvater**
* **Guilherme Revoredo**

O **Paga Eu** (conhecido como o *"Doom do Pix"*) é uma ferramenta de pagamento rápido e resiliente, projetada para funcionar onde a infraestrutura convencional falha. Na **V3.0**, o projeto rompe fronteiras com um motor de internacionalização nativo, focado em zonas de crise, isolamento geográfico e missões humanitárias globais.

---

## 🌍 Novidade V3.0: Internacionalização (i18n)

A V3.0 introduz suporte nativo a quatro idiomas estratégicos, permitindo que a ferramenta seja operada em diferentes continentes sem necessidade de tradução externa ou conexão com a internet:

* **🇧🇷 Português (PT-BR):** Contexto nativo do Pix brasileiro.
* **🇫🇷 Français (FR):** Atendimento para França, Canadá e vasta região da África Ocidental e Central.
* **🇪🇸 Español (ES):** Resiliência para toda a América Latina e Espanha.
* **🇨🇩 Lingala (LN):** Foco humanitário específico para a **República Democrática do Congo** e região do Congo-Brazzaville, onde a estabilidade econômica offline é vital.

---

## ⛈️ Resiliência em Situações de Crise 

Diferente de soluções que dependem da nuvem, o **Paga Eu** foi construído para ser um **Kit de Emergência Digital**:

* **Autonomia Total:** Funciona 100% offline após o carregamento inicial ou via arquivo local.
* **Distribuição Física:** O projeto ocupa apenas **33kb** no total. Pode ser transportado via pen drive, cartão SD ou transmitido via Bluetooth/Rádio entre dispositivos.
* **Privacidade:** Processamento **100% local**. Nenhum dado financeiro ou pessoal sai do navegador.
* **O "Doom do Pix":** Assim como o lendário jogo, se o dispositivo tem uma tela e um navegador (mesmo que antigo), ele vai rodar o Paga Eu.

---

## 🚀 Funcionalidades

* **Motor i18n Nativo:** Seletor instantâneo de idiomas integrado na interface.
* **Pix Estático:** Geração de payloads no padrão EMV QRCPS (Banco Central do Brasil).
* **Máscaras Inteligentes:** Formatação visual em tempo real para CPF, Celular e Moeda (BRL) embutida nos campos.
* **Layout Adaptável:** Interface profissional otimizada para dispositivos modernos e legados.
* **Aba de Apoio:** Sistema integrado para contribuições voluntárias ao projeto.

---

## 💻 Tabela de Compatibilidade

Graças ao motor de renderização híbrido (**SVG / Canvas / Table**), o Paga Eu roda em praticamente qualquer hardware.

| Dispositivo / SO | Compatibilidade | Modo de Renderização | Uso Recomendado |
| :--- | :---: | :--- | :--- |
| **Android (Todas as versões)** | ✅ Total | Canvas / SVG | Smartphone de campo |
| **iPhone / iOS** | ✅ Total | SVG | Uso cotidiano e PWA |
| **Windows / Zorin OS / Mac** | ✅ Total | SVG / Canvas | Desktop / Centros de Apoio |
| **Navegadores Legados (IE6+)** | ✅ Total | HTML Table | Computadores antigos/doação |
| **Pen Drive / Mídia Física** | ✅ Total | Local File System | Emergências sem Internet |
| **Raspberry Pi / POS Terminal** | ✅ Total | Canvas | Totens de atendimento |

---

## 📥 Instalação e Uso

O projeto é composto por dois arquivos essenciais que devem ser mantidos na mesma pasta:

1.  **`index.html` (14kb):** Interface, dicionário de idiomas e lógica de negócio.
2.  **`qrcode.min.js` (19kb):** Motor matemático de geração do código.

### Instruções:
1.  Faça o download de ambos os arquivos.
2.  Abra o arquivo `index.html` em qualquer navegador.
3.  **Para Emergências:** Mantenha uma cópia desta pasta em um pen drive ou cartão SD.

---

## 🌍 O Futuro: BRICS Pay

A arquitetura da V3.0 pavimenta o caminho para a integração com o sistema **BRICS Pay**. O objetivo é transformar o Paga Eu em uma ponte financeira internacional, suportando pagamentos em moedas do bloco (**Yuan, Rublo, Rúpia, etc.**) em situações de comércio transfronteiriço ou ajuda humanitária global.

---

## ❤️ Apoie o Projeto

> "Pague quando puder, se puder."

Sua contribuição garante que este código permaneça público, aberto e útil para quem mais precisa.

**Chave Aleatória Pix:** `52806ce2-7edb-4f89-9003-f8d199feb4f6`

---
**Licença:** MIT (Código Aberto)