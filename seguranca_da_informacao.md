# Estudos iniciais sobre Segurança da Informação 

>> Informações retiradas do curso "Defendendo aplicações WEB"
- SSL só protege a camada de transporte. 
- Selo de segurança é só uma imagem. 
- Não existe um plano de hospedagem 100% seguro. 

## Categorias de atacantes

### White Hats

Profissionais de segurança da informação com o intuito de proteção das organizações. 

### Black Hats

Indivíudos com o intuito criminioso normamente focados em espionagem industrial. 

### Script Kiddies 

Normalmente são jovens que se interessam por ferramentas disponibilizadas no YT ou em outros sites, normalmente, não precisamos nos preocupar com esse tipo de perfil. 

### Defacers

Intenção de manifestação contra governo e partidos. 

### Crackers

Quebram sistemas de segurança como KeyGens, etc...

### Carders

Intecionados em roubar cartões de crédito, etc... 

# Etapas de uma invasão

1 - Lenvantamento de informações do alvo

2 - Exploração da vulnerabilidade

3 - Pós-exploração (uso de scripts e coleta de dados sensíveis)

    Compreender as principais vulnerabilidades web e todo passo a passo para explorá-las. (Vejamos...)
    
    
## Coleta de dados 

- Buscar informações públicas sem invasão, apenas por exploração. 

- Google Hacking

- Registrar as infos, é muito importante anotá-las.

- whois.com

- archive.com

- shodan.io

- wappalyzer

- dirb (windows dirbuster)

- php info (version)

## Os pilares das Falhas 
### Learn

 - SQL Injection >> manipulação da conversa da aplicação com o banco de dados
 
 ### Query string 
 
 SELECT * FROM users WHERE email = $email and pass = $pass
 

