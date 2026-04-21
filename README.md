Script em R para gerar um fluxograma do tipo PRISMA usado em revisões sistemáticas, utilizando DiagrammeR. 
O código cria um diagrama com etapas de identificação, triagem e elegibilidade a partir de dados de busca bibliográfica.

Pré-requisitos: R e RStudio instalados.

Pacotes: DiagrammeR, DiagrammeRsvg e rsvg. 

Exemplo de instalação: install.packages(c("DiagrammeR", "DiagrammeRsvg", "rsvg"))

Personalização: 
Edite os textos dentro de label = '' para refletir seus dados;
Ajuste layout com rankdir = TB (vertical) ou LR (horizontal);
Modifique cores com fillcolor;
Altere tamanho de fonte com fontsize.

Exemplo de uso foi aplicado em uma revisão bibliométrica sobre milho doce e biofertilizantes com etapas de busca em português e inglês, triagem e elegibilidade. 
Também pode ser utilizado para revisões bibliográficas.

Autor
Jasmyn Tognere 

Referências Bibliográficas: 
BORGES, G.; KLEIN, L. L. Tutorial Bibliometrix: passo a passo de utilização da ferramenta para análises bibliométricas da literatura. 
Santa Maria, Rio Grande do Sul. 2024. Disponível em < https://www.ufsm.br/app/uploads/sites/539/2025/03/TUTORIAL-BIBLIOMETRIX.pdf > 
Acesso em 21 abr. 2026. 
