Este template oferece uma estrutura básica para um cofre no [Obsidian](https://obsidian.md) voltado à pesquisa científica e trabalhos acadêmicos em geral. Ela foi pensada para ser o mais simples possível e facilitar o início do processo de construção do seu sistema de "*Personal Knowledge Management*" (PKM). Além disso, pode (e deve) ser adaptada ao longo do tempo conforme as necessidades que surgirem e as preferências pessoais de organização e manutenção do sistema.

## O que é um cofre? E por que no Obsidian?

Um cofre nada mais é do que uma pasta no computador com subpastas e arquivos de texto em um formato chamado [Markdown](https://pt.wikipedia.org/wiki/Markdown), combinadas a algumas configurações que ampliam as capacidades do Obsidian (por meio de plugins) e estabelecem como ele deve funcionar. Os arquivos de texto contêm anotações diversas e formam um sistema interligado de notas ou ideias que nos auxilia a gerenciar nosso aprendizado.

Além disso, o armazenamento em arquivos de texto com extensão `.md` garante que eles:

- estão sempre no computador, em um formato acessível, e não em alguma base de dados de um serviço na nuvem, por exemplo;
- podem ser abertos em qualquer computador usando qualquer programa que abra arquivos de texto, tais como o Notepad, o que garante preservação das informações no futuro caso o Obsidian não esteja mais disponível por qualquer motivo; e
- podem ser copiados como backup da mesma maneira que quaisquer outros arquivos, inclusive em serviços de nuvem, se desejado.

![Screenshot do Template](https://github.com/rtsaboya/cofre-obsidian-academico-basico/blob/master/06.%20Anexos/template_screenshot_2025_01_13.png)

## Como instalar o template

1. Faça o download do arquivo `.zip` da última versão disponível clicando na seta ao lado do botão "Code," acima e à direita, e selecionando a opção "Download ZIP."
2. Salve o arquivo em uma pasta do computador e descompacte-o para a pasta em que você deseja que o cofre do Obsidian fique armazenado permanentemente. Provavelmente será necessário criar essa pasta especificamente para isso, na localização desejada.
3. Após instalar e abrir o Obsidian, serão oferecidas duas opções: criar um novo cofre vazio ou usar uma pasta existente. Selecione esta segunda opção e aponte para a pasta criada no passo anterior, contendo a estrutura básica de pastas do cofre existente no arquivo ZIP original.
4. Abra a nota "Home" e comece a explorar o cofre.

## Como configurar a integração com o Zotero

1. Faça o download e instale o Zotero.
2. Instale o plugin "Better BibTeX":
	1. Faça o download do arquivo xpi da [última versão disponível](https://github.com/retorquere/zotero-better-bibtex/releases/latest).
	2. No Zotero, vá no menu Tools > Plugins.
	3. Clique na roldana localizada no canto superior direito e selecione "Install plugin from file..."
	4. Na caixa de diálogo, aponte para o arquivo xpi baixado no passo 1.

## Como importar referências do Zotero

Tendo configurado o Zotero como descrito na seção anterior:
1. Certifique-se de que ele esteja rodando e pressione ctrl + shift + O.
2. Uma barra do Zotero se abrirá para você informar qual referência deseja importar. Digite qualquer parte do nome da referência ou de seus autores.
3. Selecione, dentre as opções oferecidas pelo Zotero, a desejada e pressione Enter.
4. O Obsidian irá criar uma nova nota, com o título referenciando o trabalho e seus dados básicos já inseridos no corpo da nota como Propriedades. Caso a referência no Zotero esteja associada a um PDF e existam realces já feitos nele, estes serão importados também.
5. Se desejar personalizar o template de importação do Zotero, é possível abrir a [[Zotero-integration Import Template|nota com o template]] e editar seu conteúdo diretamente. Alternativamente, é possível também duplicá-la e fazer as modificações na cópia, lembrando de depois editar as configurações do plugin Zotero para indicar na opção "Template File" o novo Template a ser usado.
