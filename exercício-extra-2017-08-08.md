- Apache HHTP Server

Novos Módulos
mod_proxy_fcgi
Fastend do protocolo FastCGI para mod_proxy
mod_proxy_scgi
Protocolo de protocolo SCGI para mod_proxy
mod_proxy_express
Fornece proxies reversos de massa dinamicamente configurados para mod_proxy
mod_remoteip
Substitui o aparente endereço IP e o nome do host remoto para a solicitação com a lista de endereços IP apresentada por um proxies ou um balanceador de carga por meio dos cabeçalhos das solicitações.
mod_heartmonitor, mod_lbmethod_heartbeat
Permita mod_proxy_balancerbasear decisões de balanceamento de carga no número de conexões ativas nos servidores backend.
mod_proxy_html
Anteriormente, um módulo de terceiros, isso suporta a fixação de links HTML em uma situação de proxy reverso, onde o backend gera URLs que não são válidos para os clientes do proxy.
mod_sed
Uma substituição avançada de mod_substitute, permite editar o corpo de resposta com o poder total de sed.
mod_auth_form
Permite a autenticação baseada em formulários.
mod_session
Permite o uso do estado da sessão para clientes, usando armazenamento de cookies ou banco de dados.
mod_allowmethods
Novo módulo para restringir determinados métodos HTTP sem interferir com autenticação ou autorização.
mod_lua
Incorpora o idioma Lua em httpd, para funções de configuração e lógica de pequenas empresas. (Experimental)
mod_log_debug
Permite a adição de log de depuração personalizável em diferentes fases do processamento da solicitação.
mod_buffer
Fornece armazenamento em buffer das pilhas de filtro de entrada e saída
mod_data
Converta o corpo da resposta em um URL de dados RFC2397
mod_ratelimit
Fornece Limitação de Taxa de Banda Larga para Clientes
mod_request
Fornece filtros para lidar e disponibilizar os organismos de solicitação HTTP
mod_reflector
Fornece Reflexão de um corpo de solicitação como uma resposta através da pilha de filtro de saída.
mod_slotmem_shm
Fornece um provedor de memória compartilhada baseado em slots (ala o painel de avaliação).
mod_xml2enc
Anteriormente, um módulo de terceiros, isso aceita a internacionalização em módulos de filtro baseados em libxml2 (com reconhecimento de marcação).
mod_macro (Disponível desde 2.4.5)
Fornecer macros dentro dos arquivos de configuração.
mod_proxy_wstunnel (Disponível desde 2.4.5)
Apoio de túneis de conexão web.
mod_authnz_fcgi (Disponível desde 2.4.10)
Habilite aplicativos do autorizador FastCGI para autenticar e / ou autorizar clientes.
mod_http2 (Disponível desde 2,4.17)
Suporte para a camada de transporte HTTP / 2.
mod_proxy_hcheck (Disponível desde 2.4.21)
Apoie verificações de saúde dinâmicas independentes para servidores de backend de proxiy remotos.
topo



- NGINX
Depois de apenas 30 dias de desenvolvimento é disponibilizado uma nova versão estável do nginx 1.0.7 seguido da versão 1.0.8, estes lançamentos contém 3 melhorias e 16 correções/mudanças 
já previamente disponível para avaliação na versão de desenvolvimento. 
Entre as principais novidades estão o módulo ngx_http_mp4_module, diversas correções que impediam a compilação do nginx, redução de consumo de memória dentre outras.



- WordPress

A versão 4.8 do WordPress enfim foi lançada! Se você acompanhou nossa cobertura sobre o beta, então já sabe das novidades que vieram com a versão de codinome “Evans”.
Basicamente, tudo o que foi previsto nas versões beta se confirmou na versão final – inclusive a novidade de “limite dos links”, que agora finalmente fica um pouco mais clara.
Cabeçalhos mais acessíveis no painel de administração. Devido a novas regras de CSS, conteúdo alheio ao cabeçalho da área de administração, como links de “Adicionar novo”, não precisam mais estar nestas áreas. Isso melhora a acessibilidade para aqueles que usam tecnologias assistivas.
Remoção do suporte para arquivos WMV e WMA. Como cada vez menos navegadores dão suporte para o Silverlight, formatos de arquivo que necessitam da presença do plugin não recebem mais suporte pelos arquivos básicos. Os arquivos continuarão sendo exibidos como um link para download, mas não serão mais incorporados automaticamente.
Atualizações no multisite. Novas capacidades foram introduzidas na versão 4.8 com a intenção de remover chamadas para is_super_admin(). Além disso, foram adicionados novos ganchos e ajustes para uma maior granularidade no controle dos sites e na contagem de usuários por rede.
