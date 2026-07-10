![LibreSpeed Logo](https://github.com/librespeed/speedtest/blob/master/.logo/logo3.png?raw=true)

# LibreSpeed HTML - Automated Router-X Stack

Sem Flash, Java, Websocket, besteira.

Este e um Speedtest extremamente leve, implementado em Javascript Puro, usando XMLHttpRequest e Web Workers. Esta versao foi totalmente automatizada e otimizada para rodar com foco em performance na stack Nginx + PHP-FPM.

## Teste
[Teste aqui](https://librespeed.org)

## Compatibilidade
Todos os navegadores modernos são suportados: IE11, mais recente Edge, mais recente Chrome, mais recente Firefox, mais recente Safari.
Também funciona com versões móveis.

## Features
* Download
* Upload
* Ping
* Jitter
* IP Address, ISP, distância do servidor (opcional)
* Telemetria (optional)
* Compartilhamento de resultados (opcional)
* Vários pontos de teste (opcional)

## Requisitos do servidor
* Um servidor Web com Apache 2 (nginx, IIS também suportado)
* PHP 5.4 (outros back-ends também disponíveis)
* Banco de dados MySQL/MariaDB para armazenar os resultados dos testes (opcional, PostgreSQL e SQLite também são suportados)
* Uma rápida conexão de internet

## Android app
Um modelo para criar um cliente Android para sua instalação do LibreSpeed está disponível [aqui]

## License
Direitos autorais (C) 2016-2020 Federico Dossena

Este programa é um software gratuito: você pode redistribuí-lo e / ou modificar
nos termos da Licença Pública Geral Menor GNU, publicada pela
Free Software Foundation, versão 3 da Licença ou
(a seu critério) qualquer versão posterior.

Este programa é distribuído na esperança de que seja útil,
mas SEM QUALQUER GARANTIA; sem sequer a garantia implícita de
COMERCIALIZAÇÃO ou ADEQUAÇÃO PARA UMA FINALIDADE ESPECÍFICA. Veja o
GNU General Public License para mais detalhes.

Você deveria ter recebido uma cópia da Licença Pública Geral Menor GNU
junto com este programa. Caso contrário, consulte <https://www.gnu.org/licenses/lgpl>.
