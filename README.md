# Channel.
- channel PS3 SysCon Tool 1.3.1

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Tech_Santi) [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/techsanti)


# Doação para o projeto.
- Doação para o projeto.
- Donation for the project.

[![YouTube](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/ademesonsantiago)

# PS3 SysCon Tool 1.3.1

<img width="702" height="702" alt="Capturar" src="https://github.com/user-attachments/assets/a2f71a60-5f49-47dd-8b4d-7b2aec1b7490" />


Funcionalidade do programa:

Idioma: Seleção de idiomas entre português Brasil e inglês.

Porta COM: Seleciona a porta de comunicação COM do módulo ttl, com o botão atualizar caso não reconheça a porta COM.

Tipo SC: Modelos de SysCon selecionável.

Auth: botão de autenticação para fazer comunicação entre o programa, módulo ttl e syscon.

Executar novo ciclo de erro: O botão executa 5 ciclos de ligar e desligar o console, para gerar armazenar o mais precisão os código de erro na SysCon.

Ler log de erro: Faz a leitura dos código de erro da syscon, e também ao terminar a leitura ele irá abrir uma janela mostrando o código de erro detectado.

Janela de erro: Faz abrir a janela de erro, sem a necessidade de iniciar novamente o “Ler log de erro” caso venha fechar acidentalmente a janela que mostra os códigos de erro, fazendo o que você abra a janela de código de erros quantas vezes for necessário.

Inicializar PS3: Inicializa o PlayStation 3 remotamente utilizando o módulo TTL.

Desligar PS3: Desliga por completo PlayStation 3 remotamente pelo módulo TTL.

Limpar log de erros: Limpa completamente os códigos de erro armazenado na syscon. Ele é recomendado em caso de reparo do console, evitando que ao “Executar novo ciclo de erro” e a leitura código se repita mesmo depois de efetuado o reparo do console.

Limpar dados: Faz a limpeza de todos os dados armazenados no programa, evitando resíduos de leitura dos consoles anteriores.

MELHORIAS DO PROGRAMA.

Bancos de dados completo totalmente off-line.

Suporte a dois idiomas.

Sincronização automática com idioma em português Brasil e inglês do programa e com banco de dados.

Conexão rápida e precisa.

Janela que mostra o código de erro automaticamente ao finalizar a leitura.







PS3 SysCon Tool

Uma ferramenta para diagnosticar e controlar o System Controller (SysCon) do PlayStation 3 (PS3) via comunicação serial UART. Ideal para técnicos e entusiastas que precisam ler códigos de erro (como YLOD), autenticar conexões seguras e executar comandos de hardware de baixo nível. Funcionalidades Principais

1- Autenticação Segura: Suporte a autenticação AES para tipos de SysCon: CXR, CXRF e SW. Leitura de Logs de Erros: Executa comandos como "ERRLOG" para coletar até 32 códigos de erro, filtra e exibe descrições baseadas em um banco de dados JSON (em português e inglês).

2- Ciclos de Teste: Realiza power cycles automáticos (bringup/shutdown) para gerar novos logs de erros.

3- Controle do Console: Comandos para ligar (bringup), desligar (shutdown) e limpar logs de erros.

4- Exportação de Dados: Salva erros em TXT/CSV, cópia para clipboard e exibição em janela popup.

5- Interface Amigável: Suporte a idiomas (Pt-Br/En), barra de progresso e logos rotativos.

7- Logging Detalhado: Registra todas as operações em ps3syscon.log para debug.

