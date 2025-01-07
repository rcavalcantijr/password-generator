# Password Generator
Este é um projeto simples de um gerador de senhas desenvolvido em Python, utilizando a biblioteca PySimpleGUI para criar uma interface gráfica

## Funcionalidades
- Gera senhas aleatórias com caracteres alfanuméricos e símbolos especiais.
- Permite ao usuário especificar o número de caracteres da senha.
- Salva as senhas geradas junto com o site/software e e-mail do usuário em um arquivo de texto.

## Tecnologias Utilizadas
- Python 3
- [PySimpleGUI](https://pysimplegui.readthedocs.io/en/latest/) (para a interface gráfica)

## Requisitos
Certifique-se de ter o Python instalado em sua máquina. Instale também as dependências do projeto executando:

```bash
pip install PySimpleGUI
```

## Como Usar
1. Clone este repositório ou faça o download dos arquivos.

```bash
git clone <URL_DO_REPOSITORIO>
```

2. Navegue até o diretório do projeto.

```bash
cd <NOME_DO_DIRETORIO>
```

3. Execute o script principal:

```bash
python <nome_do_arquivo>.py
```

4. Preencha os campos necessários:

    - **Site/Software**: Nome do site ou software para o qual a senha será gerada.
   - **E-mail**: E-mail ou nome de usuário associado.
   - **Caracteres**: Número de caracteres desejados para a senha.

6. Clique no botão "Gerar Senha". A senha será exibida na interface e salva em um arquivo de texto chamado `senhas_txt` no mesmo diretório do script.

## Estrutura do Projeto
- **`<nome_do_arquivo>.py`**: Código principal do gerador de senhas.
- **`senhas_txt`**: Arquivo gerado automaticamente para salvar as senhas criadas (caso não exista, será criado).

## Observações
- O arquivo `senhas_txt` é salvo no mesmo diretório do script e contém todas as senhas geradas com as informações associadas (site/software, e-mail).
- Certifique-se de manter este arquivo em local seguro para evitar o acesso não autorizado.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença
Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais informações.
