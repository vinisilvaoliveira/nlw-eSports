1 - AULA 1
    NODE: (configuração de ambiente) 
        -npm init -y (iniciar aplicação node) 
        -npm install express (coisas comuns - rotas) 
        -npm install typescript 
        -npm install ts-node-dev -D (restart automatico ) 
        -HOPPSCOT -> gratuito igual postman, insominia


    React: (configuração de ambiente)
        -Vitejs = https://vitejs.dev/
        -npm create vite@latest
        -conceitos react -> componentes  propriedades
        criar componentes:
            function Button() {
                return (
                    <button>
                        Enviar
                    </button>
                )
            }
        executar: 
        function App() {
            return <Button />
        } 

    reactNative: (configuração de ambiente)
        -JavaScript -> Bundle -> Expo -> Android/IOS -> interfaces declarativas com JSX 
        -https://docs.expo.dev/
        -npm i -g expo-cli
        -expo init mobile (iniciar uma nova aplicacao com nome "mobile" )
        -escolher a opção blank typeScript
        -expo go (instalar no device fisico)
        -expo start (iniciar aplicação)