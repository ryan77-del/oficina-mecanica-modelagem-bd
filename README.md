## 📊 Diagrama do Banco de Dados
![Diagrama](oficina-mecanica-modelagem-bd/Sistema%de%Gestão%de%Ordens%de%Serviço/imagens/diagrama-oficina.png)





# Sistema de Gestão de Ordens de Serviço - Oficina Mecânica
Projeto de modelagem de banco de dados para um sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.


# Objetivo 🎯
Modelar o funcinamento de um sistema de gerenciamento de ordens de serviço em uma oficina mecânica seguindo as regras de negócio

# Entidades 📜:
- Cliente
- Veículo
- OS (Ordem de serviço)
- Equipe
- Mecânico
- Peça
- Serviço

# Regras de negócios modeladas 🛍️:
- Cada cliente pode possuir vários veículos.
- Cada veículo pode gerar várias ordens de serviço ao longo do tempo.
- Cada ordem de serviço pertence a um veículo e é atribuída a uma equipe.
- Uma equipe pode atender várias ordens de serviço.
- Uma equipe é formada por vários mecânicos.
- Uma ordem de serviço pode conter vários serviços e várias peças

# Arquivos 🗃:
- Imagem do diagrama
- Arquivo do MySQL 

# Ferramentas utilizadas 🛠:
- MySQL Workbench
- GitHub
