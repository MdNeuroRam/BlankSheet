# 📝 BLANKSHEET - Sistema de Revisão com Active Recall

Um sistema web minimalista e científico para gerenciar revisões de estudo usando a técnica de **folha em branco** (active recall), baseado em evidências da ciência cognitiva.

## 🎯 O Problema

A maioria dos estudantes usa métodos passivos de revisão (reler, resumir, assistir videoaulas) que criam a **ilusão de conhecimento**. Você acha que sabe, mas na prova percebe que não consegue recuperar a informação.

## ✨ A Solução

**BLANKSHEET** não armazena flashcards digitais. Em vez disso, ele:

1. **Gerencia QUANDO você deve revisar** cada tópico
2. **Força você a usar folha em branco** de verdade
3. **Aplica espaçamento científico** (algoritmo SM-2 modificado)
4. **Avalia sua performance honesta** (sem reconhecimento falso)
5. **Ajusta intervalos automaticamente** baseado no seu desempenho

## 🧠 Por Que Folha em Branco?

A técnica de "blank sheet recall" é considerada o **método mais efetivo** de revisão porque:

- ✅ **Retrieval effort máximo** - Sem pistas visuais ou reconhecimento
- ✅ **Production effect** - Escrever à mão aumenta retenção em 30%
- ✅ **Metacognição autêntica** - Você vê exatamente o que não sabe
- ✅ **Spatial memory** - Localização espacial no papel reforça memória
- ✅ **Zero distrações** - Apenas você, papel e seu cérebro

## 🚀 Funcionalidades

### **Sistema Completo de Active Recall**
- Gerenciamento de tópicos por categoria (todas as matérias do Ensino Médio)
- Algoritmo de espaçamento SM-2 modificado
- Sistema de revisão guiado com timer
- Dicas progressivas (quando necessário)
- Auto-avaliação de performance
- Ajuste automático de intervalos baseado em desempenho

### **Dashboard Inteligente**
- 🔴 Revisões urgentes (atrasadas)
- 🟢 Próximas revisões futuras
- Estatísticas em tempo real
- Sistema de streak (dias consecutivos)

### **Análise de Desempenho**
- Retenção média por categoria
- Histórico completo de revisões
- Timeline visual de progresso
- Intervalo ótimo personalizado
- Progresso por matéria

### **Sistema de Maestria**
- Níveis: ⭐ Novato → ⭐⭐⭐⭐⭐ Mestre
- Baseado em número de revisões e intervalos
- Gamificação científica (sem elementos nocivos)

## 📊 Baseado em Ciência

O BLANKSHEET implementa técnicas comprovadas pela ciência cognitiva:

- **Testing Effect** - Recuperação ativa é superior à revisão passiva
- **Spacing Effect** - Intervalos espaçados aumentam retenção de longo prazo
- **Desirable Difficulty** - Desafio calibrado otimiza aprendizagem
- **Generation Effect** - Produzir informação (escrever) fortalece memória
- **Metacognition** - Auto-avaliação honesta calibra confiança vs. performance

## 🎨 Design

Interface minimalista inspirada em brutalismo digital:
- Sidebar preta com navegação clara
- Tipografia bold e impactante (Inter)
- Cards limpos e espaçados
- Animações sutis e profissionais
- Foco total no conteúdo, zero distrações

## 💾 Armazenamento

- **100% local** - Todos os dados salvos no `localStorage` do navegador
- **Zero servidor** - Funciona completamente offline
- **Privacidade total** - Seus dados nunca saem do seu computador
- **Portátil** - Um único arquivo HTML

## 🛠️ Tecnologias

- HTML5
- CSS3 (Vanilla, sem frameworks)
- JavaScript (Vanilla ES6+)
- LocalStorage para persistência
- Google Fonts (Inter)

## 📖 Como Usar

1. **Baixe o arquivo** `blanksheet-v2.html`
2. **Abra no navegador** (qualquer navegador moderno)
3. **Adicione tópicos** que você estudou
4. **Revise quando o sistema avisar**
5. **Use folha em branco real** - escreva tudo que lembra
6. **Avalie sua performance honestamente**
7. **O sistema ajusta os intervalos automaticamente**

### Exemplo de Fluxo:
```
Segunda, 8h: Estudo "Ciclo de Krebs" por 1h
           → Adiciono no BlankSheet
           → Sistema agenda: revisar amanhã

Terça, 8h:  Notificação de revisão
           → Pego papel e caneta
           → Escrevo tudo que lembro (20min)
           → Comparo com material
           → Marco: 80% de acerto
           → Sistema agenda: próxima em 3 dias

Sexta, 8h:  2ª revisão: 90% acerto
           → Próxima em 7 dias

Continua até consolidação (90+ dias)
```

## 🎓 Para Quem é Este Projeto?

- **Vestibulandos** preparando ENEM, vestibulares
- **Concurseiros** estudando para concursos públicos
- **Estudantes de medicina** (residência médica)
- **Estudantes de direito** (OAB, concursos)
- **Qualquer pessoa** que quer aprender com eficiência científica

## ⚠️ O Que Este Projeto NÃO É

- ❌ Um Anki alternativo (não usa flashcards digitais)
- ❌ Um gerador de resumos automáticos
- ❌ Um substituto para estudo ativo inicial
- ❌ Uma forma de "estudar mais rápido" (é sobre estudar MELHOR)

## 🤝 Contribuindo

Contribuições são bem-vindas! Áreas de interesse:

- [ ] Modo dark/light toggle
- [ ] Exportação de dados (JSON, CSV)
- [ ] Gráficos de evolução mais elaborados
- [ ] Sistema de tags para tópicos relacionados
- [ ] Integração com Google Calendar
- [ ] App mobile (PWA)
- [ ] Análise preditiva (quando estará pronto para prova)

## 📄 Licença

MIT License - Use livremente, mas mantenha os créditos!

## 🙏 Agradecimentos

Inspirado por:
- Pesquisas de Henry Roediger sobre Testing Effect
- Herman Ebbinghaus e a Curva do Esquecimento
- Piotr Woźniak (criador do algoritmo SM-2 do SuperMemo)
- Barbara Oakley e "Learning How to Learn"

## 📚 Referências Científicas

- Roediger, H. L., & Karpicke, J. D. (2006). Test-enhanced learning: Taking memory tests improves long-term retention.
- Dunlosky, J., et al. (2013). Improving Students' Learning With Effective Learning Techniques.
- Mueller, P. A., & Oppenheimer, D. M. (2014). The Pen Is Mightier Than the Keyboard.

---

**Feito com 🧠 para estudantes que querem dominar, não apenas passar.**

*"A ilusão de conhecimento é o maior inimigo do aprendizado real."*
