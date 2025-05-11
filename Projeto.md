Especificação de Requisitos do 
Sistema: Quality Study 
1. Escopo Atualizado do Projeto 
O Quality Study é uma plataforma web/mobile voltada para organização de estudos, 
voltada principalmente para estudantes e concurseiros que desejam otimizar seu 
tempo e planejamento. A ideia surgiu da dificuldade em estudar de forma 
organizada, conciliando grande volume de conteúdo com prazos limitados. O 
sistema propõe a criação automática de cronogramas personalizados com base em 
prazos, disponibilidade do usuário e conteúdos fornecidos manualmente ou 
extraídos de editais via upload de PDF/imagem. 
2. EAP (Estrutura Analítica do Projeto) 
1. Levantamento de Requisitos 
2. Protótipo de Telas e Experiência do Usuário 
3. Desenvolvimento Backend (API) 
4. Desenvolvimento Frontend (interface web/mobile) 
5. Integração com OCR e IA para análise de PDFs/imagens 
6. Sistema de Cronograma Dinâmico 
7. Testes e Validação 
8. Segurança e Autenticação (fase futura) 
9. Lançamento MVP e feedback de usuários 
Requisitos Funcionais (RF) 
CÓDIGO -  REQUISITO FUNCIONAL : DESCRIÇÃO — ( LEGENDA) 
RF01 - Cadastro de Usuários : O sistema deve permitir que usuários se cadastrem                       
informando nome, e-mail e senha. 
RF02 - Login e Autenticação : O sistema deve permitir login com validação segura 
dos dados (JWT em versões futuras). 
RF03 - Criação de Cronograma : O usuário deve informar o prazo, matéria e 
conteúdo. O sistema gera um cronograma com sugestão de dias/horas para estudo. 
RF04 - Registro de Disponibilidade : O usuário deve conseguir informar seus 
horários livres. 
RF05  - Upload de Edital (PDF/Imagem) : O sistema deve permitir envio de arquivo 
de edital para extração automática de conteúdo via OCR e IA. 
RF06 - Visualização de Cronograma : O usuário pode visualizar e editar seu 
cronograma personalizado. 
RF07 - Edição de conteúdo : O usuário pode editar as matérias e os conteúdos 
planejados no cronograma. 
RF08 - Feedback sobre andamento : O usuário pode marcar como "estudado" e 
acompanhar o progresso. 
Requisitos Não Funcionais (RNF) 
CÓDIGO - REQUISITO NÃO FUNCIONAL : JUSTIFICATIVA — ( LEGENDA) 
RNF01 - Interface Responsiva : Para garantir acesso via desktop e dispositivos móveis 
com boa usabilidade. 
RNF02 - Performance : O sistema deve gerar cronogramas em tempo real sem 
travamentos. 
RNF03 - Usabilidade : Interface simples, intuitiva e com fluxos de navegação claros. 
RNF04 - Compatibilidade : Compatível com navegadores modernos (Chrome, Firefox, 
Edge). 
RNF05 - Escalabilidade :  Estrutura preparada para expansão de funcionalidades futuras 
(como gamificação, grupos de estudo, IA preditiva). 
RNF06 - Segurança de Dados (futuro) : Uso de bcrypt e JWT para criptografia e 
autenticação de usuários. 
Priorização de Requisitos 
Critérios Utilizados: 
● Obrigatórios: fundamentais para que o sistema cumpra sua função básica. 
● Desejáveis: agregam valor mas podem ser adicionados após o MVP. 
● Opcionais: ideias futuras que complementam a experiência. 
Tabela de Priorização 
Requisito 
RF01, RF02, RF03, RF04, RF06 
RF05, RF07, RF08 
RNF06 
Prioridade 
Obrigatórios 
Desejáveis 
Opcional 
(implementação futura