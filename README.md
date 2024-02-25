# Projeto IntegraBrasilAPI em C#

Este é um projeto em C# que utiliza a BrasilAPI para fornecer funcionalidades relacionadas a informações de endereços e dados bancários no Brasil. A BrasilAPI é uma API pública brasileira que fornece acesso a diversos dados úteis.

## Funcionalidades

### Buscar Endereço por CEP:
* Utilize a função BuscarEnderecoPorCEP(string cep) para obter informações detalhadas sobre um determinado CEP.

* Utilize a função BuscarCodigosBancos() para obter uma lista de códigos de todos os bancos no Brasil.

* Utilize a função ObterDadosBanco(int codigoBanco) para inserir o código de um banco específico e receber informações detalhadas sobre ele.

### Certifique-se de que você tenha o seguinte instalado:

* .NET Core SDK
* BrasilAPI NuGet Package (disponível em [https://www.nuget.org/packages/BrasilAPI/])

## Como Usar

* Clone o repositório:

* git clone https://github.com/ReisLuizito/brasil_api_consulting.git
* cd seu-projeto
* Abra o projeto em seu ambiente de desenvolvimento preferido.

## Execute o projeto.

* dotnet run

* Sinta-se à vontade para contribuir para este projeto. Se encontrou um problema ou tem sugestões para melhorias, abra uma issue ou envie um pull request.
