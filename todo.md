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
