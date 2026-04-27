# Escorpigame
# EscorpioMed — Protocolo em Jogo

Aplicação interativa desenvolvida em **Streamlit** para apoiar o ensino, a revisão e a fixação de condutas clínicas relacionadas ao **escorpionismo**, com base no **PCDT de Acidentes Escorpiônicos — Ministério da Saúde, 2026**.

O jogo foi estruturado como uma experiência educacional com perguntas, casos clínicos e flashcards, permitindo que estudantes, residentes e profissionais de saúde revisem conceitos essenciais sobre classificação de gravidade, manejo inicial, analgesia, soroterapia, monitoramento e complicações clínicas.

---

## Objetivo

O objetivo do **EscorpioMed** é transformar o estudo do protocolo clínico de escorpionismo em uma atividade interativa, acessível e de fácil compartilhamento.

A proposta é favorecer:

- aprendizagem ativa;
- revisão rápida de condutas clínicas;
- treinamento de tomada de decisão;
- fixação dos principais pontos do protocolo;
- uso em atividades de ensino, capacitações, oficinas e educação permanente em saúde.

---

## Modos de jogo

A aplicação contém três modos principais:

### 1. Quiz Rápido

Modo de múltipla escolha com questões sobre:

- diagnóstico clínico-epidemiológico;
- classificação em leve, moderado e grave;
- indicações de soroterapia;
- manejo da dor;
- sinais de gravidade;
- monitoramento clínico e laboratorial;
- diagnóstico diferencial;
- armazenamento dos soros;
- condutas complementares.

Cada resposta apresenta feedback explicativo para reforçar o aprendizado.

---

### 2. Caso Clínico

Modo de tomada de decisão baseado em situações clínicas simuladas.

O jogador deve analisar dados do paciente, sinais vitais, manifestações clínicas e selecionar condutas relacionadas a:

- classificação da gravidade;
- manejo analgésico;
- indicação ou não de soro antiveneno;
- dose de soro;
- suporte hemodinâmico;
- particularidades de acidentes na Região Amazônica.

Esse modo simula a lógica de raciocínio clínico necessária no atendimento inicial de pacientes com suspeita de escorpionismo.

---

### 3. Flashcards

Modo de revisão rápida com cartões interativos.

Os flashcards abordam conceitos-chave como:

- espécies de importância médica;
- manifestações neurológicas por *Tityus obscurus*;
- doses de soro antiescorpiônico;
- tempo de observação;
- exames de monitoramento;
- analgesia;
- diagnóstico diferencial;
- profilaxia antitetânica;
- CID-10;
- classificação internacional.

---

## Tecnologias utilizadas

- **Python**
- **Streamlit**
- **HTML**
- **CSS**
- **JavaScript**
- `streamlit.components.v1.html` para renderizar o jogo interativo dentro do Streamlit

---

## Estrutura do projeto

```text
escorpiomed-streamlit/
│
├── app.py              # Aplicação principal em Streamlit
├── requirements.txt    # Dependências do projeto
└── README.md           # Documentação do projeto
```

---

## Como executar localmente

### 1. Clone ou baixe este repositório

```bash
git clone https://github.com/SEU-USUARIO/escorpiomed-streamlit.git
cd escorpiomed-streamlit
```

Caso você tenha baixado os arquivos manualmente, basta abrir a pasta onde estão `app.py` e `requirements.txt`.

---

### 2. Crie um ambiente virtual

No Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

No Linux/macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

---

### 4. Execute o aplicativo

```bash
streamlit run app.py
```

Depois disso, o Streamlit abrirá o aplicativo no navegador.

---

## Publicação no Streamlit Community Cloud

Para publicar o jogo online:

1. Crie um repositório no GitHub.
2. Envie os arquivos:
   - `app.py`
   - `requirements.txt`
   - `README.md`
3. Acesse o **Streamlit Community Cloud**.
4. Clique em **New app**.
5. Selecione o repositório criado.
6. Defina o arquivo principal como:

```text
app.py
```

7. Clique em **Deploy**.

Ao final, será gerado um link público para acesso ao jogo.

---

## Dependências

O arquivo `requirements.txt` deve conter:

```text
streamlit>=1.33
```

---

## Uso educacional

Este jogo foi desenvolvido para fins de **educação em saúde**, **capacitação profissional** e **revisão de protocolos clínicos**.

Pode ser utilizado em:

- aulas de vigilância em saúde;
- treinamentos de residentes;
- oficinas sobre acidentes por animais peçonhentos;
- educação permanente de equipes assistenciais;
- atividades de simulação clínica;
- revisão rápida antes de atendimentos supervisionados.

---

## Aviso importante

O **EscorpioMed** é uma ferramenta educacional e não substitui:

- avaliação clínica individual;
- julgamento profissional;
- protocolos institucionais vigentes;
- fluxos locais de assistência;
- consulta ao PCDT oficial;
- orientação de centros de informação e assistência toxicológica.

Em situações reais, a conduta deve seguir as normas técnicas atualizadas do Ministério da Saúde, protocolos locais e avaliação da equipe responsável.

---

## Conteúdo técnico abordado

O jogo contempla tópicos como:

- diagnóstico clínico-epidemiológico do escorpionismo;
- manifestações locais e sistêmicas;
- classificação clínica de gravidade;
- critérios de casos leves, moderados e graves;
- indicações de soro antiescorpiônico;
- doses recomendadas conforme gravidade;
- uso do soro antiaracnídico em situações específicas;
- manejo da dor;
- manifestações neurológicas na Região Amazônica;
- monitoramento clínico, laboratorial e eletrocardiográfico;
- suporte em casos graves;
- choque cardiogênico;
- edema agudo de pulmão;
- profilaxia antitetânica;
- armazenamento e transporte de soros.

---

## Créditos

**Elaboração:** Fernanda Haltenburg  
**Tema:** Escorpionismo e protocolo clínico assistencial  
**Base técnica:** PCDT de Acidentes Escorpiônicos — Ministério da Saúde, 2026  
**Formato:** jogo educacional interativo em Streamlit

---

## Sugestões de melhoria futura

Algumas funcionalidades que podem ser adicionadas em versões futuras:

- tela de boas-vindas institucional;
- registro de nome do participante;
- certificado de conclusão;
- banco de pontuação por turma;
- exportação de desempenho em CSV;
- painel do professor/facilitador;
- modo treinamento e modo avaliação;
- integração com Google Sheets ou REDCap;
- versão mobile otimizada;
- inclusão de novos casos clínicos;
- expansão para outros acidentes por animais peçonhentos.

---

## Licença

Este projeto pode ser adaptado para fins educacionais e institucionais. Caso seja reutilizado, recomenda-se manter os créditos de elaboração e indicar a fonte técnica utilizada.
