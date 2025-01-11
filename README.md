# Desafio Phishing para captura de senhas do Facebook

### Ferramentas

Abrir o aplicativo Virtual Box e acessar as máquinas Virtuais: 
- Kali Linux > setoolkit
- Windows

### Configurando o Phishing no Kali Linux

Entrar na Máquina Virtual da Kali Linux:
- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
  
Vai iniciar a interface setoolkit, seguir vai mostrar as ferramentas para a construção da página do desafio, escolher as opções abaixo:
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` Vai mostrar o IP ``` dar enter pra continuar
- URL para clone: http://www.facebook.com

### Teste da clonagem

Entrar na Máquina Virtual do Windows
- Abrir o navegador
- digitar o IP
- colocar o login e senha.

### Resutados

Ao executar o teste na Máquina Virtual do Windows, voltar para a Máquina Virtual do Linux para verificar a movimentação do site clonado:

![image](https://github.com/user-attachments/assets/3b17d59c-f1ab-48e3-a578-7d7df6c4bcd7)

Ao colocar o login e senha na pagina clonada, vai fazer o registro do que foi digitado no Linux conforme imagem abaixo:

![image](https://github.com/user-attachments/assets/33a7bdef-e64f-4338-a837-a4facff9ca19)

![image](https://github.com/user-attachments/assets/ec4b7070-faba-43e9-9ce1-a05c74869167)




