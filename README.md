# estudos-naughtydogs-notebooklm

# 🎯Contexto e Objetivos
Este repositório explora a filosofia de desenvolvimento da **Naughty Dogs** e sua metodologia na criação de jogos.
Desafio proposto pela DIO no bootcamp **Dados e GenIA**, ultilizando a ferramenta nootbooklm.

O Objetivo é documentar como a empresa integra narrativa, gameplay e tecnologia para criar experiências imersivas, sendo capaz de aprimorar e desenvolver habilidades para criação e design de jogos.

# 🌐Curadoria de Fontes
Para este estudo no NotebookLM, foram selecionadas as seguntes fontes:

- [A Hístoria da Naughty Dogs](https://en.wikipedia.org/wiki/Naughty_Dog);
- [Tecnicas de desenvolvimento de jogos](https://www.dualshockers.com/naughty-dog-explains-how-they-develop-their-games-from-start-to-finish/);
- [Design do jogo Uncharted 4](https://gamingbolt.com/naughty-dog-reveals-the-tech-behind-uncharted-4-taas-ps4-gpu-usage-deferred-lighting-and-more);
- [Regime crunch](https://wnhub.io/news/other/item-49626);
- [Métodos operacionais](https://www.reddit.com/r/gamedev/comments/207g2b/naughty_dog_lead_programmer_jason_gregory_talks/).

# 🏗️ Engenharia de Prompts e "Cicatrizes"

# 1° Quais são os principais pilares da metodologia de criação da Naughty Dogs?

A metodologia de criação da Naughty Dog é fundamentada em uma integração simbiótica entre tecnologia de ponta, narrativa cinematográfica e uma estrutura organizacional que prioriza a agilidade e a responsabilidade individual. [1]( https://medium.com/@arnaldo42/level-design-at-naughty-dog-8b9592107805).
Os principais pilares dessa abordagem incluem: 

- **Design "Sem Fricção" e Intencionalidade Espacial:** O estúdio busca minimizar a frustração cognitiva do jogador através da clareza de intenção, garantindo que o propósito de cada nível  seja imediatamente compreensível
. Para isso, utilizam-se Marcos Visuais (Landmarks) para orientação sem auxílio de interface, e "Migalhas de Pão" (Breadcrumbs) — pequenos estímulos visuais que sugerem o próximo passo. [2](https://www.dualshockers.com/naughty-dog-explains-how-they-develop-their-games-from-start-to-finish/)
- **Desenvolvimento Orgânico e Simultâneo:** Diferente de modelos lineares, a Naughty Dog desenvolve sistemas e narrativa ao mesmo tempo
. O coração dessa colaboração é o "Game Macro", um documento simples que serve como mapa de calor emocional e mecânico do projeto, detalhando o ritmo da história e os locais visitados para que o gameplay potencialize os momentos dramáticos. [3](https://www.gamedeveloper.com/game-platforms/in-depth-how-planning-derailed-playtesting-redeemed-i-uncharted-2-i-) [4](https://www.naughtydog.com/blog/naughty_dog_gdc_2017)
- **Iteração Técnica Rápida e "Hacks" Funcionais:** A cultura técnica do estúdio prioriza a velocidade
. Programadores frequentemente implementam "hacks" funcionais — soluções rápidas e possivelmente deselegantes — para que os designers testem mecânicas imediatamente. [5](behind-uncharted-4-taas-ps4-gpu-usage-deferred-lighting-and-more)
- **A Estrutura do Profissional em "T":** O estúdio recruta indivíduos com conhecimento vasto em múltiplas áreas e especialização profunda em um domínio específico. Espera-se, por exemplo, que artistas técnicos tenham proficiência em C++ para construir suas próprias ferramentas, e que cada desenvolvedor atue como seu próprio "produtor", tomando decisões sem depender de uma burocracia excessiva. [6]( https://www.quora.com/I-want-to-be-a-game-producer-Is-this-a-viable-career)
- **Cultura de Comunicação Aberta e Crítica:** Todos no estúdio são encorajados a contribuir com ideias de design e a questionar o que não está funcionando. O design evolui através da inspeção constante por equipes multidisciplinares, onde o feedback é direto e focado na qualidade do jogo, nunca em questões pessoais. [7](https://www.naughtydog.com/blog/naughty_dog_at_gdc_2021) [8](https://cloudairy.com/blog/flat-vs-hierarchical-organizational-structure)
- **Playtesting Intensivo e Métricas:** O estúdio utiliza um volume massivo de testes para refinar o fluxo e a navegabilidade
. Durante o desenvolvimento de Uncharted 2, por exemplo, realizaram 15 testes formais nos últimos dez meses, coletando métricas precisas como tempo de conclusão e frequência de mortes. [9](https://www.reddit.com/r/GamerGhazi/comments/bfoj5m/no_bosses_no_managers_the_truth_behind_the_flat/) [10](https://www.avclub.com/toxic-crunch-culture-reports-come-from-the-last-of)

 Recentemente, a metodologia tem passado por uma transição organizacional, saindo de uma hierarquia plana informal (conhecida por causar períodos severos de crunch) para uma gestão mais profissionalizada com prod° utores dedicados e foco em sustentabilidade humana.

 # 2° De onde vem a ideia de usar tecnicas realistas nos design dos personagens?

 A ideia de utilizar técnicas realistas no design dos personagens na Naughty Dog surgiu de uma transição gradual e estratégica que teve seu ápice com a criação da franquia Uncharted em 2007. 
A evolução para o realismo pode ser traçada através dos seguintes pontos:

- **Evolução Natural em Jak and Daxter:**  Durante a trilogia **Jak and Daxter**, a arte do estúdio já começava a evoluir. As proporções de Jak foram se tornando cada vez mais próximas de um ser humano, e a narrativa se tornava mais intricada, afastando-se da identidade "cartoon" e colorida dos primeiros trabalhos. [1](https://www.youtube.com/watch?v=A4ZpWtXW3YM)
- **O "Projeto Big" (Uncharted):** A decisão consciente de adotar o realismo veio com o codinome "Projeto Big", que viria a ser Uncharted: Drake's Fortune. O objetivo era criar um mundo mais "pé no chão" e real, contrastando com os mundos fantásticos de Crash e Jak. [2](https://medium.com/@arnaldo42/level-design-at-naughty-dog-8b9592107805)
- **Busca pela Qualidade Cinematográfica:** O estúdio desejava que seus jogos tivessem a aparência de um filme. Para isso, era essencial capturar toda a **sutileza das performances** dos atores, o que exigiu que uma equipe anteriormente especializada em animações exageradas (estilo cartoon) criasse novas tecnologias de **captura de movimento** (mocap) e softwares para entregar personagens realistas. [3](https://www.dualshockers.com/naughty-dog-explains-how-they-develop-their-games-from-start-to-finish/)
- **Adoção de Tecnologias Fisicamente Corretas:**  Com a chegada do hardware mais potente (PS3 e PS4), a Naughty Dog percebeu que tudo precisava ser baseado em princípios físicos (**PBR - Physically-Based Rendering**). Isso incluiu simular o comportamento real da luz em materiais como cabelo, tecidos e pele, buscando uma fidelidade visual que desafiasse as limitações do hardware. [4](https://www.gamedeveloper.com/game-platforms/in-depth-how-planning-derailed-playtesting-redeemed-i-uncharted-2-i-) [5](https://gamefaqs.gamespot.com/boards/652686-the-last-of-us/66779112)

 Essa mudança não foi apenas estética, mas também técnica e narrativa, permitindo que o foco dos jogos permanecesse na jornada emocional dos personagens, algo que o estúdio considerava mais impactante em contextos realistas e fundamentados na realidade humana.

 # 3° Como funciona o documento 'Game Macro' na prática? E como ele opera?

 O documento 'Game Macro' funciona como a fundação esquelética e estratégica de um projeto na Naughty Dog, servindo de mapa de calor emocional e mecânico para todo o desenvolvimento. Na prática, ele substitui os tradicionais documentos de design de centenas de páginas por uma planilha simples, geralmente com cerca de 70 linhas de extensão.
 Abaixo estão os detalhes de como esse documento opera no cotidiano do estúdio:

 - **Conteúdo Detalhado e Conciso:** O Macro detalha as batidas da história (story beats), os locais visitados e os padrões de jogabilidade esperados para cada segmento do jogo. [1](https://medium.com/@arnaldo42/level-design-at-naughty-dog-8b9592107805)
  
 - **Criação Multidisciplinar:** O documento não é feito apenas por designers; ele é estabelecido por equipes cruzadas que incluem programadores, artistas, animadores e especialistas em áudio e efeitos. [2](https://www.deviantart.com/kahlanamnelle/art/the-last-of-us-part-ii-2020-2024-mobile-996784472)

 - **Adaptabilidade e Mudança:** Sua força reside na simplicidade esquelética, o que o torna altamente adaptável às mudanças inerentes ao processo de produção orgânica do estúdio. [3](https://www.naughtydog.com/blog/naughty_dog_gdc_2017) [3](https://gamefaqs.gamespot.com/boards/652686-the-last-of-us/66779112)

 - **Ferramenta de Rastreamento de Visão:** Ao longo da produção, o estúdio usa o Macro para rastrear a visão original, complementando-o com ferramentas ágeis como quadros brancos e fotografias digitais para registrar iterações rápidas sem gerar burocracia excessiva. [4](https://www.naughtydog.com/blog/naughty_dog_gdc_2017)
   



 
 




 





