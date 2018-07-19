# fastlane-starter-iOS
repositorio para utilização de fastlane no iOS


fastlane - principais funções
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
https://docs.fastlane.tools/getting-started/ios/setup/
```
xcode-select --install
```
Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

```
update_fastlane

## iOS

### inicia os arquivos do fastlane configuração para envio ao iTunes, seguir os passos orientados
```
fastlanne init

### cria e baixa os certificados 
https://docs.fastlane.tools/actions/cert/#cert
```
fastlane cert

### cria os arquivos de publicação da apple store
https://docs.fastlane.tools/actions/deliver/#deliver
```
fastlane deliver init

### cria os arquivos de envio de screenshots da apple store
https://docs.fastlane.tools/actions/capture_screenshots/#capture_screenshots
```
fastlane snapshot init


### criar os certificados de push 
https://docs.fastlane.tools/actions/pem/#pem
```
fastlane pem --force -p "senha do certificado" --development




