# 📅 Sistema de Planejamento Semanal e Rotas

Um sistema completo para organizar sua rotina semanal com visualização de rotas diárias e gestão de tempo.

## 🎯 Características

### Planejamento Semanal
- **Interface em abas** - Um dia por vez para melhor foco
- **Edição inline** - Clique para editar qualquer atividade
- **Auto-preenchimento** - Títulos automáticos baseados no tipo
- **Cores consistentes** - Sistema de cores unificado
- **Estatísticas diárias** - Resumo de atividades e horários
- **Persistência local** - Salva automaticamente no navegador

### Mapa de Rotas Diário
- **Visualização por dia** - Mapa específico para cada dia da semana
- **Timeline interativo** - Horários e durações claras
- **Cálculo automático** - Tempos de deslocamento e intervalos
- **Rotas visuais** - Conexões claras entre atividades
- **Estatísticas** - Tempo total gasto em cada categoria

## 🚀 Como Usar

### Instalação Local
1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/planejamento-semanal.git
cd planejamento-semanal
```

2. Abra os arquivos HTML no navegador:
- `planejamento-semanal.html` - Sistema de planejamento com abas
- `mapa-rotas-timeline.html` - Visualização de rotas com timeline

### Estrutura do Projeto
```
planejamento-semanal/
├── README.md
├── planejamento-semanal.html
├── mapa-rotas-timeline.html
├── data/
│   └── exemplo-config.json
└── docs/
    └── manual-usuario.md
```

## 💾 Salvamento e Backup

### Local Storage
- Os dados são salvos automaticamente no navegador
- Use o botão "Exportar" para fazer backup em JSON

### Formato de Dados
```json
{
  "segunda": [
    {
      "time": "06:30 - 07:00",
      "name": "Passeio 🐕",
      "type": "passeio"
    }
  ]
}
```

## 🎨 Personalização

### Tipos de Atividade
- **Passeio** - #9f7aea
- **Café** - #ed8936
- **Trabalho CRAS** - #4299e1
- **Atendimento** - #48bb78
- **Musculação** - #f56565
- **Muay Thai** - #38b2ac
- **Dança** - #ed64a6
- **Funcional** - #ecc94b
- **Descanso** - #cbd5e0
- **Lazer** - #b794f4
- **Sono** - #718096
- **Transporte** - #a0aec0

## 📱 Compatibilidade

- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablet (iPad, Android Tablets)
- ✅ Mobile (iOS, Android)

## 🔄 Atualizações Futuras

- [ ] Sincronização na nuvem
- [ ] Notificações e lembretes
- [ ] Integração com calendário
- [ ] Modo escuro
- [ ] Relatórios semanais/mensais
- [ ] Compartilhamento de rotinas
- [ ] App mobile nativo

## 🤝 Contribuindo

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👤 Autora

Desenvolvido com 💜 para organização pessoal e bem-estar.

## 🙏 Detalhes

- Ícones por Emoji
- Inspirado na necessidade de equilibrar vida pessoal e profissional
- Desenvolvido com ajuda do Claude (Anthropic)

---

**Nota:** Este é um projeto pessoal em desenvolvimento contínuo. Sugestões são sempre bem-vindas!
