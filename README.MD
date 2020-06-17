# Primeiros passos

## Instalar Chocolatey
### PowerShell(Admin) 
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
choco

## Instalar vscode / Git / Node.js / yarn
### PowerShell(Admin)
cinst vscode git nodejs-lts -yf

VsCode
https://code.visualstudio.com/download

Git
https://gitforwindows.org/

Node.js
https://nodejs.org/ ou 

## Instalar expo
### PowerShell(Admin): 
npm install expo-cli --global

## Criar Projeto
### Terminal bash: 
expo init nomeProjeto
npm run android

# Configurar Navegação 
## Terminal bash:
yarn add react-navigation

# Pasta src
## index.js
## routes.js

# Pasta pages
## main.js

import React, { Component } from 'react';

import {View, Text} from 'react-native';

export default class Main extends Component {
    render(){
        return(
            <View>
                <Text>
                    Hello
                </Text>
            </View>
        )
}
