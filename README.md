# EcoSmart Home System

## Descrição do Sistema

**(Nota: Todos os dados apresentados neste README.md são fictícios e criados para fins de demonstração acadêmica.)**

O **EcoSmart Home System** é uma solução de automação residencial inovadora, desenvolvida por uma empresa fictícia dedicada à sustentabilidade. Nosso sistema visa otimizar o consumo de energia e água em residências, promovendo um estilo de vida mais consciente e eficiente. Ele foi projetado para **consumidores e pequenas empresas** que buscam reduzir sua pegada ambiental e economizar recursos. O sistema resolve o problema do desperdício e dos altos custos de energia, oferecendo controle inteligente e monitoramento em tempo real. Através de sensores e algoritmos avançados, o EcoSmart Home System ajusta automaticamente o uso de eletrodomésticos, iluminação e sistemas de irrigação, contribuindo para um futuro mais verde.

## Tecnologias Utilizadas

*   **Linguagem:** Python
*   **Framework:** Django (para o backend da plataforma web)
*   **Banco de Dados:** PostgreSQL
*   **Ferramenta Adicional:** Docker (para conteinerização e ambiente de desenvolvimento)

## Como Executar o Projeto

Para executar o EcoSmart Home System localmente, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/empresa-ficticia/EcoSmartHomeSystem.git
    cd EcoSmartHomeSystem
    ```

2.  **Crie e ative um ambiente virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure as variáveis de ambiente:**
    Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis (exemplo):
    ```
    DATABASE_URL=postgresql://usuario:senha@host:porta/nome_do_banco
    SECRET_KEY=sua_chave_secreta_aqui
    DEBUG=True
    ```

5.  **Execute as migrações do banco de dados:**
    ```bash
    python manage.py migrate
    ```

6.  **Inicie o servidor de desenvolvimento:**
    ```bash
    python manage.py runserver
    ```
    O sistema estará acessível em `http://127.0.0.1:8000/`.

## Estrutura de Pastas

A estrutura principal do projeto é organizada da seguinte forma:

*   `src/`: Contém o código-fonte principal da aplicação, incluindo os módulos do framework, modelos, views e templates.
*   `docs/`: Armazena a documentação do projeto, como manuais de usuário, diagramas de arquitetura e especificações técnicas.
*   `tests/`: Inclui todos os testes automatizados para garantir a qualidade e funcionalidade do código.

## Tabela de Funcionalidades Principais

| Funcionalidade              | Descrição                                                               | Status de Desenvolvimento |
| :-------------------------- | :---------------------------------------------------------------------- | :------------------------ |
| Monitoramento de Energia    | Acompanhamento em tempo real do consumo elétrico.                       | Concluído                 |
| Controle de Iluminação      | Agendamento e automação de luzes.                                       | Concluído                 |
| Gestão de Água              | Monitoramento e controle inteligente do uso de água (ex: irrigação).    | Em Desenvolvimento        |
| Relatórios de Consumo       | Geração de relatórios detalhados sobre o uso de recursos.               | Concluído                 |
| Integração com Dispositivos | Compatibilidade com diversos dispositivos inteligentes (IoT).           | Em Desenvolvimento        |

## Link

Visite nosso repositório no GitHub para mais detalhes: [Repositório do EcoSmart Home System](https://github.com/empresa-ficticia/EcoSmartHomeSystem)

---

## Desenvolvedores

*   Gabriel Andrade | RGM 114.073
*   Adelano Mascarenhas | 114.027
*   Guilherme Graces de Oliveira | 114.072
*   Antonella Scanoni | 114.045

---

**Empresa Fictícia:** Inovando o Futuro, Hoje.
**Contato:** contato@empresa-ficticia.com | (XX) XXXX-XXXX