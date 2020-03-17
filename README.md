# Escopo Proposto Para Lançamento Emergencial (Apoio estudo EAD / Covid-19)

+ App para Estudantes e Professores ou Mentores selecionados (Advogados / Coachs)

+ Permite cadastro apenas de Estudante (com CPF/email previsamente liberados pelo Admin)

+ Professores/Mentores serão cadastrados manualmente no BD e/ou pelo Administrativo

+ Os matchs dispararão notificações para todos os mentores cadastrados (push, que será ativado apenas após primeiro acesso e autorização do mentor)

+ Ao clicar na notificação, ou "Atender", verifica se Mentoria ainda está em aberto

+ Retirado tempo máximo de primeira resposta OU retirar tela de primeira resposta (indo direto ao chat após atendido)

+ Após primeira resposta Estudante e Mentor terão acesos apenas ao Chat

+ Chat permite envio de Texto, Anexos e Gravação de Voz

+ (À Confirmar) Avaliação Cruzada após Mentoria

+ Ambos podem finalizar a mentoria em andamento







# Tarefas para Lançamento

## Dev - App

+ (*) Ajustes no primeiro acesso
   - Verificar se o estudante é permitido (cpf ou email) e se ainda não tem cadastro
   - Retirar seleção de perfil (apenas estudantes se cadastrarão)

+ (*) Bloquear gestão de perfil pra Professores/Mentores (serão selecionados e cadastrados manualmente)

+ (*) Validar tela de notificações recebidas (e retirá-la dessa versão caso possa causar problema)

+ (*) Retirar cronometro da tela de primeira resposta, OU, Redirecionar direto ao chat após mentor atender

- (*) Tela de Match Offline, listando todas as mentorias em aberto + botão Atender em cada
	- (**) Acrescentar Listener na tela, para retirar a mentoria da lista caso outro mentor tenha atendido, ou adicionar caso cadastrem uma nova enquanto mentor está na tela

+ (**) Validar anexos do chat, inclusive áudio que será gravado e enviado como anexo

+ (***) Implementar recurso de gravação de Áudio, compatível com Expo (versão de Jan/20)
   - (**) Rotina de compactação para upload como anexo

+ (**) Replicar recursos de Avaliação Cruzada (presente na versão Mar/20) na versão Expo (Jan/20)


## Dev - Administrativo

+ (*) Cadastro de Professor / Mentor (nova tela, com todos os dados necesśarios para cadastro ativo como mentor)

+ (*) Cadastrar CPF/email de estudante que poderá usar o App (será validado e único)

+ (*) Validar gestão de Mentorias e Matchs (destaque para em aberto, por ordem de tempo em aberto)

+ (**) Notificar Mentor específico manualmente


## Dev - Publicação

+ (*) Criar conta Play Store (U$25 único)
+ (*) Criar conta Apple Store (U$299 / ano)



## Negócio

+ Definir metódo de controle de estudantes (se será exclusivo de alunos Probante, e se restrição será por CPF no primeiro acesso)

+ Planejar divulgação para os estudantes/testers, e se for o caso, avisar sobre a versão ser Beta (em teste e exclusiva para eles [?])

+ Redigir Termos de Uso, de Privacidade

+ Criar página ou forma de contato para estudantes interessados, e que concordarem com os termos (versão beta) solicitarem permissão de cadastro (caso prefira não permitir todos os alunos do Probante de um vez)

+ Criar página, ou formulário Google, para avaliação e feedback sobre o App (tanto Estudantes como Mentores selecionados)
