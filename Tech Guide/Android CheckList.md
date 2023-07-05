# Android
## Nivel 1

- [ ] **Kotlin - Fundamentos**:
   <details>
      <ul>
      <li>Kotlin é uma linguagem de programação multiplataforma, orientada a objetos, funcional e estaticamente tipada. Ela compila para a máquina virtual Java e também pode ser traduzida para a linguagem JavaScript e compilada para código nativo (via LLVM). É a linguagem oficial do sistema Android da Google.</li>
      <li>Entender a sua sintaxe</li>
      <li>Conhecer os tipos primitivos</li>
      <li>Declarar e usar variáveis e constantes</li>
      <li>Usar estruturas condicionais (if, else)</li>
      <li>Usar estruturas de repetição e laços (while, for)</li>
      <li>Usar funções, passando parâmetros e argumentos</li>
      <li>Implementando métodos e reutilizando eles</li>
      <li>Null Safety (Elimine o perigo de referências nulas)</li>
      <li>Exceptions e Throwables</li>
      <li>Convenções de código</li>
      <li>Manipular Coleções, arrays e listas</li>
      <li>Recursos do Paradigma funcional</li>
      <li>Orientação a Objetos com Kotlin (Properties, Data class, Companion Objects, Delegation)</li>
      </ul>
   </details>
   
- [ ] **Android - Fundamentos**:
   <details>
      <ul>
      <li>Conhecer Kotlin, Java ou C++ que são as linguagens para desenvolver Apps Android.</li>
      <li>Entender como o SDK do Android empacota o código e recursos do App em um APK (Android Package - Pacote Android) para rodar no SO do Android</li>
      <li>Saber os componentes de entrada de um App - Activity, Service, Broadcast Receiver e Content Provider</li>
      <li>Compreender os ciclos de vida de componentes do Android e como funcionam - O ciclo de vida de uma Activity</li>
      <li>Ativar componentes de entrada do App com Intents</li>
      <li>Conhecer o arquivo de manifesto e os principais itens de configuração</li>
      <li>Entender quais são os recursos de um projeto Android - código fonte, recursos estáticos, drawables, layout, mipmap, values etc</li>
      <li>Criar um projeto Android com o Android Studio e rodar em um dispositivo físico ou virtual</li>
      <li>Conhecer bibliotecas do jetpack para garantir a compatibilidade entre as versões do Android</li>
      </ul>
   </details>
   
- [ ] **Conceitos de Orientação a Objetos**:
   <details>
      <ul>
      <li>A Programação Orientada a Objetos é um paradigma de programação de software baseado na composição e interação entre diversas unidades chamadas de &#39;objetos&#39; e as classes, que contêm uma identidade, propriedades e métodos). Ela é baseada em quatro componentes da programação: abstração digital, encapsulamento, herança e polimorfismo.</li>
      <li>Como funcionam objetos</li>
      <li>Criar e utilizar construtores</li>
      <li>O que são classes</li>
      <li>Criar e utilizar métodos</li>
      <li>Como funciona encapsulamento</li>
      <li>O que é herança</li>
      <li>O que é polimorfismo</li>
      <li>Como funcionam interfaces</li>
      <li>O que são abstrações</li>
      </ul>
   </details>
- [ ] **Android - Sistema de View**:
   <details>
      <ul>
      <li>A classe View representa o bloco básico de construção dos componentes de interface do usuário em Android.</li>
      <li>Conhecer a referência View e ViewGroup para definir um Layout</li>
      <li>Saber as principais ViewGroups para construir layouts - LinearLayout, RelativeLayout, FrameLayout e ConstraintLayout</li>
      <li>Usar o editor visual de Layout para personalizar a tela, ou então, utilizar o arquivo XML para a edição</li>
      <li>Conhecer o Preview do editor visual e usá-lo para preparar as telas e componentes do App</li>
      <li>Utilizar as Views do SDK do Android - TextView, Button, EditText, CheckBox, DatePicker etc</li>
      <li>Criar Views personalizadas para atender demandas específicas</li>
      <li>Personalizar as Views com propriedades do Android ou da própria View - Ajustes de altura, largura, visibilidade, espaçamento</li>
      <li>Implementar Layouts de conteúdos dinâmico com adaptadores - AdapterView e RecyclerView</li>
      <li>Integrar código de negócio com o layout da tela - Chamar e manipular as Views com o View Binding</li>
      <li>Reagir a eventos das Views a partir de listeners como cliques, cliques longos, rolagem, arrastar e soltar</li>
      </ul>
   </details>
- [ ] **Android - Fragments**:
   <details>
      <ul>
      <li>Um Fragment representa o comportamento ou uma parte da interface do usuário em uma Activity hospedeira. É possível combinar vários fragmentos em uma única Activity para criar uma IU de vários painéis e reutilizar um fragmento em diversas atividades. Você pode imaginar um fragment como uma seção modular de uma Activity, que tem o próprio ciclo de vida, recebe os próprios eventos de entrada e que pode ser adicionada ou removida durante a execução da Activity.</li>
      <li>Entender o que é um Fragment</li>
      <li>Como usar e reutilizar Fragments na mesma Activity</li>
      <li>Entender os motivos para utilizar Fragments em projetos Android</li>
      <li>Implementar layouts com múltiplos painéis</li>
      <li>Migrar projetos Android que utilizam apenas Activities para utilizar fragments</li>
      <li>Lidar com transações do gerenciador de fragments</li>
      </ul>
   </details>
- [ ] **Android - Navegação no App**:
   <details>
      <ul>
      <li>A navegação de telas em Apps é fundamental para a experiência de uso de Apps Android. Para isso é essencial conhecer os princípios de navegação do Android.</li>
      <li>Aprender o que é a biblioteca Navigation e como é possível implementá-la, seja para o sistema de Views ou para o Jetpack Compose</li>
      <li>Integrar a navegação com componentes do App, seja em navegação de abas, ou na visualização de componentes visuais dependendo da tela</li>
      <li>Saber o que é uma task de back stack do Android</li>
      <li>Conhecer os App links - Deep Link, Web Links e Android App Links</li>
      </ul>
   </details>
- [ ] **Jetpack Compose - Fundamentos**:
   <details>
      <ul>
      <li>O Jetpack Compose é uma ferramenta que trás a proposta de criar interfaces nativas Android com menos código, mais rápido e deixa seus apps mais bonitos, ele faz isso através da abordagem declarativa.</li>
      <li>Criar um app Android do zero utilizando o Jetpack Compose</li>
      <li>Construção de Layouts apartir de composables</li>
      <li>Pré-visualizações de Composables</li>
      <li>Gerenciamento de estados, eventos, composição e recomposição</li>
      <li>Configurar o Compose em um projeto já existente e aplicar a interoperabilidade</li>
      <li>Trabalhar com formulários</li>
      <li>Entender a diferença do XML para o Compose</li>
      <li>Manter estados utilizando o padrão MVVM com ViewModel e StateFlow, entendendo o ciclo de vida</li>
      </ul>
   </details>
- [ ] **Android - Persistência**:
   <details>
      <ul>
      <li>O conceito de &quot;persistência de dados&quot; refere-se a garantir que as informações inseridas na aplicação serão armazenadas em um meio em que possam ser recuperadas de forma consistente. Ou seja, são registros permanentes e que não são perdidos quando há o encerramento da sessão.</li>
      <li>No Android podemos armazenar de maneira persistente arquivos específicos ou para o App ou compartilhado, informações de tipo primitivo com preferências e dados estruturados com banco de dados.</li>
      </ul>
   </details>
- [ ] **Android - Gradle**:
   <details>
      <ul>
      <li>O Gradle e o plug-in do Android para Gradle(AGP) oferecem uma maneira flexível de compilar, criar, gerenciar e empacotar seu app ou biblioteca Android.</li>
      <li>O que é uma build tool</li>
      <li>Aprender a estrutura de um projeto Android como um projeto multi módulo do Gradle</li>
      <li>Para que serve o Gradle e como usá-lo</li>
      <li>O que são dependências e como utilizá-las</li>
      </ul>
   </details>
- [ ] **Android - Carregamento de imagens**:
   <details>
      <ul>
      <li>As imagens vem em tamanhos e formas diferentes. Na maioria dos casos, elas são maiores do que o necessário para a Interface de usuário (UI) de um app. Dado que estamos trabalhando com memória limitada, no Android é usada uma técnica de decodificação de bitmaps, para evitar todo o trabalho de utilizar isso, temos diversas bibliotecas que facilitam esse processo.</li>
      <li>O que é Bitmap</li>
      <li>Conhecer as bibliotecas de carregamento de imagens (Glide, Picasso, Coil, entre oturas) e usá-las</li>
      <li>Vantagens e desvantagens das bibliotecas de carregamento de imagens</li>
      </ul>
   </details>
   
## Nivel 2

- [ ] **Android - Permissões**:
   <details>
      <ul>
      <li>As permissões do app ajudam a apoiar a privacidade do usuário protegendo dados restritos, como estados do sistema e os dados de contatos dos usuários, há também as ações restritas, como a conexão a um dispositivo pareado e a gravação de áudio ou uso de câmera.</li>
      <li>Entender o que são permissões</li>
      <li>Aprender sobre os diferentes tipos de permissões</li>
      <li>Permissões especiais</li>
      <li>Práticas recomendadas</li>
      </ul>
   </details>
- [ ] **Kotlin - Assíncrono**:
   <details>
      <ul>
      <li>Na programação assíncrona as funções não são executadas em ordem. Com o assincronismo, podemos interromper do código para conseguirmos alguma outra informação necessária para a continuar a execução. Isso significa que o código espera por uma outra parte do código e, enquanto espera, executa as demais partes.</li>
      <li>Aprender as possibilidades para rodar o código de maneira assíncrona no Android</li>
      <li>Conhecer o pacote java.concurrent e as suas soluções</li>
      <li>Utilizar Coroutines como uma solução de código assíncrono no Kotlin</li>
      <li>Entender e usar estruturas reativas como LiveData, Flow, StateFlow, RX, etc</li>
      </ul>
   </details>
- [ ] **Kotlin - Comunicação com APIs**:
   <details>
      <ul>
      <li>Uma API é uma interface que desenvolvedores de software utilizam para programar a interação com componentes ou recursos de software fora de seu próprio código. Uma definição ainda mais simples é que uma API é a parte de um componente de software que é acessível a outros componentes.</li>
      <li>Realizar requisições HTTP para se comunicar com serviços online, como REST API é fundamental na maioria dos Apps Android. Sendo assim, é importante conhecer as principais ferramentas e técnicas necessárias para esse tipo de funcionalidade.</li>
      <li>Conhecer bibliotecas famosas no mundo Android para realizar requisições - Retrofit, Ktor ou Volley</li>
      <li>Configurar as requisições para executararem de maneira assíncrona</li>
      <li>Converter objetos para JSON e vice-versa</li>
      </ul>
   </details>
- [ ] **Android - Recursos do sistema**:
   <details>
      <ul>
      <li>Os smartphones que estão sob a plataforma Android, na sua grande maioria possuem diversos recursos específicos do sistema, tais como câmeras, sensores, gps, entre outros.</li>
      <li>Aprenda quais são e como utilizar esses recursos</li>
      </ul>
   </details>
- [ ] **Kotlin - Injeção de Dependências**:
   <details>
      <ul>
      <li>Injeção de Dependências é um padrão de projeto no qual uma classe solicita dependências de fontes externas ao invés de criá-las.</li>
      <li>Ao escrever códigos em projetos Android, é muito que uma funcionalidade utilize códigos de bibliotecas, como o Room para salvar dados ou o Retrofit para fazer requisições para REST API. Essas bibliteocas são conhecidas como dependências dos nossos códigos, justamente pela necessidade para realizar a ação esperada. Usar essas bibliotecas com facilidade em qualquer parte do app pode ter os seus desafios, como oferecer instâncias únicas e realizar toda a configuração necessária para o funcionamento correto. Para isso, utilizamos ferramentas de injeção de dependência que facilitam o nosso trabalho.</li>
      <li>Aprender a usar a técnica de injeção de dependências e alguma das ferramentas comuns no Android para tal - Hilt, Dagger ou Koin</li>
      </ul>
   </details>
- [ ] **Android - Testes**:
   <details>
      <ul>
      <li>O teste de software é o processo de avaliação e verificação de que um software realmente faz o que deveria fazer. Os benefícios dos testes incluem a prevenção de bugs, a redução dos custos de desenvolvimento e a melhoria do desempenho.</li>
      <li>Usar testes unitários</li>
      <li>Usar testes de integração</li>
      <li>Usar testes instrumentados</li>
      <li>Usar mocks para facilitar a implementação de testes com dependências</li>
      <li>Implementar testes com ferramentas de Injeção de Dependências como o Hilt</li>
      </ul>
   </details>
## Nivel 3
- [ ] **Android - Arquitetura**:
   <details>
      <ul>
      <li>O guia de arquitetura Android aborda práticas e a arquitetura recomendada para a criação de apps robustos com alta qualidade de produção. Organizar sua base de código em partes contidas e acopladas com flexibilidade (Modularização).</li>
      <li>Aprender o que é e para que serve a arquitetura MVVM (Model-View-ViewModel)</li>
      <li>Camadas de IU, dados e domínios</li>
      <li>Fluxo de dados dentro do app</li>
      <li>Como utilizar o ViewModel</li>
      <li>Recomendações da arquitetura, padrão repositório, offline-first</li>
      <li>Gerenciamento de estado</li>
      <li>Injeção de dependências</li>
      <li>Melhorar a experiência dos usuários do app com o ViewModel</li>
      <li>Aprender o que é modularização</li>
      <li>Benefícios da modularização</li>
      </ul>
   </details>
- [ ] **Android - Critérios de qualidade do App**:
   <details>
      <ul>
      <li>Ao escrever um App Android, existe uma série de requisitos para garantir uma qualidade esperada, como por exemplo, a compatibilidade do App com a navegação esperada pelo sistema Android, ou então, pelos gestos, etc.</li>
      <li>Os requisitos são classificados como - Experiência visual, Funcionalidade, Desempenho e estabilidade, Privacidade e segurança, Google Play e Procedimento de teste</li>
      <li>Cumprir todos os requisitos, ou quase todos, significa que o App possui uma maior qualidade para os usuários.</li>
      </ul>
   </details>
- [ ] **Android - Entrega e integração contínuas (CI/CD)**:
   <details>
      <ul>
      <li>CI/CD é a abreviação de Continuous Integration/Continuous Delivery, traduzindo para o português &quot;entrega e integração contínuas&quot;. Trata-se de uma prática de desenvolvimento de software que visa tornar a integração de código mais eficiente por meio de builds e testes automatizados.</li>
      <li>Ao implementar novas funcionalidades do App, precisamos garantir que todas as entregas irão funcionar corretamente. Para isso, podemos utilizar técnicas de integração e entrega contínua, dessa forma, agilizamos a evolução do App e tentamos garantir os comportamentos esperados ao mesmo tempo.</li>
      <li>Conhecer alguma das ferramentas para fazer a entrega contínua, como Firebase Test Lab, Jenkins, GitHub Actions, etc</li>
      </ul>
   </details>
- [ ] **Android - Otimização do app**:
   <details>
      <ul>
      <li>Ao gerar um App, existem alguns detalhes de otimização para torná-lo rápido, menor e otimizado, como por exemplo, a remoção de código desnecessário, a ofuscação que reduz o nome dos códigos e a otimização que aplica estratégias mais agressivas para reduzir mais ainda o app.</li>
      <li>Aprender a ativar cada otimização no plugin do Android para o Gradle</li>
      <li>Utilizar o proguard para realizar uma otimização mais agressiva</li>
      <li>Ativar o multidex para que o app seja capaz de obter mais de 64000 métodos e conseguir utilizar as técnicas de otimização</li>
      <li>Conhecer e utilizar ferramentas auxiliarem para aumentar o desempenho do App</li>
      </ul>
   </details>
- [ ] **Java - Fundamentos**:
   <details>
      <ul>
      <li>Java é uma linguagem de programação amplamente usada para codificar aplicações Web. Java é uma linguagem multiplataforma, orientada a objetos e centrada em rede que pode ser usada como uma plataforma em si. É uma linguagem de programação rápida, segura e confiável para codificar tudo, desde aplicações móveis e software empresarial até aplicações de big data e tecnologias do servidor.</li>
      <li>Conhecer os tipos primitivos</li>
      <li>Declarar variáveis, considerando os diferentes tipos</li>
      <li>Usar estruturas condicionais (&#39;if&#39;, &#39;else&#39;)</li>
      <li>Conhecer os operadores de atribuição e comparação</li>
      <li>Usar estruturas de repetição e laços (&#39;while&#39;, &#39;for&#39;)</li>
      <li>Usar funções, passando parâmetros e argumentos</li>
      <li>Manipular métodos</li>
      <li>Manipular arrays e listas</li>
      <li>Obter dados de uma API</li>
      <li>Fazer chamadas assíncronas &#39;Future&#39;, etc</li>
      <li>Criar construtores</li>
      </ul>
   </details>
- [ ] **Android - Depuração**:
   <details>
      <ul>
      <li>Durante o desenvolvimento de um app, é bastante comum a presença de bugs inesperados, como também, a falta de compreensão do motivo do bug. Para agilizar a análise e investigação de problemas ou comportamentos inesperados no app, precisamos aprender a depurar ou debuggar um app Android.</li>
      <li>Saber como executar um app em depuração no Android Studio</li>
      <li>Aprender a ativar a depuração em dispositivos físicos</li>
      <li>Utilizar Logs para identificar eventos</li>
      <li>Analisar stack track</li>
      <li>Inspecionar o Layout, recursos do sistema como processador, memória e rede</li>
      <li>Depurar o banco de dados do app e arquivos APKs pré-compilados</li>
      <li>Analisar o build com o analizador de APK</li>
      </ul>
   </details>
   
## Habilidade Auxiliar: Infraestrutura e boas práticas 

- [ ] **Git e GitHub - Fundamentos**:
   <details>
      <ul>
      <li>Git é um sistema de controle de versão distribuído gratuito e de código aberto projetado para lidar com tudo, desde projetos pequenos a muito grandes com velocidade e eficiência.</li>
      <li>GitHub é um serviço de hospedagem para desenvolvimento de software e controle de versão usando Git.</li>
      <li>Criar um repositório</li>
      <li>Clonar um repositório</li>
      <li>Fazer commit, push e pull de e para o repositório</li>
      <li>Reverter um commit</li>
      <li>Criar branches e pul requests</li>
      <li>Lidar com merge e conflitos</li>
      </ul>
   </details>
- [ ] **HTTP - Fundamentos**:
   <details>
      <ul>
      <li>HTTP significa Hyper Text Transfer Protocol. A comunicação entre computadores cliente e servidores web é feita enviando solicitações HTTP e recebendo respostas HTTP.</li>
      <li>Entender a diferença dos verbos HTTP</li>
      <li>Testar os requests e ver os status codes no navegador</li>
      <li>Saber fazer uma requisição HTTP na linha de comando com WGET</li>
      <li>Baixar uma imagem com WGET</li>
      <li>Fazer um post</li>
      </ul>
   </details>
- [ ] **JSON**:
   <details>
      <ul>
      <li>JSON significa JavaScript Object Notation (notação de objeto JavaScript). É um formato de texto para armazenar e transmitir dados.</li>
      <li>Criar um objeto</li>
      <li>Transformar um objeto em uma string</li>
      <li>Transformar uma string em objeto</li>
      <li>Manipular um objeto</li>
      </ul>
   </details>
- [ ] **Design Patterns**:
   <details>
      <ul>
      <li>Na engenharia de software, um &quot;padrão de projeto&quot; (Design Pattern em inglês) é uma solução geral e reutilizável para um problema que ocorre normalmente dentro de um determinado contexto de projeto de software.</li>
      <li>Conhecer e aplicar os principais Design Patterns</li>
      </ul>
   </details>
- [ ] **Linha de comando - Fundamentos**:
   <details>
      <ul>
      <li>CLI é um programa de linha de comando que aceita entradas de texto para executar funções do sistema operacional.</li>
      <li>Conhecer os principais comandos</li>
      </ul>
   </details>
- [ ] **Cloud - Fundamentos**:
   <details>
      <ul>
      <li>Cloud, ou computação em nuvem é a distribuição de serviços de computação pela Internet usando um modelo de preço pago conforme o uso. Uma nuvem é composta de vários recursos de computação, que abrangem desde os próprios computadores (ou instâncias, na terminologia de nuvem) até redes, armazenamento, bancos de dados e o que estiver em torno deles. Ou seja, tudo o que normalmente é necessário para montar o equivalente a uma sala de servidores, ou mesmo um data center completo, estará pronto para ser utilizado, configurado e executado.</li>
      <li>Conhecer a diferença entre IaaS, PaaS e SaaS</li>
      <li>Conhecer os maiores provedores de cloud</li>
      <li>Especializar-se em algum provedor</li>
      </ul>
   </details>
- [ ] **SOLID**:
   <details>
      <ul>
      <li>O Solid possui cinco princípios considerados como boas práticas no desenvolvimento de software que ajudam os programadores a escrever os códigos mais limpos, separando as responsabilidades, diminuindo acoplamentos, facilitando na refatoração e estimulando o reaproveitamento do código.</li>
      </ul>
   </details>
- [ ] **Clean Architecture**:
   <details>
      <ul>
      <li>A Clean Architecture (Arquitetura Limpa) é uma forma de desenvolver software, de tal forma que apenas olhando para o código fonte de um programa, você deve ser capaz de dizer o que o programa faz.</li>
      </ul>
   </details>
- [ ] **Firebase**:
   <details>
      <ul>
      <li>O Firebase é uma plataforma de desenvolvimento de aplicativos Backend-as-a-Service (BaaS) que fornece serviços de backend hospedados, tais como banco de dados em tempo real, armazenamento em nuvem, autenticação, relatórios de falhas, aprendizado de máquina, configuração remota e hospedagem para seus arquivos estáticos.</li>
      <li>Entender como Instalar o Firebase</li>
      <li>Conhecer a documentação do Firebase</li>
      <li>Conhecer as ferramentas do Firebase disponíveis</li>
      </ul>
   </details>
   
## Habilidade Auxiliar: UX & Design 

- [ ] **Material Design**:
   <details>
      <ul>
      <li>Material Design é um sistema de design de código aberto do Google, onde ele te passa componentes com determinados padrões de uso e certa personalização para seus apps.</li>
      <li>Fundações de experiência de usuário</li>
      <li>Personalizar seus componentes</li>
      <li>Layouts adaptativos</li>
      </ul>
   </details>
- [ ] **Design Systems**:
   <details>
      <ul>
      <li>Um Design Systems (sistema de design) é uma coleção de componentes reutilizáveis, guiados por padrões claros, que podem ser colocados juntos para construir aplicações.</li>
      <li>Criar e manter bibliotecas que serão consumidas e usadas como padrão para a construção de um projeto</li>
      </ul>
   </details>
- [ ] **Sistemas de cores**:
   <details>
      <ul>
      <li>Definir uma paleta de cores que faça sentido para determinada interface</li>
      </ul>
   </details>
- [ ] **Como usar fontes**:
   <details>
      <ul>
      <li>Escolher a fonte mais adequada para determinado projeto</li>
      </ul>
   </details>
- [ ] **Design Responsivo**:
   <details>
      <ul>
      <li>Ajustar suas páginas para o tamanho da tela do usuário</li>
      <li>Media queries</li>
      <li>Conhecer o conceito de Mobile first</li>
      </ul>
   </details>
- [ ] **Android - Acessibilidade**:
   <details>
      <ul>
      <li>Acessibilidade Digital é a eliminação de barreiras na Web. O conceito pressupõe que os sites e aplicativos sejam projetados de modo que todas as pessoas possam perceber, entender, navegar e interagir de maneira efetiva com as páginas, incluindo pessoas com necessidades de acessibilidades, como pessoas com problemas de visão, daltonismo, dificuldades auditivas, comprometimento motor, deficiência cognitivas e muitos outros tipos de deficiência.</li>
      <li>Aumentar a visibilidade do texto</li>
      <li>Usar controles grandes e simples</li>
      <li>Descrever cada elemento de IU</li>
      </ul>
   </details>
- [ ] **Figma - Fundamentos**:
   <details>
      <ul>
      <li>Figma é uma aplicação web colaborativa para design de interfaces. O conjunto de recursos do Figma se concentra na interface do usuário e no design da experiência do usuário, com ênfase na colaboração em tempo real, utilizando uma variedade de editores de gráficos vetoriais e ferramentas de prototipagem.</li>
      <li>Criar layouts de páginas e componentes</li>
      </ul>
   </details>
