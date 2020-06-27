# git-caboclinhos
Teste do desenvolvimento compartilhado.

(Abra o terminal)

1 - Selecione um diretório

2 - git clone https://github.com/math3usc/git-caboclinhos.git

3 - cd git-caboclinhos

Pronto, agora você tem o repositório em seu computador.

Sempre que for mexer no código, verificar se há novas alterações pra trabalhar na versão mais recente e criar novo galho.

1 - git checkout master

2 - git pull origin master (check updates)

3 - git checkout -b index novoGalho
#criar novo galho para edição

Após fazer mudanças, você deve salvá-las e refazer o upload dos arquivos.

1 - git add .

2 - git commit -m "breve comentário do que foi adicionado"

3 - git push origin novoGalho
#nesse "novoGalho", você deve colocar um nome que faça menção ao que foi alterado. esse galho vai ser analisado pelos colaboradores para ser incorporado ao programa principal depois da aprovação geral. (Pra evitar que secretaria faça merda no código).
