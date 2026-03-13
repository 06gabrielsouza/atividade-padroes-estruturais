# 🏗️ Padrões de Projeto Estruturais

Repositório destinado à entrega da **Atividade Assíncrona 2** da disciplina de **Requisitos, Projeto de Software e Validação**. O objetivo é explorar como os padrões estruturais facilitam a organização de classes e objetos para criar sistemas mais flexíveis e escaláveis.

**Aluno:** Gabriel Souza  
**Curso:** Análise e Desenvolvimento de Sistemas (4º Período)  
**Instituição:** CESAR School

---

## 📄 Relatório Técnico
Toda a fundamentação teórica, respondendo aos problemas que cada padrão resolve, como eles funcionam e seus componentes, está detalhada no documento abaixo:

👉 **[Acesse aqui o Relatório Completo](https://docs.google.com/document/d/1pdJVg_pQc_dyIueJkvVGpWlkzhus5lTOap281C8gl3w/edit?usp=sharing)**

---

## 💻 Implementações Práticas
Para esta atividade, selecionei dois padrões fundamentais para o dia a dia de um desenvolvedor ADS, aplicando-os em contextos reais de mercado:

### 1. Adapter (Adaptador)
- **Arquivo:** `adaptador_cep.py`
- **Contexto:** Adaptação de uma API antiga de Correios (legada) para um sistema moderno de logística que exige objetos de coordenadas geográficas.
- **Por que usar?** Para evitar que mudanças em serviços externos quebrem a lógica central do nosso software.

### 2. Facade (Fachada)
- **Arquivo:** `facade_deploy.py`
- **Contexto:** Simplificação do processo de deploy em produção, gerenciando interações complexas entre Banco de Dados, Servidor e Notificações em um único método.
- **Por que usar?** Para reduzir o acoplamento do cliente com subsistemas complexos e evitar erros manuais em processos repetitivos.

---

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3
- **Ambiente:** VS Code
- **Versionamento:** Git & GitHub

---

## ▶️ Como rodar os exemplos

1. **Certifique-se de ter o Python instalado**

2. **Clone o repositório**

```bash
git clone https://github.com/06gabrielsouza/atividade-padroes-estruturais.git
cd atividade-padroes-estruturais
```

3. **Execute os arquivos**

```bash
python adaptador_cep.py
python facade_deploy.py
```
