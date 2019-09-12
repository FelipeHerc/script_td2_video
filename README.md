
# Script Vídeo TD2

## Título da proposta
Desenvolvimento de um sistema web de gerenciamento de posse de equipamentos para empresas utilizando metodologias ágeis

## Nome do aluno
Felipe Hercules de Almeida Oliveira

## Nome do orientador
Luiz Alberto Gomes

## Apresentação do problema
É bastante comum o gerenciamento de patrimônio em ambientes empresariais, especialmente no caso de aparelhos eletrônicos. Porém, em muitos momentos tal controle é feito utilizando planilhas ou então de forma manuscrita, dificultando assim procedimentos como consulta do estado do equipamento (se está disponível para algum funcionário, se já está sob posse), emissão de relatórios no dia-a-dia e etc. Outro problema bastante comum ocorre quando o controle de posse é feito por mais de uma pessoa, podendo comprometer a fidelidade dos dados no caso de diversas planilhas distribuídas em várias máquinas, por exemplo. O conteúdo referente ao controle de posse trata-se de um dado muito importante nesse ambiente profissional, cria-se então a necessidade da persistência, padronização e integridade desses dados.

## Estratégias, técnicas e ferramentas para solução do problema
Será desenvolvido um sistema web para facilitar a rotina de controle de posse dentro de ambientes empresariais, nesse sistema será possível:
* Criar e gerenciar patrimônios e suas características
* Criar e gerenciar funcionários
* Criar e gerenciar vínculo entre funcionário e patrimônio (posse)
* Controlar status do equipamento (se está disponível, em posse e etc.)
* Emitir relatórios
* Emitir e persistir documentos de posse

O desenvolvimento será feito utilizando técnicas de metodologias ágeis, dando foco ao uso de TDD (Test Driven Development). Serão feitas releases incrementais, dando prioridade no desenvolvimento de funcionalidades que agreguem maior valor ao projeto.

O backend será desenvolvido em Rails, o frontend será desenvolvido em React, e a integração será feita via API.
Serão utilizados também serviços da aws para hospedagem e armazenamento de arquivos.

## Potenciais beneficiários da solução
O sistema será escalável para que seja possível acrescentar mais funções conforme necessário. Sendo assim, qualquer instituição que faça controle de patrimônio poderá usufruir e da plataforma e contribuir para seu crescimento.
Atualmente há uma parceria com a empresa Outcenter, o sistema será utilizado internamente pelos setores responsáveis pelo controle de posse desde a primeira release, tornando possível obter métricas de usabilidade e tornando mais fácil o planejamento de tarefas.

## Considerações finais
O foco do projeto é o uso tecnologias modernas, manter uma alta qualidade de código, aprimorar conhecimentos sobre TDD e metodologias ágeis e, principalmente, agregar valor no cotidiano dos usuários.
