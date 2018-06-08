[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat)](https://github.com/mercadopago/px-android)
# Plugin MercadoPago Cordova adaptado para o sistema KMRS
O MercadoPago Hybrid SDK facilita a coleta de detalhes do cartão de crédito dos usuários dentro de um aplicativo hibrido (WebView), usando a biblioteca Nativa do MercadoPago. Com a criação de tokens, o MercadoPago lida com a maior parte da conformidade com a PCI, impedindo que dados sensíveis de cartões fiquem em seu servidor.

![Screenshot iOS](https://cloud.githubusercontent.com/assets/9399970/20975888/96dd46e4-bc7f-11e6-9aab-436cf8ff97f5.png)

# Instalação
Primeiramente, instale o plugin do MercadoPago no config.xml com o comando abaixo

    <gap:plugin name="mercadopago-plugin-kmrs" source="npm" />

Também é possível instalar via url diretamente no repositório ( instável, usada somente para testes de implantação )

    <gap:plugin spec="https://github.com/popcomputadores-desenv/px-hybrid.git#plugin" source="git"/>

Se você tiver problemas com a versão do iOS, consulte [aqui](https://github.com/mercadopago/px-hybrid/wiki/Using-the-plugin-with-iOS-Guide).

# Documentação
  [Veja no site do MercadoPago Developers!] (http://mercadopago.github.io/px-hybrid/)
