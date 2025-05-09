
# 💻 Desafio: Criação de Máquina Virtual no Azure – DIO + XP Inc.

Este repositório contém a documentação do desafio proposto no bootcamp **Cloud com Inteligência Artificial** da DIO em parceria com a **XP Inc.**. O objetivo foi praticar a criação e configuração de uma máquina virtual (VM) na plataforma Microsoft Azure, documentando cada etapa para estudo e futuras implementações.

---

## 🧠 Objetivos do Desafio

- Aplicar os conceitos de cloud computing utilizando o Microsoft Azure.
- Criar e configurar uma máquina virtual Linux ou Windows.
- Documentar o processo técnico de forma clara e objetiva.
- Compartilhar o conhecimento utilizando o GitHub.

---

## 🛠️ Ferramentas Utilizadas

- Microsoft Azure (portal web)
- Git e GitHub
- (Opcional) Terminal ou Remote Desktop
- VS Code ou editor de texto

---

## 📋 Etapas Realizadas

### 1. Acesso ao Portal Azure
- Acesso ao portal: [https://portal.azure.com](https://portal.azure.com)

### 2. Criação do Grupo de Recursos
- Nome: Meu azure
- Região: Brasil

### 3. Criação da Máquina Virtual
- Nome: Máquina Virtual Azure
- SO: Ubuntu 20.04 LTS (ou Windows Server 2022)
- Tamanho: B1s
- Autenticação: Chave SSH (Linux) ou Senha (Windows)
- Porta liberada: 22 (Linux) ou 3389 (Windows)

### 4. Acesso à Máquina Virtual
- Acesso via `ssh` usando o IP público:
```bash
ssh azureuser@<IP_da_VM>
```
- Ou acesso via RDP, no caso do Windows.

---

## 📂 Estrutura do Repositório

```
azure-vm-desafio-dio/
├── README.md
└── images/
    ├── grupo-de-recursos.png
    ├── configuracao-vm.png
    ├── acesso-vm.png
```

---

## 🖼️ Imagens e Capturas de Tela

As imagens utilizadas para ilustrar o processo estão na pasta `/images`.

| Etapa                     | Imagem                          |
|---------------------------|----------------------------------|
| Grupo de Recursos         | ![Grupo](images/grupo-de-recursos.png) |
| Criação da VM             | ![VM](images/configuracao-vm.png)      |
| Acesso à VM               | ![Acesso](images/acesso-vm.png)        |

---

## 💡 Dicas Aprendidas

- A conta gratuita do Azure permite usar a VM B1s por até 750h/mês.
- Sempre nomeie seus recursos de forma organizada.
- Usar chave SSH é mais seguro do que senha para Linux.
- Após a criação da VM, sempre monitore o uso para evitar cobranças.

---

## 📚 Referências

- [Início Rápido: Criar uma VM no Azure (Microsoft)](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [Documentação Oficial Azure](https://learn.microsoft.com/pt-br/azure/)
- [Markdown no GitHub](https://guides.github.com/features/mastering-markdown/)

---

## 🚀 Autor

Desenvolvido por Arlana Yung – participante do bootcamp DIO + XP Inc.
