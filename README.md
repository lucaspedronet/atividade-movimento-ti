# atividade-movimento-ti

Apresentação: Atividade proposta no curso de react-native no evento Movimento TI no CEULP/Ulbra.

### Atividade 01

Crie uma aplicação do zero com nome de projeto **myGitHub** você deve reproduzir o layout abaixo utilizando FlexBox layout:

![Tela de Login](./assets/Login.png)

Nesse projeto você desenvolverá uma tela de Login como a ilustrada acima e Feed de posts. Crie um layout tentando chegar o mais próximo possível da imagem acima (logo abaixo temos um guia de metricas e cores).

**Atenção**: Não é obrigatório desenvolver o layout da tela de Feed, mas caso queira, você pode acessar [Tela Feed repositorios](./assets/Repositorios.png).

### Regras:

- O layout deve ser criado utilizando apenas os componentes `<View />` , `<Text />`, `<StyleSheet />`, `<StatusBar />`, `<TextInpu />` e `<TouchableOpacity />` do react-native; e `<Icon />` do react-native-vector-icons.
- Você deve criar apenas um component com nome Login, este deve ser utilizado no component App (component principal).
- O nome do usuário deve ser armazenado no estado do componente Login da sua aplicação.

### Metricas do Projeto:

- Caso queira segui os padrões/metricas do Google - Android acesse [List](https://material.io/archive/guidelines/components/lists.html#lists-specs), [Card](https://material.io/archive/guidelines/components/cards.html#cards-content), [Layout Metrics & keylines](https://material.io/archive/guidelines/layout/metrics-keylines.html#metrics-keylines-keylines-spacing) e outros (List, Card, Header, Button e etc).
- Referências de cores:
- - Cor ícone do github: "#FFFFFF"
- - Cor background: "#212121"
- - Cor button: "#32CC56"
- - Cor do placehould: "#D1D5DA"
- - Cor do link: "#3B86FF"
- - Cor Text Description: "#C0C0C0"
- Metricas:
- - PaddingHorizontal: 20,
- - PaddingTop do ícone: 15,
- - PaddingTop do Button para InputText: 15,
- - height de Buton para Input: 54,
- - height de InpuText para Input: 54,

### Dicas:

- Para alinhar todo conteúdo de um componente ao centro basta unir as propriedades `justifyContent: “center”` e `alignItems: “center”`;
- Para uma melhor abordagem do conceito, acesse este link: https://facebook.github.io/react-native/docs/layout-props

##### Criando novo projeto

- No Windows abra a pasta `perfil de usuário` - e apartir dela abra o CMD, em seguida execute o seguite comando:

- `$ react-native init NomeDoProjeto` - _Criando um novo projeto em react native._

- `$ cd NomeDoProjeto` - _Acesse o projeto._

- `$ adb connect IP_DO_EMULADOR:5555` _esse comando deve ser executado com emulador aberto, pra descubrir o IP de seu emulador bastar maximiza a janela do emulador, o seu IP será apresenta no cabeçalho._

- `$ react-native run-android` - _(caso esteja utilizando o Mac react-native run-ios) esse processo de Build deve ser realizado com emulador aberto._

- `$ react-native start` ou `yarn start` - _inicializar o projeto (deve ser executado na pasta do projeto)._

- `$ react-native start --reset-cache` - _este comando rezeta o cache de memória do metro blund, na maioria das vezes resolve grande parte dos problemas._

### Entregar:

- Esse desaﬁo precisa ser entregue **até data 25/05/2019 às 23:59** (23 horas e 59 minutos), e receberá a correção, mas você pode ver o resultado do código da atividade feito por mim aqui: **Em brave**.
- A entrega deve ser via github acessando esta [organização](https://github.com/curso-de-react-native-movimento-ti) e criando um novo repositório com seu nome, será avaliado os commits como forma de a participação.
- PS.: Tente fazer o desaﬁo sem olhar o código antes :)
- PS2.: Após concluir o desaﬁo, adicionar esse código ao seu Github é uma boa forma de demonstrar seus conhecimentos para oportunidades futuras :D
