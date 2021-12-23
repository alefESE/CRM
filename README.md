# Sistema de monitoramento remoto em redes de sensores sem fio
A monitorização do paciente é um processo de coleta de parâmetros médicos de um paciente presente em um local remoto. Este trabalho descreve a simulação deste processo a partir da descrição de um sistema já desenvolvido e publicado.

Todo projeto que pode ser simulado no Cooja precisa de um arquivo Make, que não é diferente do [CMakefiles](https://pt.wikibooks.org/wiki/Programar_em_C/Makefiles) comum, com a exceção da necessidade da inclusão do “Makefile.include” que contém definições dos arquivos C do núcleo do sistema Contiki. Este arquivo sempre reside na raiz da árvore de fontes Contiki.

Dependências:
- Instant Contiki OS v2.7
- VMWare Player 15
- Windows 10 64bit Host
- Firefox Browser

Inicialmente é preciso realizar uma configuração no firefox, pois as versões mais novas do browser não permitem a  WebExtensions API e precisaremos dela para a instalação do Copper (Cu), que é uma extensão que entende o protocolo CoAP, para teste do servidor RESTFul. A configuração do firefox pode ser feita seguindo o tutorial do repositório do próprio autor da extensão, na sessão “How to integrate the Copper sources into Firefox:”, través deste link: <https://github.com/mkovatsc/Copper>.

Mais informações no [relatório](https://docs.google.com/document/d/1fAf1RZqkhXKODpLUxRpoie0SyJll71J-vcgLkQdwTgI/edit?usp=sharing).
