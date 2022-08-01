1- A 2a versão foi para o commit

2-Como o arquivo ficou salvo na area de staging, nao houves problemas em deletar o arquivo da WT. Ao fazer o commit,
este arquivo ficou salvo no repositorio

4- No campo "changes" houve a exclusão de ANSWERS e a criacao de RESPOSTAS

5-hash: e69843ae9f7a4a55e5ecc59a835aeebddbfee402
A saida de -p e a exibicao (sem ser descricao) do codigo que foi adicionado ou removido (destacado em 
verde ou vermelho) do ultimo arquivo do commit. Em outras palavras, foi feito um diff entre a versao do arquivo mais
recente e a versao anterior

6-A partir do git log, percebe-se que o a flag amend faz com que o git, ao inves de adicionar mais um commit na branch, substitua
o commit anterior pelo novo commit

7-Revert: Cria um novo commit que copia um commit anteriormente adicionado no repositorio. Esse comando
tem a intencao de desfazer um ou mais commits, mas mantendo-os no historico.

Checkout: Este comando checa o conteudo em seu repositorio e adiciona/substitui um ou mais arquivos do repositorio em sua working tree.
Este comando nao altera o historico do repositorio

Reset: Descarta um commit (ou varios) do seu repositorio local. Pode ser hard (em que se deleta permanentemente os commits de
sua maquina) ou soft, em que as alteracoes vao para a sua area de stage

8-.gitignore faz com que o git ignore certos arquivos nao rastreados da WT, desde que atenda parametros pre estabelecidos. Neste caso,
o git ignora todos os arquivos com extensão .pdf. Isso pode ser util quando se deseja usar o comando git add --all, mas estabelecendo
excecoes

9-A diferenca é que o fetch apenas faz o download do repositório remoto e atualiza o repositorio da maquina, enquanto o pull nao so
atualiza o repositorio privado como tambem atualiza a WT

10-Checkout pega o conteudo de uma branch e o reproduz na sua WT, criando, substituindo ou deletando arquivos. Nesse exemplo, ao trocar
de branch e fazer checkout, o arquivo de texto criado saiu da WT e continuou salvo no repositorio na nova branch criada

11- Embora a branch tenha sido deletada, o arquivo de texto ficou salvo no repositorio no ultimo commit da branch master devido
ao merge

12-O conteudo do arquivo, ao fazer stash, volta a ser o que era antes de fazer as modificacoes. Ja ao fazer o pop do
stash, o arquivo recupera as modificacoes que tinham sido feitas na WT.

