# Como criar uma Máquina Virtual no Azure

Este guia passo a passo explica de forma simples como criar uma máquina virtual (VM) no Azure.

---

## 1. Acesse o Portal do Azure
- Vá até o site [portal.azure.com](https://portal.azure.com).
- Faça login com sua conta Microsoft ou de estudante.
  !(images/pagina inicial.jpg)
_01. página inicial do Azure_
---

## 2. Crie um novo recurso
- Clique em **"Criar um recurso"** no menu lateral esquerdo.
- Selecione **"Máquina Virtual"** na lista de opções.
- !(images/criar maquina_passo 1.jpg)
_02. criar maquina_

---

## 3. Configure os detalhes básicos
- **Assinatura**: escolha sua assinatura do Azure.
- **Grupo de recursos**: crie um novo ou use um existente (um agrupamento de recursos relacionados).
- **Nome da VM**: dê um nome para sua máquina virtual.
- **Região**: escolha uma região próxima a você para melhor desempenho.
- **Imagem**: selecione o sistema operacional desejado (exemplo: Windows Server, Ubuntu, etc.).
- **Tamanho**: escolha o tamanho da VM, que define recursos como CPU e memória (para iniciantes, opções padrão funcionam bem).

- !(images/criar maquina_passo 2.jpg)
_02. Configuração_
- !(images/criar maquina_passo 3.jpg)
_03. Configuração_
---

## 4. Configure as opções de autenticação
- **Método de login**:
  - Senha: crie uma senha forte.
  - Chave SSH (opcional): para conexões mais seguras, especialmente no Linux.
- **Nome de usuário**: crie um usuário administrador.
- !(images/criar maquina_passo 4.jpg)
_04. Configurar Usuário e Senha_
---

## 5. Configure as opções de rede
- **Rede virtual**: use a padrão ou crie uma nova.
- **Endereço IP público**: deixe como padrão para acesso externo.
- **Portas de entrada**:
  - Para Windows, geralmente habilite **RDP (3389)**.
  - Para Linux, habilite **SSH (22)**.
- !(images/criar maquina_rede_passo 1.jpg)
_05. Configurar Opções Rede_
---

## 6. Revisar e criar
- Revise todas as configurações.
- Clique em **"Criar"** para iniciar a implantação da VM.
- !(images/criar maquina_rede_passo 1.jpg)
_06. Configurar Opções Rede_
---

## 7. Acompanhe a implantação
- Aguarde alguns minutos enquanto o Azure cria sua máquina virtual.
- Quando finalizar, você verá uma mensagem de sucesso.
- !(images/criar maquina_criar_passo 1.jpg)
_07. Detalhes da implantação_
- !(images/criar maquina_criar_passo 2.jpg)
_07. Detalhes da implantação (2)_
- !(images/criar maquina_criar_passo 3.jpg)
_07. Detalhes da implantação (3)_
- !(images/criar maquina_criar_passo 4.jpg)
_07. Detalhes da implantação (4)_
- !(images/criar maquina_criar_finalizado.jpg)
_07. Impltantação finalizada_
---

## 8. Acesse sua máquina virtual
- Para Windows:
  - Use o **Conexão de Área de Trabalho Remota (RDP)**.
  - Clique na VM no portal, depois em **Conectar** e baixe o arquivo RDP.
- Para Linux:
  - Use um cliente SSH com o IP público e o usuário criado.
- !(images/conectando na maquina virtual 1.jpg)
_07. Conectando na máquina_
- !(images/conectando na maquina virtual 2.jpg)
_07. Conectando na máquina (2)_
- !(images/conectando na maquina virtual 3.jpg)
_07. Conectando na máquina (3) - aceitar certificado (SIM)_
- !(images/conectando na maquina virtual 4.jpg)
_07. Conectando na máquina (4) - página inicial_
- !(images/conectando na maquina virtual 5.jpg)
_07. Conectando na máquina (5) - Server Manager_
- !(images/conectando na maquina virtual 7.jpg)
_07. Conectando na máquina (6) - visualizando Local Server_
---

## Parabéns!
Você criou sua primeira máquina virtual no Azure! Agora pode explorar, instalar programas e aprender mais sobre nuvem.

---

Este laboratório foi realizado com instruções do Bootcamp Microsoft Azure Essentials da [DIO](https://dio.me)! 😊
