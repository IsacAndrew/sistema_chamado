# Sistema-Chamado

Sistema-Chamado é um projeto de help desk que estou desenvolvendo para praticar HTML e CSS na construção de uma interface com diferentes áreas: login, início, chat e chamados. Neste momento, meu foco está na estrutura visual e na organização das telas; o backend e os fluxos do sistema ainda serão desenvolvidos em etapas futuras.

A versão da branch `main` é a versão principal do projeto e está executando corretamente. Ela reúne as telas e a base visual em desenvolvimento. Na branch `area-testes`, experimento alternativas de layout, incluindo cards vazios com bordas destacadas para facilitar a identificação e o ajuste dos elementos na interface.

## O que estou praticando

- Estruturação de páginas e formulários com HTML.
- Criação e organização de estilos com CSS.
- Construção de uma interface com áreas distintas para um sistema de help desk.
- Uso de branches para manter uma versão principal e testar mudanças visuais.
- Prática contínua de Git para registrar e organizar o desenvolvimento.

## Tecnologias

- HTML
- CSS
- Python
- Flask — estrutura inicial para servir a aplicação

## Executar localmente

É necessário ter Python 3 e `pip` instalados.

```bash
git clone https://github.com/IsacAndrew/Sistema-Chamado.git
cd Sistema-Chamado
python -m venv .venv
```

Ative o ambiente virtual e instale as dependências:

```bash
# Windows
.venv\Scripts\activate

# Linux ou macOS
source .venv/bin/activate

pip install -r requirements.txt
```

Inicie a aplicação:

```bash
python app.py
```

Acesse `http://127.0.0.1:5000` no navegador.

## Estado atual

O projeto está em desenvolvimento. A prioridade atual é construir e organizar a interface; as funcionalidades completas de chamados, chat e persistência de dados serão trabalhadas posteriormente, conforme avanço nos estudos de Python e backend.
