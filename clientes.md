# Clientes

## Definição

Nesta área, estarão dispostos todos os seus Clientes, sejam eles formandos, participantes de congresso, ou qualquer outro perfil de cliente que você atende.

Na lista de clientes você terá acesso a uma lista com todos os seus clientes organizados por ID (gerado automaticamente e de forma autonumerada pelo sistema), E-mail, Instituição e Turma. Além disso, existem outras colunas que visam auxiliar na gestão e também na operação da plataforma, sendo estas colunas:

- **Foto Perfil** - Nesta coluna é exibido por meio de símbolos de Certo (✓) ou Falso (X) a presença de uma foto de Perfil (Avatar) no cadastro do Cliente. O **Avatar** é uma variável obrigatória e fundamental para a realização do reconhecimento facial das fotos do cliente. 

- **Fotos** - Botão com o número de fotos reconhecidas para o cliente no momento. Ao clicar no botão, você será redirecionado a Biblioteca de Fotos Reconhecidas do Cliente.

- **Fav.** - Aqui é informado se o cliente finalizou ou não a etapa de favoritação de fotos em seu acesso por meio de símbolos de Certo (✓) ou Falso (X).

- **Down.** - Aqui é informado se o cliente realizou o download de fotos, se permitido, em seu acesso por meio de símbolos de Certo (✓) ou Falso (X).

- **Ações** - Botões com as ações à serem realizadas para o cliente sendo elas: Enviar foto por e-mail, Download de Todas as Fotos, Alterar Senha do Cliente, Alterar Cadastro do Cliente e Remover Cliente

<div align=center>
<img class="border1" width="80%" src="../_media/clientelista.png"/>
</div>

## Cadastro

Para cadastrar um novo cliente em seu acesso, clique no botão no canto superior direito **Adicionar Cliente**. Você será redirecionado ao formulário de cadastro de cliente.

Os campos para criação do cliente são os de:

- Instituição
- Turma
- Nome do Cliente (Sendo este o único campo obrigatório para o cadastro)
- E-mail
- Senha
- Confirmação da Senha
- CPF
- Data de Nascimento
- Código do Editor (Campo preenchido automaticamente, se sincronizado com o e-commerce)
- Limite de Fotos para Favoritar
- Campos de Endereço: Cep, Logradouro, Número, Complemento, Bairro, Cidade, Estado.

<div align=center>
<img class="border1" width="80%" src="../_media/clientecad.png"/>
</div>

A **Foto de Avatar** fica disponível para atribuição ao cadastro do cliente após a criação, acessando o registro do cliente cadastrado por meio do botão de **Alterar**.

<div align=center>
<img class="border1" width="80%" src="../_media/clientefoto.png"/>
</div>

## Exportar para Loja

Ao selecionar clientes por meio do checkbox disponibilizado na primeira coluna no canto esquerdo de cada cliente, você poderá exportá-los para seu e-commerce fazendo com que estes registros também fiquem disponíveis no e-commerce.

## Importar Clientes

Para cadastrar clientes em lote, você terá disponibilizada uma planilha modelo para que sejam preenchidas informações dos clientes. Ao clicar em **Importar Clientes** você será redirecionado a uma tela onde haverá um link para download da planilha modelo. Após realizar o preenchimento da planilha modelo, na tela da plataforma selecione a Turma e Instituição onde os clientes serão importados e então suba sua planilha. Após concluir a operação, os clientes preenchidos na planilha serão cadastrados automaticamente em seu acesso do Pluga.

!> A foto de avatar deve ser definida por cliente, após a importação.

<div align=center>
<img class="border1" width="80%" src="../_media/import.png"/>
</div>

## Biblioteca de Fotos Reconhecidas do Cliente

Ao clicar no botão presente na coluna de **Fotos**, você será redirecionado a lista com todas as fotos reconhecidas do cliente. Nesta tela você terá como realizar operações importantes como o **Reconhecimento Facial** e a filtragem de fotos por Turma, Instituição, Evento e Fotógrafo.

<div align=center>
<img class="border1" width="80%" src="../_media/reconhecidas.png"/>
</div>

### Reconhecer Fotos ###

No Botão de **Reconhecer Fotos**, será realizada a operação de reconhecimento facial do cliente, armazenando todas as fotos da turma relacionada ao cliente à sua biblioteca. O processo de reconhecimento facial é feito de cliente a cliente e tem duração média de 15 segundos. Após a conclusão da operação, todas as fotos estarão disponíveis para gestão na biblioteca.

### Upload de Fotos ###

Caso o administrador tenha fotos já separadas para o cliente selecionado, é possível realizar o upload diretamente na biblioteca de fotos do cliente por meio do botão **Upload Fotos**. Após clicar, basta vincular ao evento e fotógrafo e então subir as fotos do seu dispositivo para o cliente.

### Vincular Fotos ###

Ao clicar no botão **Vincular Fotos**, você será redirecionado a lista com todas as fotos **Não Reconhecidas**, também disponível para filtragem na seção de **Fotos**. Caso hajam fotos que estejam com essa classificação. Nesta lista, você poderá selecionar as fotos exibidas e vincular à biblioteca do cliente. Ao realizar a operação, as fotos selecionadas não serão mais classificadas como "Fotos Não Reconhecidas".

### Filtrar ###

Esta função permite com que você faça a filtragem de fotos na lista do cliente permitindo com que você veja somente as fotos classificadas com os filtros selecionados. Você pode filtrar por:

- Nome da Foto (Filename original do arquivo)
- Fotógrafo
- Evento

## Compartilhamento por E-mail ##

No primeiro ícone na coluna de ações está disposta a funcionalidade de **"Compartilhamento por E-mail"**. Esta função permite com que o administrador realize o envio de fotos do cliente para seu e-mail, diretamente pelo painel administrativo. Esta função é interessante caso você trabalhe somente com a gestão de fotos por meio do painel, sem que ofereça dados de acesso de Login e Senha para seus clientes.

Ao cliar no botão, você será redirecionado ao formulário de criação do E-mail. Primeiramente no campo de seleção **Como deseja enviar as fotos**, defina o evento. As fotos do evento selecionado serão enviadas para o cliente. 

?> O envio de fotos segregado por evento permite com que você crie modelos de negócio que envolvem a venda de pacotes de fotos. Ex: O cliente pode comprar somente as fotos do evento de Colação de Grau mas não do Baile de Formatura.

No campo **Corpo do E-mail**, digite a mensagem que deseja enviar para o seu cliente. Esta mensagem será exibida no corpo do e-mail junto do link para download.

?> O e-mail enviado tem o layout de e-mail transacional do Pluga.Vc. O logo no topo do e-mail é o mesmo cadastrado no registro de **Turma** onde o cliente em questão está vinculado.

<div align=center>
<img class="border1" width="80%" src="../_media/email.png"/>
</div>

Após concluir a operação, seu cliente receberá, no e-mail registrado em seu cadastro, uma mensagem com o link para download das fotos e a mensagem definida pelo administrador.







