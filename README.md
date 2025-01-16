# Cadastro de Caminhões

Bem-vindo ao projeto **Cadastro de Caminhões**, uma aplicação simples e eficiente para o gerenciamento de registros de gravações de caminhões e suas respectivas quantidades de GB (Gigabytes). Este sistema permite que você registre, visualize, busque e exclua dados relacionados aos caminhões de maneira fácil e intuitiva.

## Funcionalidades

- **Cadastro de Caminhões:** Adicione novos caminhões informando a placa e a quantidade de GB.
- **Exclusão de Registros:** Remova registros de caminhões diretamente da tabela.
- **Busca por Placa:** Pesquise rapidamente caminhões por sua placa.
- **Ordenação de Dados:** Organize os dados por diferentes colunas, como número de registro, data, placa e quantidade de GB.
- **Interface Gráfica (GUI):** Interface intuitiva com tkinter para uma experiência de usuário agradável.

## Tecnologias Utilizadas

- **Python:** Linguagem de programação utilizada no desenvolvimento da aplicação.
- **Tkinter:** Biblioteca para criação da interface gráfica do usuário (GUI).
- **Pandas:** Biblioteca para manipulação e análise de dados, utilizado para carregar, manipular e salvar os dados em formato Excel.
- **Regex:** Expressões regulares para validação do formato da placa do caminhão.

## Requisitos

Antes de executar o projeto, você precisa ter o Python instalado em sua máquina. Caso não tenha, baixe e instale o Python [aqui](https://www.python.org/downloads/).

Além disso, você precisará das seguintes bibliotecas:

- `pandas`
- `tkinter` (já incluído na instalação padrão do Python)
- `re` (também incluído por padrão no Python)

Para instalar o pandas, execute:

```bash
pip install pandas
```

## Como Usar

1. **Clone este repositório** em sua máquina:

```bash
git clone https://github.com/seu-usuario/cadastro-de-caminhoes.git
```

2. **Abra o arquivo** `main.py` ou o script que você utilizar para rodar o código e execute o aplicativo:

```bash
python main.py
```

3. **Interaja com a aplicação:** Na interface gráfica, você poderá:

   - Adicionar novos caminhões, preenchendo a placa e a quantidade de GB.
   - Pesquisar caminhões pela placa.
   - Excluir registros de caminhões.
   - Ordenar os dados pela coluna desejada (Número de Registro, Data, Placa do Caminhão e Q. GB).

4. **Os dados são salvos em um arquivo Excel** chamado `dados_caminhoes.xlsx`, que é criado automaticamente. Se o arquivo não existir, ele será gerado ao adicionar o primeiro registro.

## Exemplo de Uso

Após abrir o aplicativo, você verá uma tela com os seguintes campos e opções:

1. **Placa do Caminhão:** Digite a placa no formato **ABC1D23**.
2. **Quantidade de GB:** Informe a quantidade de GB associada ao caminhão.
3. **Adicionar Dados:** Adiciona os dados ao sistema.
4. **Pesquisar por Placa:** Pesquise por uma placa de caminhão.
5. **Excluir Dados:** Exclua registros selecionados da tabela.

A tabela de dados será exibida na parte inferior, onde você poderá visualizar todas as informações registradas. A interface também permite a ordenação dos dados e a exclusão de registros.

## Contribuindo

Este é um projeto de código aberto, e as contribuições são sempre bem-vindas!

Se você deseja contribuir para o desenvolvimento do projeto, siga os seguintes passos:

1. **Fork este repositório**.
2. **Crie uma branch** para suas alterações.
3. **Commit suas alterações**.
4. **Abra um pull request**.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
