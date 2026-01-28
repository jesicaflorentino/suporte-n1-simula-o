# Simulação de Atendimento – Suporte Técnico N1  
## Simulação 01 – Sistema não acessa (erro de conexão)

### 📞 Contexto do chamado
O usuário entra em contato informando que não consegue acessar o sistema interno da empresa.  
O erro apresentado é de **conexão**, mesmo com a internet funcionando normalmente.

---

### 🗨️ Diálogo da simulação

**Usuário:**  
“Oi, bom dia! Cheguei agora e não consigo entrar no sistema interno, dá erro de conexão.”

**Suporte N1:**  
“Bom dia! Esse problema começou hoje? Os outros usuários conseguem acessar normalmente?”

**Usuário:**  
“Sim, começou hoje e é só comigo que não acessa. A internet está funcionando normalmente.”

**Suporte N1:**  
“Entendi. Houve alguma atualização recente no computador? A data e a hora estão corretas?”

**Usuário:**  
“Teve atualização ontem à noite e a data está errada.”

**Suporte N1:**  
“Isso explica o erro. Ajuste a data e a hora para a forma automática, reinicie o navegador e tente novamente.”

**Usuário:**  
“Agora sim! Deu certo.”

---

### 🔍 Análise do Suporte N1

A partir das informações coletadas, o suporte identifica que:
- O erro ocorre apenas com um usuário
- A conexão com a internet está funcional
- Houve atualização recente do sistema
- A data e hora do computador estão incorretas

Esses indícios apontam para um **problema de validação de certificados**, comum em sistemas internos que utilizam autenticação segura.

---

### 🛠️ Ação aplicada

- Orientação para ajustar **data e hora automaticamente pelo sistema operacional**
- Reinício do navegador para aplicar a correção
- Novo teste de acesso ao sistema

A correção foi suficiente para restabelecer o acesso, sem necessidade de escalonamento.

---

### 📌 Encerramento técnico

Muitos sistemas utilizam **certificados digitais** para segurança e autenticação.  
Quando a data ou a hora do computador está incorreta, o certificado pode parecer expirado ou inválido, causando falha no login ou impedindo o carregamento do sistema.
