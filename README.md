# 🚀 Criando um Grupo de Recursos e um Recurso na Microsoft Azure

Este repositório faz parte do desafio de projeto da DIO com o objetivo de aplicar, na prática, os conceitos aprendidos sobre **grupos de recursos** e **provisionamento de recursos** na plataforma Microsoft Azure.

---

## 📚 O que você vai aprender com este projeto:

- Conceito e função dos **Grupos de Recursos** na Azure
- Como criar um **Grupo de Recursos** via portal
- Como adicionar um **recurso simples** (ex: Conta de Armazenamento) ao grupo
- Prática de organização de infraestrutura na nuvem

---

## 🧠 Conceitos principais

### 🔹 Grupo de Recursos

Um **Grupo de Recursos** é um contêiner lógico na Azure que agrupa recursos relacionados que compartilham o mesmo ciclo de vida. Ele permite:
- Gerenciamento centralizado (como exclusão e monitoramento)
- Aplicação de políticas
- Organização de custos por projeto, equipe ou ambiente

> Exemplo: você pode criar um grupo chamado `meu-projeto-web` e dentro dele incluir a VM, o banco de dados e o armazenamento do mesmo sistema.

### 🔹 Recurso

Um **Recurso** na Azure é qualquer item utilizável da nuvem, como:
- Conta de Armazenamento (Storage Account)
- Banco de Dados
- Máquina Virtual (VM)
- App Web, etc.

---

## 🛠️ Passo a Passo no Portal Azure

### 1. Acesse o Portal Azure
Acesse: [https://portal.azure.com](https://portal.azure.com)

### 2. Criar um Grupo de Recursos

1. No menu lateral, clique em **Grupos de Recursos**
2. Clique em **Criar**
3. Selecione:
   - **Assinatura** (ex: Gratuita)
   - **Nome do grupo** (ex: `grupo-primeiro-projeto`)
   - **Região** (ex: Brazil South)
4. Clique em **Revisar + Criar** e depois **Criar**

> 💡 A escolha da região é importante, pois define a localização física dos recursos.

### 3. Criar um Recurso Simples (Conta de Armazenamento)

1. No menu lateral, clique em **Criar um recurso**
2. Pesquise por **Conta de Armazenamento** e selecione
3. Preencha os dados:
   - **Grupo de Recursos**: selecione o que você acabou de criar
   - **Nome da conta**: nome único, sem espaços
   - **Região**: mesma do grupo
   - **Tipo de Redundância**: padrão (LRS)
4. Clique em **Revisar + Criar** e depois **Criar**

---

## ✅ Resultado Final

Você terá criado com sucesso:
- Um **Grupo de Recursos** organizado
- Um **Recurso** dentro dele (uma conta de armazenamento)
  
Essa estrutura facilita a manutenção, escalabilidade e organização da sua infraestrutura em nuvem.

---

## 🔗 Links úteis

- [Portal Microsoft Azure](https://portal.azure.com)
- [Documentação oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Criar Grupo de Recursos - Microsoft Docs](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/manage-resource-groups-portal)
- [Sobre Contas de Armazenamento](https://learn.microsoft.com/pt-br/azure/storage/common/storage-account-overview)

---

## 👨‍🎓 Projeto acadêmico

Este projeto foi desenvolvido como parte do desafio da DIO para reforçar os conhecimentos em Microsoft Azure e construção de portfólio.
