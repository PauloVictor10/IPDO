# 📊 Automação IPDO ONS — Notificação por E-mail

Este projeto implementa uma automação em Python responsável por:

- Acessar o site oficial do **ONS**
- Identificar e baixar automaticamente o **IPDO diário**
- Ler o PDF e extrair os **Destaques da Operação do Submercado Nordeste**
- Enviar um **e-mail HTML formatado**, com o resumo e o PDF anexado

Projeto desenvolvido com foco em **rotinas operacionais do setor elétrico**, RPA e automação de alertas.

---

## 🧩 Tecnologias utilizadas

- Python 3
- Requests (download do PDF)
- PyPDF (leitura e extração de texto)
- Regex avançado para parsing de conteúdo
- SMTP (envio de e-mail automático)
- HTML/CSS inline para formatação do e-mail

---

## 🔄 Fluxo da automação

1. Consulta o acervo digital do ONS
2. Baixa automaticamente o IPDO do dia anterior
3. Localiza a seção **"4 - Destaques da Operação"**
4. Extrai exclusivamente o trecho do **Submercado Nordeste**
5. Formata os destaques em HTML profissional
6. Envia e-mail com:
   - Resumo automático
   - PDF IPDO anexado

---

## 📧 Exemplo do e-mail recebido

![E-mail IPDO](gmail.png)

---

## 📄 Exemplo do PDF IPDO

![PDF IPDO](ipdo.png)

---

## ⚙️ Como executar

Roda como tarefa diária no pythonanywhere
