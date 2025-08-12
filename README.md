# Como criar uma Máquina Virtual no Azure

Este guia passo a passo explica de forma simples como criar uma máquina virtual (VM) no Azure. Neste exemplo, criaremos uma máquina com o sistema operacional Windows.

---

## 1. Acesse o Portal do Azure
- Vá até o site [portal.azure.com](https://portal.azure.com).
- Faça login com sua conta Microsoft ou de estudante.
### _01. página inicial do Azure_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/pagina%20inicial.JPG)

---

## 2. Crie um novo recurso
- Clique em **"Criar um recurso"** no menu lateral esquerdo.
- Selecione **"Máquina Virtual"** na lista de opções.
### _02. criar maquina_
![.](https://github.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/blob/main/images/pagina%20criar%20recurso.jpg)

---

## 3. Configure os detalhes básicos
- **Assinatura**: escolha sua assinatura do Azure.
- **Grupo de recursos**: crie um novo ou use um existente (um agrupamento de recursos relacionados).
- **Nome da VM**: dê um nome para sua máquina virtual.
- **Região**: escolha uma região próxima a você para melhor desempenho.
- **Imagem**: selecione o sistema operacional desejado (exemplo: Windows Server, Ubuntu, etc.).
- **Tamanho**: escolha o tamanho da VM, que define recursos como CPU e memória (para iniciantes, opções padrão funcionam bem).

### _03.1 Configuração_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_passo%201.JPG)
### _03.2 Configuração_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_passo%202.JPG)
### _03.3 Configuração_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_passo%203.JPG)
### _03.4 Configuração de Tamanho, nesta tela detalha as configurações de tamanhos e preços disponíveis_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_passo%203_tamanhos%20vm_precos.JPG)


---

## 4. Configure as opções de autenticação
- **Método de login**:
  - Senha: crie uma senha forte.
  - Chave SSH (opcional): para conexões mais seguras, especialmente no Linux.
- **Nome de usuário**: crie um usuário administrador.
### _04. Configurar Usuário e Senha_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_passo%204.JPG)

---
## 5. Configure o Tipo de Disco do SO
- **Método de login**:
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_disco_passo%201.JPG)

---

## 6. Configure as opções de rede
- **Rede virtual**: use a padrão ou crie uma nova.
- **Endereço IP público**: deixe como padrão para acesso externo.
- **Portas de entrada**:
  - Para Windows, geralmente habilite **RDP (3389)**.
  - Para Linux, habilite **SSH (22)**.
### _06. Configurar Opções Rede Criar Endereço IP Público_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_rede_passo%201.JPG)

---

## 7. Configure Gerenciamento, Monitoramento e Marcas
- **Gerenciamento**: mantenha as opções padrão.
- **Monitoramento**: mantenha as opções padrão.
- **Marcas**: você pode colocar tag para localizar os recursos com facilidade.
### _07.1 Configurar Gerenciamento_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_gerenciamento_passo%201.JPG)
### _07.2 Configurar Monitoramento_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_monitoramento_passo%201.JPG)
### _07.3 Configurar Marcas_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_marcas_passo%201.JPG)

---

## 8. Revisar e criar
- Revise todas as configurações.
- Clique em **"Criar"** para iniciar a implantação da VM.
### _08.1 Revisar (1)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_revisar_passo%201.JPG)
### _08.2 Revisar (2)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_revisar_passo%202.JPG)
### _08.3 Revisar (3)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_revisar_passo%203.JPG)

---

## 9. Acompanhe a implantação
- Aguarde alguns minutos enquanto o Azure cria sua máquina virtual.
- Quando finalizar, você verá uma mensagem de sucesso.
### _09.1 Detalhes da Implantação (1)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_criar_passo%201.JPG)
### _09.2 Detalhes da Implantação (2)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_criar_passo%202.JPG)
### _09.2 Detalhes da Implantação (3)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_criar_passo%203.JPG)
### _09.4 Detalhes da Implantação (4)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_criar_passo%204.JPG)
### _09. Impltantação finalizada_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/criar%20maquina_criar_finalizado.JPG)

---

## 10. Ir para o Recurso
- Verifique o recurso criado e as informações disponíveis.
- É possível navegar pelo menu e alterar as configurações que desejar.
- Visualizar o IP públic0, usuário da máquina e etc.
### _10.1 Página inicial do Recurso_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/serverwd_pagina%20inicial%20do%20recurso.JPG)
### _10.2 Detalhes do Recurso_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/serverwd_pagina%20inicial%20do%20recurso_2.JPG)
### _10.3 Detalhes do SO_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/serverwd_configuracoes_sistema%20operacional.JPG)
### _10.4 Consulte disponibilidade da máquina em Ajuda >> Diagnostico de inicialização_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/serverwd_diagnostico%20de%20inicializacao.JPG)

## 11. Acesse sua máquina virtual
- Para Windows:
  - Use o **Conexão de Área de Trabalho Remota (RDP)**.
  - Clique na VM no portal, depois em **Conectar** e baixe o arquivo RDP.
- Para Linux:
  - Use um cliente SSH com o IP público e o usuário criado.
### _11.1 Conectando na máquina - IP público (1)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/conectando%20na%20maquina%20virtual%201.JPG)
### _11.2 Conectando na máquina - Credenciais (2)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/conectando%20na%20maquina%20virtual%202.JPG)
### _11.2 Conectando na máquina - Aceitar certificado (SIM) (2)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/conectando%20na%20maquina%20virtual%203.JPG)
### _11.3 Conectando na máquina - Tela Inicial (3)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/conectando%20na%20maquina%20virtual%204.JPG)
### _11.4 Conectando na máquina - Server Manager (4)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/conectando%20na%20maquina%20virtual%205.JPG)
### _11.5 Conectando na máquina - Local Server (5)_
![.](https://raw.githubusercontent.com/GabrielaBrazSantos/resumo-lab-dio-criando-maquinas-virtuais-azure/refs/heads/main/images/conectando%20na%20maquina%20virtual%207%20-%20local%20server.JPG)

---

## Parabéns!
Você criou sua primeira máquina virtual no Azure! Agora pode explorar, instalar programas e aprender mais sobre nuvem.

---

Este laboratório foi realizado com instruções do Bootcamp Microsoft Azure Essentials da [DIO](https://dio.me)! 😊
