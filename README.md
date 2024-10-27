# Governança e Conformidade
## Portal de segurança do Serviço
o [Portal de Segurança do Serviço](https://servicetrust.microsoft.com/) serve como um guia, já que aqui podemos encontrar: Informações de sertificações, regulamentos, padrões de serviço, informação de como os serviços protegem os dados etc.

## Bloqueios de srviços (Locks)
### Resource Group
Um Lock configurado em um grupo de recurços faz com que todos os recursos que fazem parte dele herdem esse lock, que podem ser movidos para outros grupos (dependendo do lock); se o recurso for criado separado de um grupo de recurso, não herda nenhum lock de gurpos de recurços posteriores.
- Lock Delete ---> Pode ler; pode atualizar; mas não pode excluir
- Lock Readonly ---> Pode ler; mas não pode atualizar nem excluir

## Microsoft Policys (Politicas)
São aplicadas a qualquer pessoa/cargo de acordo com as leis;
- É possivel *criar* politicas personalizadas.
