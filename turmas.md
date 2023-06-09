## Turmas

## Definição

O registro de **Turmas** é um dos registros mais importantes na hierarquização da sua base de fotos. Trata-se da camada que vem logo após da Instituição. A Turma é um dado obrigatório no cadastro de cliente e, no reconhecimento facial no cadastro do cliente, as fotos que serão analisadas na operação do Reconhecimento serão todas as fotos da Turma em que o cliente está vinculado. Consequentemente, as fotos abaixo da Turma, ou seja, as fotos dos Eventos e Fotógrafos também serão analisadas.

Na lista de turmas, todas as turmas cadastradas serão exibidas organizadas pelas colunas de **ID** (gerados automaticamente e de maneira autonumérica), **Nome**, **Instituição** além de:

- **Fotos** - Botão com o número de fotos vinculadas a turma. Ao clicar no botão, você será redirecionado a uma tela com todas as fotos junto às opções de **Baixar todas as fotos da Turma** e também de **Remover todas as fotos da Turma**.

- **Ações** - Botões com as ações à serem realizadas para a turma sendo elas: Gerar Link para upload de fotos, gerar link para o cliente se cadastrar, Download de Fotos favoritadas/reconhecidas da turma, Editar Turma e Remover Turma

<div align=center>
<img class="border1" width="80%" src="../_media/turmalista.png"/>
</div>

## Cadastro

Para criar um novo registro de turma, clique em **Adicionar** no canto superior esquerdo e você será redirecionado ao formulário de criação de turma.

No formulário, os campos a serem preenchidos são:

- **Logo da Turma** - Imagem que será exibida no formulário de cadastro, no link de upload de fotos e também nos e-mails transacionais enviados para os clientes vinculados a turma.
- **Nome da Turma**
- **Instituição**
- **Qual a Forma que os clientes tem acesso as fotos?** - Aqui será definido como o cliente, ao acessar seu usuário, poderá interagir com suas fotos. As opções são: **Padrão**: O cliente poderá apenas visualizar e favoritar suas fotos e prosseguir ao e-commerce (caso haja integração). **Download**: O cliente poderá realizar o download de suas fotos. **E-mail**: O cliente poderá enviar um link de download para seu e-mail com as fotos. **E-mail + Download**: As duas opções ficarão disponíveis para os clientes da turma.
- **Clientes conseguem visualizar todas as fotos da turma?** - Se disponível a opção para download e/ou e-mail, o cliente baixará fotos **favoritadas** ou **reconhecidas**(todas).
- **Clientes podem utilizar o reconhecimento facial para atualizar suas fotos?(SIM/NÃO)** - Define se o cliente poderá realizar o reconhecimento na sua biblioteca de fotos, em seu acesso de cliente.
- **Clientes recebem email de boas vindas?(SIM/NÃO)** - Ao se cadastrar, no link para Cadastro do Cliente, define se o cliente receberá um e-mail de boas-vindas ou não.
- **Código da Subloja** - Se a turma tiver integração com o e-commerce, aqui deverá ser definido o código da subloja. No campo, há a localização do valor de código da subloja no painel do e-commerce.
- **Acesso à Loja** - Termo na URL do e-commerce que define o acesso a loja.
- **URL da Subloja** - URL de onde os clientes realização o acesso ao e-commerce.

Os campos de integração não são obrigatórios e serão preenchidos somente se você pretende oferecer produtos de e-commerce para a turma.

Após preencher os campos, clique em **Cadastrar** para finalizar a operação. A turma então ficará disponível para vinculação na plataforma.

<div align=center>
<img class="border1" width="80%" src="../_media/turmacad.png"/>
</div>

## Gerar Link para Upload de Fotos

Ao clicar neste botão, no registro da turma, será copiado um link para sua área de transferência. Este link leva a uma tela com um formulário para **Upload de Fotos** que serão armazenadas em seu acesso vinculados a turma em questão.

Este link pode ser enviado para pessoas que não sejam administradores ou fotógrafos para que estas possam também armazenar fotos.

<div align=center>
<img class="border1" width="80%" src="../_media/upcad.png"/>
</div>


## Gerar Link para o Cliente se Cadastrar

Ao clicar neste botão, no registro da turma, será copiado um link para sua área de transferência. Este link leva a uma tela com um formulário para cadastro de Cliente. O cliente preencherá, no formulário, as informações de:

- Foto de Avatar (Para o Reconhecimento Facial)
- Nome
- E-mail
- Senha
- Confirmação de Senha

Após a conclusão do cadastro, o sistema fará o reconhecimento automaticamente e o **cliente terá acesso instantâneo a suas fotos reconhecidas**.

?> Este procedimento pode ser crucial para sua operação pois ele **elimina a etapa de cadastro de cliente e definição de avatar** uma vez que o seu próprio cliente fará isso, criando seu cadastro e definindo a foto de avatar.

O link de cadastro da turma poderá ser enviado para os participantes/formandos da turma em questão e o cadastro os vinculará automaticamente a instituição e turma correspondente.

<div align=center>
<img class="border1" width="80%" src="../_media/cadastro.png"/>
</div>

## Download de Fotos da Turma

Ao clicar no botão de Download de Fotos da Turma, você será redirecionado a uma tela onde há a opção de seleção de download de **Fotos Favoritadas** ou **Fotos Reconhecidas**. Essas opções definirão quais fotos da turma você irá baixar.

As fotos da turma serão baixadas em um arquivo **.ZIP** organizadas por aluno, ou seja, é uma ótima funcionalidade para guardar suas fotos em seu dispositivo de maneira já organizada.

Para realizar o download das fotos, é necessário, primeiro, clicar no botão **Gerar Links**. Ao clicar, o sistema iniciará o processo de geração de links de download. O sistema fará a geração de múltiplos links para a realização do download de fotos da turma. Os links são separados pois as turmas possuem muitas fotos e para que o servidor possa gerar todas as fotos, é preciso separar em arquivos diferentes pois o tamanho é muito grande. O número de links varia conforme o número de fotos reconhecidas/favoritadas. Se houverem poucas fotos, consequentemente haverão menos links para geração e vice-versa. Os links ficam disponíveis por 15 dias após a geração. Depois desse período, será necessário gerar novamente.

<div align=center>
<img class="border1" width="80%" src="../_media/links.png"/>
</div>

!> Caso haja uma atualização na turma, seja de novo reconhecimento facial nos clientes ou novas favoritações por parte dos clientes, será necessário realizar uma nova geração. Para isso, delete os links disponíveis e gere os links novamente.