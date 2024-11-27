Marketing Simulator - Passo a Passo para Execução do MVP


Descrição Geral
O Marketing Simulator é uma plataforma que permite aos usuários testar, simular e analisar campanhas de marketing digital de forma segura e eficiente. A plataforma possibilita que empresas e profissionais de marketing criem e otimizem suas campanhas antes de lançá-las no mercado real. O objetivo é minimizar os riscos financeiros e reputacionais, oferecendo uma maneira controlada de testar diferentes abordagens de marketing.

Problemática
Segundo um estudo realizado pela CB Insights em janeiro de 2024, estratégias ineficazes de marketing são o 8º maior motivo de falência no mundo dos negócios. Muitas empresas enfrentam dificuldades em prever os resultados e o impacto de suas campanhas antes de lançá-las, o que pode gerar investimentos financeiros significativos sem retorno. Além disso, muitas empresas não têm ferramentas acessíveis e intuitivas para testar suas campanhas sem comprometer sua reputação ou recursos.

Solução
O Marketing Simulator resolve essa problemática, oferecendo uma plataforma onde os usuários podem:

Testar Estratégias de Marketing: Simular diferentes abordagens e analisar como elas afetam os resultados.
Analisar Dados de Desempenho: Obter insights detalhados sobre o desempenho das campanhas.
Ajustar Estratégias em Tempo Real: Realizar modificações instantaneamente e observar os resultados.
O objetivo principal é permitir que os usuários otimizem suas estratégias com base em dados concretos, antes de realizar investimentos reais.

Pré-requisitos
Antes de iniciar a implantação do Marketing Simulator, verifique os seguintes pré-requisitos:

Instalar o Flutter
Para instalar o Flutter, siga o guia oficial de instalação aqui.

Nota: Certifique-se de que o Flutter esteja corretamente configurado com o comando:

Copiar código
flutter doctor
Editor de Código
Utilize um editor de código compatível, como:

Visual Studio Code
Android Studio
Dispositivo ou Emulador
Você precisará de um dispositivo físico ou um emulador Android/iOS para rodar o aplicativo.

Passos para Implantação
1. Clone o Repositório
Primeiro, é necessário clonar o repositório do Marketing Simulator para o seu ambiente local:

bash
Copiar código
git clone https://github.com/ezaucastilho27/marketing-simulator.git
cd marketing-simulator
2. Instale as Dependências
Após clonar o repositório, instale as dependências necessárias com o comando abaixo:

bash
Copiar código
flutter pub get
Isso irá baixar todas as bibliotecas e pacotes necessários para o funcionamento correto do projeto.

3. Configure o Ambiente de Desenvolvimento
Caso ainda não tenha configurado o ambiente para dispositivos móveis, siga os seguintes passos:

Android: Instale o Android Studio e crie um emulador, ou conecte um dispositivo físico Android via USB com o modo de desenvolvedor ativado.
iOS: Para rodar no iOS, é necessário ter um MacOS com Xcode instalado.
4. Execute o Projeto
Para rodar o projeto no seu dispositivo ou emulador, use o comando:

bash
Copiar código
flutter run
Isso compilará o código e executará o aplicativo no dispositivo/emulador conectado.

5. Verifique a Execução
Acesse o aplicativo em seu dispositivo ou emulador e verifique se ele está funcionando corretamente. A interface principal permitirá que você crie e simule campanhas de marketing.

Estrutura do Projeto
lib/: Contém o código fonte do aplicativo.
assets/: Contém recursos como imagens e ícones.
test/: Contém testes automatizados para garantir a qualidade do código.
Modelo de Monetização
O Marketing Simulator possui um modelo de monetização com um plano único de assinatura, que oferece benefícios exclusivos, como:

Visibilidade destacada para prestadores de serviços.
Cupons de desconto para clientes.
A plataforma oferece 3 campanhas gratuitas. Após a 4ª campanha, será cobrada uma porcentagem sobre os ganhos obtidos com as simulações.

Próximas Melhorias e Funcionalidades
Expansão de Relatórios: Implementação de mais métricas personalizadas.
Integração com APIs de Redes Sociais: Para análise de dados em tempo real.
Exportação de Relatórios: Permitindo exportar os resultados das campanhas simuladas.


Colaboradores
Maria Nascimento
Charles Patriarca
Ezau Castilho
Ellen Priscila
