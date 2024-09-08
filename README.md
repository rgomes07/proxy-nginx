Proxy NGINX

NGINX: Para que serve o NGINX e como configurar sua função de proxy para containers docker.

O NGINX é um software open-sorce, projetado para atuar como um servidor web, tem função de proxy reverso, load balancer. O NGINX foi desenvolvido como forma de disponibilizar um baixo uso de memória, além de uma alta simultaneidade. Ele trabalha de forma que as solicitações sejam tratadas em um único thread. Isso evita que o servidor crie processos para cada solicitação.

Esse estilo de processamento de conexão permite que o NGINX seja extremamente eficaz, mesmo com recursos limitados. Como o servidor é de encadeamento único e os processos não são gerados para lidar com cada nova conexão, a memória e o uso da CPU tendem a permanecer relativamente consistentes, mesmo em momentos de carga pesada.

O NGINX foi projetado desde o início para usar um algoritmo de tratamento de conexão sem bloqueio e orientado a eventos.

Quais são as vantagens do NGINX?

O NGINX pode atuar como um balanceador de carga de software muito capaz, além de contar com suas funções mais tradicionais que servem conteúdo estático sobre HTTP e conteúdo dinâmico, usando manipuladores FastCGI para scripts.

Como ele usa uma arquitetura não segmentada, é capaz de superar os servidores da Web, como o Apache. Isso é particularmente eficaz em implantações que recebem cargas pesadas.

Confira, a seguir, outros benefícios que o NGINX proporciona.
Fácil de configurar

O NGINX tem uma estrutura de arquivos de configuração simples. Ele consiste em módulos que são controlados por diretivas especificadas no arquivo de configuração. Elas são divididas em diretivas de bloco e diretivas simples.
Mais rápido e melhor para servir arquivos estáticos

Ao servir arquivos estáticos, como pdf, zip, html, mp4, mpeg, avi, jpg, gif, png e outros, é possível experimentar o incrível desempenho do NGINX. Aqueles que desejam aumentar o desempenho do servidor da Web podem adicionar armazenamento em cache.
Compatibilidade com aplicativos da web comumente usados

O tráfego de qualquer aplicativo da web é tratado pelo NGINX sem problemas. Vários aplicativos populares, como WordPress, Ruby, Python, Joomla, drupal, vbulletin, phpbb e xenforo, são servidos pelo NGINX.
Suporte ao balanceamento de carga

Um dos recursos mais destacados do NGINX é que ele pode configurar o balanceamento de carga para os servidores http de escalonamento rápido. O balanceamento de carga NGINX permite a distribuição de tráfego entre diferentes servidores.

Isso possibilita que os usuários dimensionem seus aplicativos e, simultaneamente, obtenham redundância http. A configuração do lado do servidor também será rápida e fácil.

Conexões simultâneas

A superioridade do NGINX em lidar com conexões simultâneas, tempo de resposta e uso de recursos é óbvia quando ele é comparado com o Apache ou o Lighttpd. Ao optar por esse software, seu ambiente ficará 4x mais rápido.

Assim sendo, atualmente o NGINX é identificado como um dos servidores web mais eficientes e leves do mercado. Ele suporta mais tráfego simultaneamente e também conta com uso mínimo de memória.
Rico em recursos

O NGINX Plus combina a funcionalidade de um servidor Web de alto desempenho, um poderoso balanceador de carga front-end e um cache de aceleração altamente escalável, para criar a plataforma ideal de ponta a ponta para seus aplicativos da web.
Eficiência

O NGINX pode servir um maior número de usuários sem usar recursos extras. Isso é uma vantagem sobre o Apache Server, que cria uma cópia para todas as outras solicitações que acabam com mais uso de RAM.

Além disso, ele tem uma vantagem sobre outros servidores web considerados leves e é muito mais rápido do que o Apache, um dos servidores mais populares nos dias atuais.

Com tantos recursos prontos para uso, o NGINX pode ser uma ótima maneira de servir seu aplicativo ou até mesmo pode ser usado como um proxy HTTP ou um balanceador de carga para seus outros servidores da web. Entender a maneira como o NGINX trabalha e lida com as solicitações dará muito poder para escalar e balancear a carga de seus aplicativos.

https://blog.eveo.com.br/nginx
