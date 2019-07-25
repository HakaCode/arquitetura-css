### base
  - A base é aplicada a seletores de elementos sem o uso de classes ou ID's, também inclui pseudo-classes e filhos usando apenas seletores de elementos. Isso define o estilo padrão da página, mesmo sem colocar nenhuma classe de como os elementos irão se comportar. Na base, normalmente se coloca o CSS reset, normalize, etc.
  
### layout
  - É onde se coloca os estilos das estruturas que não se repetem na página como header, footer, sidebar, main e todo resto que não é componente ou estrutura reutilizada.
  
### module
  - O module é responsavel por determinar as partes reutilizaveis, os componentes. Dentro do modulo pode ter componentes como botões, alertas, menus de navegação, estilos de blocos de textos, widgets, entre outros.
  - Estarão presentes em maiores quantidades
  - Para módulos não se usa ID's
  
### state
  - Determina o estado do elemento.
  - Todo estado recebe o prefixo **.is-** para diferenciar das outras classes, mostrando assim que ela determina um estado modificado daquele elemento.
  
### theme
  - É a parte que menor tem aplicação na maioria dos projetos, é usada para separar a parte que dá um novo design para a página
 
