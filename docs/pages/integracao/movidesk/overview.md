# MOVIDESK
O Movidesk é um sistema de atendimento que une recursos de Help Desk e Service Desk. Ele pode ser. utilizado tanto para a comunicação com os clientes, quanto para a comunicação interna. [movidesk.com](https://www.movidesk.com/).


## [API do Movidesk - Telefonia - Sem controle da fila](https://atendimento.movidesk.com/kb/article/32178/api-do-movidesk-telefonia-sem-controle-da-fila?menuId=22479-61185-32178&ticketId=&q=)

### Recursos utilizados
* `Chamada transferida` - Ligações atendidas.
* `Chamada finalizada` - Ligações encerradas.
* `Chamada cancelada/abandonada` - Ligações que não tiveram atendimento.

## O projeto (proposta)
O Gnew informa os status de chamadas através da **API do Movidesk**, que recebe os status em 3 endpoinsts:

| Método  | Endpoint  |
| ------------ | ------------ |
| GET  |  /asterisk_startTransferedCall |
| GET  | /asterisk_completedCall  |
| GET  | /asterisk_startCanceledCall  |

## Layout do projeto
![Imagem gnew](../../../assets/img/Fluxo.png)