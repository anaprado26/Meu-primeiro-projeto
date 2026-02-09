# Meu-primeiro-projeto
# 1. Iniciar o rastreamento do Git na pasta
# Isso cria uma pasta invisível .git que guardará o histórico
git init
# 2. Verificar o que mudou (o Git te mostra arquivos novos em
vermelho)
git status
# 3. Adicionar arquivos para a "área de preparação" (Stage)
# O ponto (.) adiciona tudo o que foi alterado
git add .
# 4. Salvar a versão oficialmente com uma mensagem explicativa
# Pense nisso como o "Save Point" do jogo
git commit -m "Primeiro commit: Estrutura inicial do projeto"
# 5. Ver o histórico de "saves" que você criou
git log
