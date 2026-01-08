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
