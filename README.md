# Projeto Final - Identidade Visual
🔶**Aviso:** sinta-se livre para fazer pequenas alterações nas medidas e espaçamentos se o resultado ficar melhor na página, desde que não altere demais o design original. Além disso, avise o grupo sobre as alterações, para ser possível manter a consistência no design.


💡Telas e Style Guide podem ser encontrados no [Figma do Projeto](https://www.figma.com/design/fYLYoC2BEAbZPjH57wbrDt/Projeto-Final?node-id=0-1&t=3YcQFc7vRJmnprGP-1).

💡Site do [React Icons](https://react-icons.github.io/react-icons/) para pesquisar ícones e seus nomes/imports (os nomes dos ícones estão em inglês).

💡Documentação do [Tailwindcss](https://tailwindcss.com/docs/installation/using-vite) para pesquisar classes e ver exemplos. Se não achar a propriedade na aba esquerda, procure o nome dela no search na parte de cima.

<br>

## 🎨 Cores

|Cor               |Código            |Variante (hover)   |
|------------------|------------------|-------------------|
|Azul (blue)       |#7ABCCD           |#4CAEC7 (darkblue) |
|Marrom (brown)    |#726157           |#5A4D45 (darkbrown)|
|Bege (sand)       |#F1ECE0           |                   |
|Cinza (lightgray) |#EEEEEE           |                   |
|Cinza escuro      |#D1D5DC (gray-300)|                   |
|Vermelho          |#FF6467 (red-400) |#DE5457 (darkred)  |



<br>

## ✒️ Tipografia
### Fontes:
- [Tilt Warp](https://fonts.google.com/specimen/Tilt+Warp?query=tilt)
- [Raleway](https://fonts.google.com/specimen/Raleway?query=rale)

|Elemento              |Fonte              |Tamanho       |Cor       |
|----------------------|-------------------|--------------|----------|
|H1 (Landing page)     |Tilt Warp          |4rem (64px)   |Marrom    |
|H1                    |Tilt Warp          |3rem (48px)   |Marrom    |
|H2                    |Raleway - Semibold |1.8rem (28px) |-         |
|H2 (Cuidados e dicas) |Raleway - Bold     |1.9rem (30px) |-         |
|H3                    |Raleway - Bold     |1.5rem (24px) |-         |
|H4                    |Raleway - Bold     |1.25rem (20px)|-         |
|H5                    |                   |              |          |
|Links (texto)         |Raleway - Semibold |-             |Marrom    |
|Label                 |Raleway - Semibold |.9rem (14px)  |Preto     |
|Botão                 |Raleway - Bold     |1.2rem (20px) |-         |
|Subtítulo             |Raleway - Semibold |1.5rem (24px) |Preto     |
|Texto                 |Raleway - Medium   |1rem (16px)   |Preto     |

<br>

## 🔲 Bordas, medidas e padding
### Todas as páginas (exceto Login e Cadastro)
- **Container -** max-width: 1100px
- padding: 6rem 2rem
- **Header marrom -** padding: 64px 32px

### Página de Cuidados e dicas
- **Sections -** padding: 32px
- **Imagem -** max-width: 420px
- **Header -** padding: 32px
- **Containers -** padding: 32px

### Página de Perfil do pet
- **Container do mapa**
	- border-radius: 5px
 	- padding: 20px
  - max-width: 490px
- **Mapa -** max-width: 300px

### Página de Cadastro de pet
- **Container -** padding: 40px

### Página de Sobre
- **Sections -** padding: 80px 32px
- **Imagens:**
  - max-width: 300px
  - max-height: 400px

### Header
- max-width: 1100px
- padding: 32px

### Botões
**➝ Arredondado**
- border-radius: 25px
- padding: 8px 32px

**➝ Círculo (com ícone)**
- border-radius: 50%
- border: 3px solid -
- padding: 3px
- width/height: 50px

### Cards
**➝ História de adoção**
- border-radius: 10px
- padding: 20px
- max-width: 360px
- gap: 20px
- **Imagem:**
	- border-radius: 50%  
	- width/height: 130px

 **➝ Página inicial**
- border-radius: 15px 15px 20px 20px
- padding: 20px
- max-width: 250px
- **Imagem:**
	- border-radius: 10px 10px 15px 15px  
	- width: 210px
   	- height: 230px

**➝ Perfil do pet**
- border-radius: 15px 15px 20px 20px
- padding: 20px
- max-width: 400px
- **Imagem:**
	- border-radius: 10px 10px 15px 15px  
	- width: 360px
 	- height: 380px
- **Imagem menor:**
    - border-radius: 5px
    - width/height: 90px

**➝ Página de Sobre**
- **Card de valores:**
  - border-radius: 5px
  - padding: 20px
  - **Ícone -** width/height: 60px
- **Card de números:**
  - border-radius: 5px
  - padding: 32px 64px

### Form
- **Container -** padding: 48px 32px
- **Container Login -** width: 35vw (aproximadamente, necessário testar)
- **Container Cadastro -** width: 55vw (aproximadamente, necessário testar)
- **Container Cadastro de pet -** max-width: 695px
- **Círculo de numeração da etapa -** width/height: 30px

### Inputs
- border: 1px solid gray-300
- border-radius: 5px
- padding: 5px 10px

**➝ Login**
- width: 370px

**➝ Cadastro**
- width: 320px

**➝ Cadastro de pet**
- width: 300px
- **Textarea -** width: 100%

### Ícones
- **Geral -** width/height: 24px
- **Card dos pets -** width/height: -

<br>

## 📐 Espaçamento
💡**Dica:** se tiver dúvidas em algum espaçamento (interno/padding ou externo), no arquivo do Figma é possível verificar a distância entre um elemento e outro. Basta clicar em um dos elementos e posicionar o mouse em cima do outro, enquanto pressiona a tecla alt. A distância irá aparecer em um quadradinho vermelho, em pixels.

### Página de Histórias
- **Espaço entre cards -** gap: 24px

### Página de Cuidados e dicas
- **Espaço entre sections -** gap: 40px
- **Espaço interno da header da matéria -** gap: 32px

### Página Inicial
- **Espaço entre conteúdos e header -** gap: 64px
- **Espaço entre cards -** gap: 64px

### Perfil do pet
- **Espaço entre card e texto -** gap: 40px
- **Espaço sections de texto -** gap: 56px

### Página de Sobre
- **Espaçamento entre foto e texto -** gap: 64px
- **Espaçamento entre cards de valores -** gap: 32px

### Form
- **Espaço entre elementos -** gap: 32px
- **Espaço interno do form e section -** gap: 18px
- **Espaço entre input e label -** gap: 10px
- **Espaço entre colunas do form -** gap: 30px
- **Espaço entre colunas de preferências (cadastro) -** gap: 48px
- **Espaço entre linhas de preferências (cadastro) -** gap: 24px
- **Espaço entre elementos da header de etapas -** gap: 12px
- **Espaço entre header de etapas e o form -** gap: 30px
- **Espaçamento entre etapas (cadastro de pets) -** gap: 48px

### Footer
- **Espaço entre seções -** gap: 48px
- **Espaço entre colunas -** gap: 40px
