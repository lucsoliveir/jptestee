# FitConsult Admin Dashboard

Sistema administrativo completo para consultoria online de treinos, performance e acompanhamento físico.

## 🔑 Acesso ao Painel Admin

**Para acessar o painel administrativo:**
1. Abra o arquivo `admin.html` no seu navegador
2. Isso redirecionará automaticamente para a tela de login
3. Digite a senha `jppoubel01`
4. Clique em "Entrar no Painel"

**Fluxo de acesso:**
```
admin.html → login.html (senha: jppoubel01) → dashboard.html
```

⚠️ **Importante:** O site principal (`jp\joao-pedro-treinamento-consultoria (6).html`) **NÃO foi alterado** conforme solicitado. O painel admin é um sistema separado acessível via `admin.html`.

## 💾 Armazenamento de Dados Persistente

Este sistema utiliza **LocalStorage** do navegador para armazenar todos os seus dados de forma **persistente e segura**:

- ✅ **Dados salvos permanentemente** no seu navegador até que você os exclua explicitamente
- ✅ **Nenhum dado é enviado para servidores externos** - total privacidade
- ✅ **Funciona totalmente offline** após o carregamento inicial
- ✅ **Backup e restauração** disponíveis nas Configurações
- ✅ **Versionamento de dados** para evitar perdas acidentais

### 📁 O que é salvo:
- Cadastro completo de alunos com histórico
- Treinos personalizados e bibliotecas de exercícios
- Avaliações físicas e medidas corporais
- Agendamentos e frequência
- Pagamentos e controle financeiro
- Notificações e configurações do sistema
- Histórico completo de todas as alterações

## 🔄 Integração Total de Dados

O sistema implementa **integração total** - toda ação em uma módulo atualiza automaticamente os dados relacionados em todo o sistema:

- **Ao criar uma avaliação:** 
  → Atualiza última avaliação do aluno
  → Adiciona registro no histórico
  → Atualiza gráficos de evolução
  → Verifica e remove alertas de avaliação atrasada
  → Atualiza o dashboard em tempo real

- **Ao processar um pagamento:**
  → Atualiza status financeiro do aluno
  → Atualiza dashboard financeiro
  → Remove alertas de pagamento pendente
  → Atualiza projeções de receita

- **Ao atualizar um treino:**
  → Registra alteração no histórico com versionamento
  → Mantém versão anterior disponível para consulta
  → Notifica o sistema de evolução da mudança
  → Atualiza o perfil do aluno em tempo real

## 📋 Funcionalidades Principais

### Dashboard Principal
- Visão geral rápida dos indicadores-chave em tempo real
- Alertas importantes com filtros e marcação como lida
- Agenda do dia com visualização por horário
- Gráficos interativos de desempenho e tendências

### Gestão de Alunos
- Cadastro completo com foto, dados pessoais, objetivos e planos
- Histórico cronológico detalhado de todas as interações
- Controle integrado de treinos, avaliações, pagamentos e agendamentos
- Sistema de metas individuais com acompanhamento de progresso

### Treinos e Exercícios
- Criação e gerenciamento de treinos personalizados
- Biblioteca de exercícios com grupos musculares
- Controle de séries, repetições, carga, descanso e Tempo
- Arraste e solte para reorganizar exercícios
- Sistema de versionamento com histórico completo
- Treinos associados a alunos específicos

### Avaliações e Evolução
- Registro completo de avaliações com medidas, IMC, % de gordura
- Gráficos de evolução em diferentes períodos (30d, 3m, 6m, 12m)
- Comparação visual ANTES × DEPOIS com fotos (conceito)
- Sistema de metas individuais com alertas de conquista
- Histórico timestamped de todas as alterações

### Financeiro
- Controle de planos, valores, vencimentos e formas de pagamento
- Dashboard financeiro com receitas, inadimplência e projeções
- Alertas automáticos para pagamentos atrasados e vencimentos próximos
- Histórico detalhado de todas as transações com IDs únicos
- Integração automática com status financeiro do aluno

### Agenda
- Calendário integrado com visualização dia/semana/mês
- Agendamento de consultorias, avaliações, revisões e outros tipos
- Lembretes e notificações automáticas configuráveis
- Integração com perfil do aluno (1-click para ver detalhes)
- Confirmação, reagendamento e cancelamento de atendimentos

### Relatórios
- Relatórios financeiros detalhados por aluno e período
- Relatórios de evolução com comparações e tendências
- Relatórios de frequência e taxa de comparecimento
- Exportação de dados em formato JSON para backup ou análise externa
- Filtros avançados por aluno, período, tipo e status

### Configurações
- Preferências de notificações (tipos e frequência)
- Controle total sobre backup e restauração de dados
- Informações do sistema e versão
- Opção segura para limpar todos os dados (com confirmação)

## 🛠️ Tecnologias Utilizadas

- HTML5 Semântico
- CSS3 Moderno (Flexbox, Grid, Animations, Variáveis CSS)
- JavaScript Vanilla (ES6+) com modularidade
- LocalStorage para armazenamento persistente de dados
- Font Awesome 6 para ícones
- Design Responsivo (Mobile-first)

## 🎨 Características do Design Premium

- Tema escuro profissional com tons de cobre e azul
- Interface limpa, moderna e de fácil navegação
- Cards elevados com sombras suaves e efeitos de hover
- Microanimações sutis para feedback visual imediato
- Tipografia hierárquica e legível em todos os dispositivos
- Ícones significativos e consistentes em todo o sistema
- Totalmente responsivo para todos os tamanhos de tela
- Indicadores de loading, estados vazios e feedback visual

## 📱 Responsividade Completa

O painel se adapta perfeitamente a:
- **Desktop** (≥1024px): barra lateral fixa, layout em grid otimizado
- **Tablet** (<1024px): barra lateral reduzida para ícones com tooltips
- **Smartphone** (<768px): menu hambúrguer, layout em coluna única
- Todos os componentes se reorganizam automaticamente para melhor UX
- Gráficos e tabelas adaptam-se sem perder funcionalidade
- Touch-friendly com áreas de clipe adequadas para dispositivos móveis

## 💡 Próximos Passos Para Você

1. **Teste o sistema:** Abra `admin.html` e use senha `jppoubel01`
2. **Explore as funcionalidades:** Navegue entre os diferentes módulos
3. **Adicione seus dados:** Comece cadastrando seus alunos reais
4. **Faça backup:** Use a opção de exportação em Configurações para salvar seus dados
5. **Use diariamente:** O sistema é projetado para uso profissional contínuo

## 🔒 Segurança e Privacidade

- **Dados locais:** Nenhum dado deixa seu navegador ou computador
- **Sem servidores externos:** Funciona 100% offline após carregamento
- **Backup sob seu controle:** Você decide quando e onde salvar seus dados
- **Nenhum rastreamento:** Sem cookies de terceiros ou analytics externos
- **Total propriedade:** Você é o único dono dos seus dados

## 📞 Suporte e Manutenção

Este sistema foi projetado para ser usado como uma ferramenta profissional de gestão. Para garantir o melhor desempenho:

- **Backups regulares:** Exporte seus dados semanalmente ou após alterações significativas
- **Atualizações:** Se houver melhorias futuras, basta substituir os arquivos HTML/JS/CSS
- **Compatibilidade:** Funciona em qualquer navegador moderno (Chrome, Firefox, Safari, Edge)
- **Recuperação:** Se algo der errado, restaure a partir do seu backup exportado

---

**Desenvolvido com foco em segurança de dados, usabilidade profissional e integração total para profissionais de educação física e consultoria de desempenho.**

> 💡 **Dica profissional:** Faça o backup dos seus dados antes de fazer alterações significativas e armazene o arquivo de backup em local seguro (ex: serviço de nuvem, HD externo).

© 2026 FitConsult - Sistema de Gestão para Consultoria de Performance Física