# CalmaMente

## Descrição Geral do Projeto

O CalmaMente é uma aplicação web intuitiva e acolhedora, desenvolvida com o propósito de oferecer suporte diário e ferramentas de bem-estar mental. Projetado para ser acessível e fácil de usar, o site visa auxiliar indivíduos, especialmente aqueles com déficit cognitivo e intelectual, bem como pessoas com transtornos de personalidade, a gerenciar suas rotinas, monitorar seu humor e encontrar momentos de calma. A interface amigável, combinada com funcionalidades práticas, cria um ambiente digital seguro e de apoio para a promoção da saúde mental e autonomia pessoal.

## Funcionalidades Principais

O CalmaMente oferece um conjunto de funcionalidades cuidadosamente elaboradas para proporcionar uma experiência de usuário enriquecedora e de suporte:

### Sons Relaxantes

Esta funcionalidade permite ao usuário acessar uma biblioteca de sons ambiente projetados para promover o relaxamento e a tranquilidade. Os sons disponíveis incluem:

*   **Chuva:** Som suave e contínuo de chuva, ideal para meditação ou para abafar ruídos externos.
*   **Floresta:** Sons naturais de uma floresta, como o canto dos pássaros e o farfalhar das folhas, criando um ambiente sereno.
*   **Ondas:** O ritmo calmante das ondas do mar, que pode ajudar na concentração e na redução do estresse.

**Interação do Usuário:** O usuário pode ativar e desativar cada som individualmente, controlando o ambiente sonoro de acordo com suas preferências e necessidades. A interface é simples e direta, com botões claros para cada opção de som.

### Rotina Diária

A seção de Rotina Diária é uma ferramenta essencial para a organização e o gerenciamento de tarefas. Ela permite que o usuário crie e acompanhe uma lista de atividades a serem realizadas ao longo do dia.

**Interação do Usuário:** O usuário pode adicionar novas tarefas à lista, marcar tarefas como concluídas e remover tarefas que não são mais necessárias. Esta funcionalidade visa promover a autonomia e a sensação de realização, auxiliando na estruturação do dia a dia.

### Interface Amigável e Apoio Emocional

O design do CalmaMente foi pensado para ser o mais intuitivo e acolhedor possível. A interface utiliza uma combinação de elementos visuais e textuais para criar um ambiente de suporte:

*   **Imagens e Ícones:** Elementos visuais são empregados para facilitar a compreensão e a navegação, tornando a experiência mais agradável e menos dependente de texto complexo.
*   **Textos de Apoio:** Mensagens e descrições são formuladas de maneira clara, positiva e encorajadora, reforçando o propósito de bem-estar do aplicativo.
*   **Ambiente Calmo e Acolhedor:** A paleta de cores e o layout geral contribuem para uma atmosfera de calma, reduzindo estímulos excessivos e promovendo um senso de segurança.

**Interação do Usuário:** A navegação é simplificada, com um menu de fácil acesso que permite ao usuário transitar entre as diferentes seções do site sem dificuldades.

### Área de Cadastro e Personalização

O CalmaMente inclui uma área de cadastro que permite ao usuário personalizar sua experiência e garantir que o aplicativo atenda às suas necessidades individuais.

**Interação do Usuário:** No cadastro, o usuário pode inserir seu nome e informações de um contato de apoio. Esta funcionalidade é crucial para a personalização do aplicativo e para a ativação da função SOS, que permite ligar rapidamente para um contato de emergência em momentos de necessidade. Os dados são armazenados localmente para garantir a privacidade e a acessibilidade imediata.

### Integração com Recursos Visuais

Além das funcionalidades interativas, o CalmaMente integra recursos visuais que complementam a experiência do usuário, criando um ambiente digital que é visualmente agradável e funcional.

**Interação do Usuário:** A presença de uma logo e a utilização consistente de elementos visuais em todo o site reforçam a identidade do CalmaMente e contribuem para a criação de um espaço digital que é percebido como um refúgio de calma e apoio. Embora não haja uma interação direta com esses recursos visuais no sentido de modificá-los, eles são fundamentais para a experiência geral do usuário e para o cumprimento do objetivo de criar um ambiente acolhedor.

## Tecnologias Utilizadas

O projeto CalmaMente foi desenvolvido utilizando as seguintes tecnologias web padrão, garantindo compatibilidade e acessibilidade:

*   **HTML5:** Utilizado para estruturar o conteúdo e definir a semântica das páginas web.
*   **CSS3:** Responsável pela estilização e apresentação visual do site, incluindo cores, fontes e layout.
*   **JavaScript:** Implementa a lógica interativa do front-end, gerenciando as funcionalidades dinâmicas como os sons relaxantes, a rotina diária e o monitoramento de humor.
*   **Bootstrap 5:** Framework de front-end utilizado para o desenvolvimento responsivo e para a estilização de componentes, garantindo que o site se adapte a diferentes tamanhos de tela e dispositivos.
*   **Font Awesome:** Biblioteca de ícones que enriquece a interface visual, tornando-a mais intuitiva e agradável.
*   **LocalStorage (Web Storage API):** Utilizado para o armazenamento de dados do usuário diretamente no navegador, como nome, contato de apoio, tarefas da rotina e histórico de humor. Esta abordagem dispensa a necessidade de um back-end tradicional com banco de dados, simplificando a arquitetura do projeto e garantindo a privacidade dos dados do usuário.

## Como Rodar o Projeto Localmente

Para executar o projeto CalmaMente em seu ambiente local, siga os passos abaixo:

1.  **Clone o Repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    ```
2.  **Navegue até o Diretório do Projeto:**
    ```bash
    cd CalmaMente
    ```
3.  **Abra os Arquivos HTML:**
    Como o projeto é uma aplicação front-end pura, você pode simplesmente abrir os arquivos HTML diretamente no seu navegador web. Não é necessário um servidor web para a maioria das funcionalidades, pois os dados são armazenados no `localStorage` do navegador.
    
    *   Abra `index.html` para a página inicial.
    *   Abra `cadastro.html` para a página de cadastro (se for a primeira vez que você está acessando o site, ele será redirecionado automaticamente para esta página).

    Alternativamente, para uma experiência mais próxima de um ambiente de produção (especialmente se você tiver problemas com caminhos de arquivos ou recursos locais), você pode usar uma extensão de servidor local simples para o seu navegador (como o "Live Server" para VS Code) ou um servidor HTTP básico do Python:

    ```bash
    # No diretório raiz do projeto
    python -m http.server 8000
    ```
    Em seguida, acesse `http://localhost:8000` no seu navegador.


## Contato e Autor

Este projeto foi desenvolvido por [Seu Nome/Nome da Equipe].

Para dúvidas, sugestões ou colaborações, por favor, entre em contato através de:

*   **E-mail:** [kauany.violin@gmail.com]
*   **GitHub:** [Seu perfil do GitHub ou link do repositório]



