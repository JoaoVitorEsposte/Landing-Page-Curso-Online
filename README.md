# Landing-Page-Curso-Online
Landing Page de Curso Online de Montagem e Manutenção de Computadores 

Neste meu mais recente projeto evoluí muito no uso da biblioteca AOS. Tive várias dificuldades técnicas por conta dela, mas aprendi a lidar com a maioria das particularidades que enfrentei.
Houve uma coisa que não consegui entender, e foi o fato de o AOS não funcionar direito com a pseudoclasse nth-child() do CSS. Só o valor 1n apresentava resultado no contexto do meu código...
Já em outra etapa da página, nos botões de compra do curso, o AOS, quando aplicado diretamente ao botão, não permitia o uso da propriedade transform: scale(); eu baixei o código do AOS e procurei qual parte poderia estar causando essa incompatibilidade, mas não achei. Aí levei minha dúvida para a internet, e achei a solução.
Por eu ter olhado diretamente o código dessa biblioteca, aprendi um pouco mais sobre como ela funciona, e assim vi que ela permite definir um delay para o início das animações. Sabendo disso e com alguns testes, consegui deixar o início do site com animações em sequência, além de melhorar as demais animações

Além do AOS, utilizei dois degradês em um mesmo texto para fazer o tom da cor ir de escuro para claro e depois voltar para escuro. Para isso criei duas variáveis CSS, a --bg-especial-gradiente e --bg-especial-gradiente-reverso, e a única coisa que tive que alterar de uma para a outra foi a direção do degradê (to rigth e to left).

Outra coisa foi a facilidade em usar o "repeat(auto-fill)" tanto na grid principal como na de perguntas e respostas, essa função ajustou automaticamente os itens na grid, e assim não foi preciso definir uma grid-area para cada item (o que iria tomar muito tempo e deixaria o código engessado). No final do projeto, adicionei o título à lista de itens necessários, e como eu estava utilizando o valor auto-fill, esse componente se ajustou por si só e não atrapalhou na Grid.
