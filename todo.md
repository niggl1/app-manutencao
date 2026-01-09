# App Manutenção - TODO

## Fase 1: Setup Inicial
- [x] Inicializar projeto com scaffold web-db-user
- [x] Copiar componentes UI do AppSindico
- [x] Configurar tema premium (cores, fontes, sombras)
- [x] Configurar DashboardLayout

## Fase 2: Schema da Base de Dados
- [x] Criar tabela organizacoes (universal, substitui condominios)
- [x] Criar tabelas de Ordens de Serviço (OS)
- [x] Criar tabelas de Vistorias
- [x] Criar tabelas de Manutenções
- [x] Criar tabelas de Ocorrências
- [x] Criar tabelas de Checklists
- [x] Criar tabelas de Vencimentos
- [x] Criar tabelas de Realizações/Melhorias/Aquisições
- [x] Criar tabelas de Revistas
- [x] Criar tabelas de Relatórios

## Fase 3: Módulos Core
- [x] Dashboard principal com estatísticas
- [x] Gestão de Organizações (universal)
- [x] Sistema de Ordens de Serviço completo
- [x] Configurações de OS (categorias, status, prioridades)

## Fase 4: Módulos Operacionais
- [x] Vistorias
- [x] Manutenções preventivas/corretivas
- [x] Ocorrências
- [x] Checklists
- [x] Agenda de Vencimentos

## Fase 5: Módulos de Documentação
- [x] Antes e Depois
- [x] Realizações
- [x] Melhorias
- [x] Aquisições

## Fase 6: Relatórios e Revistas
- [x] Sistema de Relatórios
- [x] Construtor de Relatórios
- [x] Editor de Revistas Digitais
- [x] Visualizador de Revistas
- [x] Exportação PDF

## Fase 7: Personalização
- [x] Configurações do sistema
- [x] Personalização de cores/logo
- [x] Páginas customizadas

## Fase 8: Compatibilidade
- [ ] Configurar para Vercel
- [ ] Integrar Capacitor
- [ ] Testes em mobile

## Bugs Reportados
(nenhum até agora)

## Testes Realizados
- [x] Cadastro de organização (Empresa Teste Manutenção)
- [x] Criação de Ordem de Serviço (#891947)
- [x] Visualização de Checklists
- [x] Sistema de Relatórios com gráficos
- [x] Navegação pelo menu lateral
- [x] Funções rápidas no dashboard

## Notas
- Todas as referências a "condomínio" devem ser substituídas por "organização" (tarefa futura)
- Layout premium consistente em todos os módulos
- Sistema universal para qualquer tipo de organização
- Capacitor será configurado após validação do sistema base

## Fase 9: Personalização da Logo
- [x] Copiar nova logo para pasta public
- [x] Atualizar logo no header
- [x] Atualizar favicon
- [x] Atualizar referências no sidebar/dashboard

## Fase 10: Universalização Completa
- [x] Substituir "condomínio" por "organização" em todos os ficheiros
- [x] Substituir "síndico" por "gestor" em todos os ficheiros
- [x] Substituir "morador" por "equipa" onde aplicável
- [x] Atualizar nome da aplicação de "App Síndico" para "App Manutenção"

## Fase 11: Capacitor
- [ ] Instalar Capacitor
- [ ] Configurar capacitor.config.ts
- [ ] Adicionar plataformas iOS e Android

## Fase 12: Personalização de Cores (Laranja, Branco, Preto)
- [x] Atualizar variáveis CSS no index.css
- [x] Ajustar cor primária para laranja (oklch 0.65 0.2 45)
- [x] Ajustar backgrounds para branco/preto
- [x] Atualizar botões e elementos de destaque
- [x] Testar contraste e legibilidade
- [x] Verificar consistência em todas as páginas
- [x] Atualizar gradientes para tons de laranja

## Fase 13: Redesign da Página Inicial - Manutenção Universal
- [x] Redesenhar hero section com foco em manutenção universal
- [x] Criar secção de setores atendidos (predial, industrial, comercial, hospitalar, escolar, máquinas)
- [x] Adicionar ícones representativos para cada setor
- [x] Atualizar textos e descrições para refletir versatilidade
- [x] Criar secção de funcionalidades principais (OS, Vistorias, Checklists, Relatórios)
- [x] Atualizar título da secção de features
- [x] Testar visual no browser

## Fase 14: Filtro por Setores na Página Inicial
- [ ] Tornar os cards de setores clicáveis/selecionáveis
- [ ] Adicionar estado de seleção visual (borda, cor de fundo)
- [ ] Criar mapeamento de módulos por setor
- [ ] Filtrar lista de funcionalidades baseado no setor selecionado
- [ ] Adicionar opção "Todos os Setores" para mostrar tudo
- [ ] Testar interatividade e responsividade

## Fase 15: Redesign Completo da Página Inicial - Premium
- [x] Criar novo layout premium do zero
- [x] Aplicar cores branco, laranja e preto
- [x] Incluir preço R$99,00 em destaque
- [x] Design moderno e profissional
- [x] Destacar setores atendidos (predial, industrial, comercial, hospitalar, escolar, máquinas)
- [x] Cards de setores com design premium interativo
- [x] Botões "Acessar Plataforma" e "Ver Demonstração" estilizados
- [x] Testar visual no browser

## Fase 16: Redesign Completo da Página Inicial do Zero
- [x] Manter Hero section (título, descrição, preço R$99, botões, card de setores)
- [x] Remover todo conteúdo herdado do template de condomínios
- [x] Criar nova secção de Funcionalidades (8 cards focados em manutenção)
- [x] Criar nova secção de Benefícios (lista + 4 cards)
- [x] Criar secção de Preço com card premium R$99/mês
- [x] Criar CTA final "Pronto para transformar sua gestão?"
- [x] Criar novo Footer simples e profissional
- [x] Header fixo com navegação por âncoras
- [x] Design 100% focado em gestão de manutenção universal

## Fase 17: Limpeza do Menu Lateral do Dashboard
- [x] Remover seção "Interativo / Comunidade" (Votações, Classificados, Achados e Perdidos, Caronas)
- [x] Remover seção "Documentação e Regras" (Regras e Normas, Dicas de Segurança, Links Úteis, Telefones Úteis)
- [x] Remover seção "Publicidade" (Anunciantes, Campanhas)
- [x] Remover seção "Configurações" (Perfil do Usuário, Config. Notificações, Preferências)
- [x] Remover seção "Eventos e Agenda" (Eventos, Reservas)
- [x] Remover "Vagas de Estacionamento" da seção Gestão da Organização
- [x] Mover "Agenda de Vencimentos" para seção Operacional / Manutenção
- [x] Alterar "Moradores" para "Moradores (Exclusivo p/ condomínios)"
- [x] Testar menu lateral no navegador

## Bugs Corrigidos - Fase 17
- [x] Corrigir erro de chave duplicada "revista" no menuSections do Dashboard.tsx

## Fase 18: Limpeza das Funções Rápidas
- [x] Remover "Eventos" das funções rápidas disponíveis
- [x] Remover "Votações" das funções rápidas disponíveis
- [x] Remover "Avisos" das funções rápidas disponíveis
- [x] Remover "Notificações" das funções rápidas disponíveis
- [x] Testar funções rápidas no navegador

## Fase 19: Atualização de Textos - Cadastro de Organização
- [x] Alterar "Meu Condomínio" para "Cadastro de locais e itens para manutenção"
- [x] Alterar botão "Novo Condomínio" para "Novo Local"
- [x] Testar alterações no navegador


## Fase 20: Atualização de Textos dos Cards do Dashboard
- [x] Alterar "Apps Criados" para "App de Manutenção" e "Crie seu app de manutenção personalizado"
- [x] Alterar "Revistas Criadas" para "Livro de Manutenções"
- [x] Alterar descrição de revistas para "Registre todas as manutenções para apresentar aos seus clientes e gestores"
- [x] Testar alterações no navegador


## Fase 21: Atualização da Logo do Dashboard
- [x] Copiar nova logo para pasta public
- [x] Logo já referenciada como /logo-manutencao.png (atualizada)
- [x] Testar alterações no navegador

## Fase 22: Remover Logo Duplicada
- [x] Remover segunda tag img da logo no Dashboard.tsx (desktop e mobile)
- [x] Testar alterações no navegador

## Fase 23: Atualização do Favicon
- [x] Criar favicon a partir da logo de engrenagem
- [x] Configurar favicon no index.html
- [x] Testar alterações no navegador

## Fase 24: Renomear Botão Criar Revista
- [x] Alterar "Criar Revista" para "Criar Livro" no Dashboard.tsx (4 ocorrências)
- [x] Testar alterações no navegador

## Fase 25: Atualizar Modal de Criação de Livro
- [x] Alterar "Criar Nova Revista" para "Criar Livro de Manutenções"
- [x] Alterar "Título da Revista" para "Título do Livro"
- [x] Alterar descrição do modal
- [x] Alterar botão "Criar Livro" para "Criar Livro de Manutenções"
- [x] Testar alterações no navegador

## Fase 26: Limpar Funções do Relatório
- [x] Identificar funções disponíveis no menu do sistema
- [x] Identificar funções listadas no relatório
- [x] Remover funções do relatório que não existem no menu (Avisos, Notificações, Eventos, Votações, Segurança, Comunidade, Áreas, Informações, Publicidade)
- [x] Testar alterações no navegador

## Fase 27: Adicionar Ordens de Serviço ao Relatório
- [x] Adicionar "Ordens de Serviço" ao availableSections
- [x] Testar alterações no navegador

## Fase 28: Universalizar Terminologia - Condomínio para Organização
- [x] Identificar arquivos com referências a "Condomínio" (163 referências em 20 arquivos)
- [x] Substituir referências nos arquivos do frontend (DashboardLayout, Dashboard, CondominioForm, AssistenteCriacao)
- [x] Testar alterações no navegador

## Fase 29: Renomear Revista Digital para Livro de Manutenções
- [x] Alterar "Revista Digital" para "Livro de Manutenções" no DashboardLayout.tsx
- [x] Alterar "Revista Digital" para "Livro de Manutenções" no Dashboard.tsx e AssistenteCriacao.tsx
- [x] Testar alterações no navegador

## Fase 30: Atualizar Passo 3 dos Primeiros Passos
- [x] Alterar "App, revista ou relatório" para "App, livro ou relatório"
- [x] Testar alterações no navegador

## Fase 31: Funções Simples - Sistema de Registro Rápido
### Schema e Backend
- [x] Criar tabela tarefas_simples no schema.ts
- [x] Criar tabela status_personalizados para status customizáveis
- [x] Criar rotas tRPC para CRUD de tarefas simples
- [x] Implementar geração automática de protocolo

### Frontend - Modal de Registro
- [x] Criar componente TarefasSimplesModal.tsx
- [x] Implementar design premium laranja clean
- [x] Campo título com botão "+" para salvar e adicionar
- [x] Upload de imagens (opcional)
- [x] Captura de localização automática GPS
- [x] Geração de protocolo automático
- [x] Campo descrição (opcional)
- [x] Status personalizável pelo usuário
- [x] Botão "Registrar e Adicionar Outra"
- [x] Botão "Enviar" para enviar todos os rascunhos
- [x] Salvamento automático como rascunho

### Frontend - Histórico
- [x] Criar página HistoricoTarefasSimples.tsx
- [x] Listar todas as tarefas simples
- [x] Filtro por tipo (Vistoria, Manutenção, Ocorrência, Antes/Depois)
- [x] Filtro por status
- [x] Visualização de detalhes
### Integração
- [x] Adicionar funções simples ao menu lateral
- [x] Adicionar às funções rápidas disponíveis
- [x] Integrar ao construtor de relatórios

### Exportação
- [x] Criar pasta com arquivos para exportar ao outro sistema
- [x] Documentar instruções de implementação
