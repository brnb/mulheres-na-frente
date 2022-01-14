# Usando o terminal (Mac)

## Comandos:
<i>ls</i> List: mostra tudo o que tem dentro de uma pasta;

<i>cd</i> Change Directory: muda de pasta, para entrar numa determinada pasta use "cd nome-da-pasta" e para voltar a pasta acima use "cd .."

<i>touch</i> Não sei o que significa, mas cria um arquivo. Coloque a extensão do arquivo ao final do nome: "nome.txt", por exemplo.

<i>rm</i> Remove: remove, né. inclua o comando <i>-rf</i> que será removido todo o conteúdo da pasta, se estiver removendo uma pasta, no caso.

# Para criar um git, começar a comitar arquivos e lançar o projeto no GitHub.

Bem, primeiro tem que baixar o git no seu computador, e isso eu não sei exatamente como faz, talvez seja melhor buscar no google mesmo... (Alguém consegue explicar aqui?)

Aí, tem que criar uma chave SSH e um token, e configurar na sua máquina e no GitHub. Mais uma coisa que já não lembro como faz, vou ter que estudar isso mais vezes, mas de novo, se alguém puder incluir aqui como faz isso, ótimo.

Bem, depois que já está tudo pronto, e eu só lembro pouco a partir disso, a gente tem que iniciar o .git, configurar nosso nome e email e empurrar o projeto pro GitHub... E isso faz assim: 

- Primeiro, entra na pasta do projeto, com o botão direito pede pra abrir com o terminal;
- Abriu o terminal, na pasta do seu projeto, coloque o comando: 

<i>git init</i> e pronto, criou a pasta.

Depois, inclua os comandos:

<i> git config --global user.name "SeuNome" </i> para avisar que aquele projeto é seu... e 

<i>git config --global user.email "SeuEmail@email"</i> para que seja sua própria conta do GitHub e essas coisas (Não entendi muito bem, mas se não colocar a conta certa, não funciona).

aí você tem que comitar sua pasta e seus arquivos, pra isso, primeiro você vai digitar os comandos:

<i>git add *</i> para adicionar a pasta/arquivos

<i>git commit -m "uma declaração explicativa"</i>

<i>git remote add origin https-do-github-encontrado-no-espaço-code-do-repositório</i> isso pra adicionar as coisas...

<i>git push origin master</i> pra empurrar as pastas do seu projeto pra página do seu repositório

<i>git pull origin master</i> para "puxar" os arquivos de um projeto no GitHub para o seu computador, para poder editá-lo e deixar todos os arquivos na mesma "ordem"... 

#### Bem, eu fiz esse arquivo/projeto para vir aqui caso eu esqueça algum comando, mas sinto que não está completamente correto. Se alguém quiser editar isso aqui, ou mesmo criar arquivos diferentes com mais detalhes, ou ainda linkar para informações adicionais na web, seria incrível... (ainda não sei como linkar páginas no GitHub).
