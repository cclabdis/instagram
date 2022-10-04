# Requisitos

Sinta-se à vontade para colocar as fotos de exemplo que quiser no seu Instagram! :)

- Layout
    - [ ]  Aplicar layout para desktop, seguindo layout fornecido no figma
    - [ ]  Aplicar layout para mobile, seguindo layout fornecido no figma
    - [ ]  O layout sem sidebar deve ser ativado quando a largura da tela for menor que 935px
    - [ ]  O layout para mobile deve ser ativado quando a largura da tela for inferior a 614px
    - [ ]  Não é obrigatório que a sidebar fique fixa conforme o usuário desce na página como ocorre no Instagram (mas é um bônus)
- Ícones
    - [ ]  Utilize os ícones da biblioteca Ionicons: [https://ionicons.com/](https://ionicons.com/)
    
    A seção **Dicas** contém um tutorial para utilizar a biblioteca.
    
- Stories
    - [ ]  Na caixa dos stories, deve haver itens o suficiente para ultrapassar a largura, mas os itens a mais não devem ser exibidos, conforme layout
    - [ ]  Deve haver, no modo desktop, uma setinha no canto direito dos stories (conforme mostrado no layout do figma)
    - [ ]  A setinha não precisa funcionar ao clicar (só será possível quando vermos JavaScript)
    - [ ]  Não pode haver um scroll horizontal visível

    # Bônus

Bônus não são obrigatórios, mas caso tenha conseguido terminar todo o projeto antes do prazo, sugerimos fazer as seguintes funcionalidades:

- Vídeo
    - [ ]  Pelo menos um dos posts deve ser um vídeo
    - [ ]  Não é necessário ter o botão de play
    - [ ]  O vídeo deve ser inserido tanto no formato .mp4 e .ogg, para que funcione em qualquer navegador
    - [ ]  O vídeo deve ser iniciado automaticamente
    
    Nos arquivos úteis já tem um vídeo para facilitar essa parte :)
    
    Para não incomodar o usuário, os navegadores (nem todos) não permitem que um vídeo toque automaticamente a não ser que o som esteja desativado. Então, se colocou o atributo para iniciar o vídeo automaticamente e não funcionou, desative o som dele :)
    
- Sidebar fixa
    
    Se você acessar a página do Instagram do seu computador e descer na página, perceberá que a barra lateral continua visível, fixa na página.
    
    A ideia deste bônus é implementar este comportamento, fazendo que, ao descer na página, a coluna permaneça no mesmo lugar sempre.
    
- Comentários
    
    Pelos propósitos do projeto, não adicionamos os comentários dos posts no layout do Figma. Estes são os requisitos deste bônus:
    
    - [ ]  Ter comentários nos posts, com botão de like no canto direito em cada comentário
    - [ ]  Uma caixa para digitar o comentário, utilizando a tag `input`
    - [ ]  Um botão ao lado desta caixa para **Publicar**, com cor `#B2DFFC` inicialmente e, ao passar o mouse, fique com a cor `#0095F6` com uma transição que dura `300ms`. Procure pela propriedade *transition* para fazer isso :)