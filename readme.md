 App de Cursos

## Visão Geral

Aplicativo móvel desenvolvido com React Native e Expo, projetado para oferecer uma experiência intuitiva e envolvente no acesso a diversos cursos.

O aplicativo utiliza React Navigation para gerenciar a navegação entre as diferentes telas. A estrutura de pastas é organizada em:

* **screens:** Contém as telas principais do aplicativo, como a tela inicial (Home), tela de login, tela de detalhes do curso (Detail), etc.
* **components:** Contém componentes reutilizáveis que são utilizados em várias telas.
* **navigation:** Contém a configuração da navegação do aplicativo (como `AppNavigation.js` que você compartilhou).
* **firebaseConfig.js:** Contém a configuração para conectar com o Firebase.

## Configuração do Ambiente (.env)

O aplicativo utiliza variáveis de ambiente para configurar o acesso ao Firebase. Abaixo está um exemplo do arquivo `.env` que você deve criar na raiz do seu projeto:

**Importante:** Substitua os valores de `SUA_API_KEY`, `SEU_AUTH_DOMAIN`, etc., pelas credenciais do seu projeto Firebase. Mantenha este arquivo seguro e não o versionamento no seu sistema de controle de versão (adicione-o ao `.gitignore`).

## Como Iniciar o Projeto com Expo

Para executar o projeto no seu ambiente de desenvolvimento, siga estes passos:

1.  **Certifique-se de ter o Node.js e o npm (ou yarn) instalados na sua máquina.** Você pode verificar as versões com os seguintes comandos no terminal:
    ```bash
    node -v
    npm -v
    # ou
    yarn --version
    ```
    Se não os tiver instalados, você pode baixá-los em [https://nodejs.org/](https://nodejs.org/).

2.  **Instale o Expo CLI (se ainda não estiver instalado).** O Expo CLI é uma ferramenta de linha de comando que ajuda a desenvolver, construir e fazer deploy de aplicativos universais React Native.
    ```bash
    npm install -g expo-cli
    # ou
    yarn global add expo-cli
    ```

3.  **Clone o repositório do projeto.**
    ```bash
    git clone git@github.com:IAbrahanArley/appCurso.git
    cd appCurso
    ```

4.  **Instale as dependências do projeto.** Navegue até a raiz do seu projeto no terminal e execute:
    ```bash
    npm install
    # ou
    yarn install
    ```
    Este comando irá instalar todas as bibliotecas e dependências listadas no arquivo `package.json`, incluindo o React Native, Expo, React Navigation, Firebase (se já instalado), e outras.

5.  **Crie o arquivo `.env` na raiz do seu projeto** e adicione as suas credenciais do Firebase conforme mostrado na seção "Configuração do Ambiente".

6.  **Inicie o aplicativo com Expo.** Execute o seguinte comando no terminal, dentro da pasta do seu projeto:
    ```bash
    npx expo start
    # ou
    yarn start
    ```
    Este comando irá abrir o Expo Developer Tools no seu navegador. Você terá várias opções para executar o aplicativo:
    * **Run on Android device/emulator:** Abre o aplicativo em um dispositivo Android físico conectado ou em um emulador configurado.
    * **Run on iOS simulator:** Abre o aplicativo no simulador do iOS (disponível apenas em macOS).
    * **Run in web browser:** Abre uma versão web do seu aplicativo (algumas funcionalidades nativas podem não estar disponíveis).

7.  **Leia o QR code com o aplicativo Expo Go no seu dispositivo (para dispositivos físicos).** Se você escolher executar no seu dispositivo Android ou iOS, certifique-se de ter o aplicativo Expo Go instalado. Escaneie o QR code mostrado no Expo Developer Tools com a câmera do seu dispositivo através do aplicativo Expo Go.

Agora você deve conseguir executar o seu aplicativo de cursos no seu ambiente de desenvolvimento!

![7e40b8f9-e04c-4321-ac08-187547368280](https://github.com/user-attachments/assets/29927286-4467-4889-9052-9d7c6a0d46f5)
![bbf92d20-fc98-4319-aa17-22d7d9e4ee95](https://github.com/user-attachments/assets/c472740c-b2c4-4401-b965-c6e49769dc0e)
