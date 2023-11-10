# Git Comandos Mais Usados

Este é um guia rápido para alguns dos comandos Git mais frequentemente utilizados. Estes comandos são essenciais para gerenciar repositórios Git e colaborar eficientemente em projetos de software.

## Configurações do Usuário

Configure as informações do usuário, como e-mail e nome:

```bash
git config --global user.email "sam@google.com"
git config --global user.name "Seu Nome"
```

# Inicializar um Repositório
Inicie um novo repositório Git em um diretório existente ou em um novo projeto:

```bash
git init
```

# Clonar um Repositório Existente
Clone (copie) um repositório existente para o seu computador:


```bash
git clone <URL> # Substitua <URL> pela URL do repositório.
```

# Adicionar e Confirmar Mudanças
Após fazer alterações nos arquivos do seu projeto, adicione e confirme as mudanças:


```bash
git add . # Adiciona todas as mudanças
git commit -m "Mensagem de commit"  # Confirma as mudanças com uma mensagem descritiva
```
# Ramificação (Branching)
 Crie uma nova ramificação para trabalhar em novas funcionalidades ou correções de bugs:


```bash
git branch nome-da-branch     # Cria uma nova branch
git checkout nome-da-branch   # Muda para a nova branch
```
# Mesclar Mudanças
Para mesclar as mudanças de uma branch de volta à branch principal (geralmente 'master'):


```bash
git checkout master         # Muda de volta para a branch principal
git merge nome-da-branch    # Mescla as mudanças da branch nome-da-branch
```
# Atualizar e Enviar Mudanças
Obtenha as últimas mudanças de um repositório remoto e envie suas mudanças:


```bash
git pull origin master      # Obtém as últimas mudanças do repositório remoto
git push origin master      # Envia suas mudanças para o repositório remoto
```

## Esses são comandos básicos do Git para começar. Consulte a documentação oficial do Git para obter mais informações.