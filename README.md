Execução do MVP - Marketing Simulator

Descrição
O Marketing Simulator é uma plataforma que permite aos profissionais de marketing testar, simular e otimizar suas campanhas de marketing digital, prevendo impactos sem riscos financeiros ou de reputação.

Problemática
Segundo um estudo da CB Insights (2024), estratégias ineficazes de marketing são o 8º maior motivo de falência. Muitas empresas não conseguem avaliar a eficácia de suas campanhas antes de lançá-las, o que pode resultar em grandes perdas. O Marketing Simulator resolve esse problema ao permitir testes antes do investimento real.

Solução
A plataforma oferece uma ferramenta para simular campanhas de marketing, ajustando variáveis como orçamento, público-alvo e canais de distribuição, com foco em otimizar os resultados.

Funcionalidades Principais
Análises de Desempenho: Visualização de métricas como ROI e engajamento.
Gestão de Campanhas: Organize e monitore campanhas.
Simulação em Tempo Real: Teste e ajuste estratégias instantaneamente.
Relatórios Detalhados: Obtenha insights sobre a eficácia das campanhas.
Objetivo
Permitir que profissionais e empresas testem e otimizem campanhas antes de lançá-las no mercado real, evitando falhas financeiras.

Tecnologias Utilizadas
Dart: Linguagem de programação.
Flutter: Framework multiplataforma.

Pré-requisitos
Antes de iniciar a implantação, verifique os seguintes pré-requisitos:

Instalação do Flutter:

Certifique-se de que o Flutter está instalado em sua máquina. Para isso, siga o guia oficial de instalação aqui.
Editor de Código:

Use um editor de código compatível, como Visual Studio Code ou Android Studio.
Dispositivo ou Emulador:

Você precisará de um dispositivo físico ou emulador Android/iOS para rodar o aplicativo.
Passos para Implantação
1. Clone o Repositório
Primeiro, é necessário clonar o repositório do Marketing Simulator para o seu ambiente local:

bash
Copiar código
git clone https://github.com/ezaucastilho27/marketing-simulator.git
cd marketing-simulator
2. Instale as Dependências
Após clonar o repositório, instale as dependências necessárias utilizando o comando abaixo:

bash
Copiar código
flutter pub get
Isso irá baixar todas as bibliotecas e pacotes que o projeto necessita para funcionar corretamente.

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
assets/: Contém recursos de mídia, como imagens e ícones.
test/: Contém testes automatizados para garantir a qualidade do código.
Modelo de Monetização
A solução possui um modelo de monetização baseado em um plano de assinatura:

Visibilidade destacada para prestadores de serviços.
Cupons de desconto para clientes.
A plataforma oferece 3 campanhas gratuitas. Após a 4ª, será cobrada uma percentagem sobre os ganhos.

Próximas Melhorias e Funcionalidades
Expansão de Relatórios: Implementação de mais métricas personalizadas.
Integração com APIs de Redes Sociais: Para análise de dados em tempo real.
Exportação de Relatórios: Permitindo a exportação de resultados das campanhas simuladas.

Colaboradores: Charles Patriarca, Maria Nascimento, Ellen Priscila, Ezaú Castilho
