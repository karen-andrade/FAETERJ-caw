# 🔬 Flashcards Científicos - Combata a Pseudociência

Projeto web educativo para matéria CAW-2° período FAETERJ desenvolvido com HTML5, CSS3 e JavaScript puro para ensinar pensamento crítico e distinguir ciência de pseudociência através de flashcards interativos.

## 📋 Sobre o Projeto

Este é um mini-projeto educacional que funciona 100% no navegador, sem necessidade de backend ou dependências externas. O objetivo é combater a pseudociência através de um sistema interativo de flashcards que apresenta afirmações científicas para o usuário classificar como **Fato** ou **Mito**.

### Funcionalidades

- ✅ 6 flashcards sobre temas científicos importantes
- 🔄 Animação de flip 3D ao clicar no card
- 🎯 Sistema de classificação Fato/Mito
- 📊 Barra de progresso visual
- 📈 Contador de acertos e tentativas
- ⬅️➡️ Navegação entre cards (anterior/próximo)
- 🎨 Design minimalista e responsivo
- 📱 Funciona perfeitamente em mobile

## Critérios Atendidos

- [x] Funciona localmente sem erros no console
- [x] Código organizado e comentado
- [x] Interface compreensível e educacional
- [x] Apenas recursos nativos (sem frameworks)
- [x] Estrutura HTML5 semântica
- [x] Estilização CSS3 moderna
- [x] Interatividade JavaScript pura
- [x] Layout responsivo
- [x] Objetivo educacional claro

## Como Executar

### Opção 1: Abrir Diretamente
1. Baixe todos os arquivos do projeto
2. Extraia o arquivo ZIP em uma pasta
3. Abra o arquivo `index.html` em qualquer navegador moderno
4. Pronto! O projeto está funcionando

### Opção 2: Servidor Local (Opcional)
```bash
# Se tiver Python instalado:
python -m http.server 8000

# Ou com Node.js e npx:
npx serve

# Depois acesse: http://localhost:8000
```

## 📁 Estrutura do Projeto

```
flashcards-cientifico/
│
├── index.html          # Estrutura HTML da página
├── style.css           # Estilos e animações
├── script.js           # Lógica e interatividade
└── README.md           # Este arquivo
```

## 🎨 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página
- **CSS3**: Estilização, gradientes e animação flip 3D
- **JavaScript (ES6+)**: Lógica, manipulação DOM e interatividade

## Temas Abordados

1. Vacinas e autismo (mito comum)
2. Idade da Terra (fato científico)
3. Uso do cérebro humano (mito dos 10%)
4. Antibióticos vs vírus (conceito importante)
5. Mudança climática (consenso científico)
6. Hereditariedade e DNA (nuances científicas)

## Como Usar

1. **Leia a afirmação** apresentada no card
2. **Clique em "Fato" ou "Mito"** para responder
3. **Veja a explicação** científica no verso do card
4. **Navegue** com os botões Anterior/Próximo
5. **Acompanhe** seu progresso e acertos

## Funcionalidades Técnicas

### Animação Flip 3D
```css
transform-style: preserve-3d;
transition: transform 0.6s ease;
transform: rotateY(180deg);
```

### Array de Dados
```javascript
const flashcardsData = [
    {
        afirmacao: "...",
        resposta: "fato" | "mito",
        explicacao: "..."
    }
];
```

### Sistema de Progresso
- Barra visual animada
- Contador de cards (ex: 2/6)
- Estatísticas de acertos

##  Objetivo Educacional

O projeto visa:
- Desenvolver pensamento crítico
- Ensinar a distinguir ciência de pseudociência
- Apresentar fatos científicos importantes
- Combater desinformação
- Promover literacia científica

## Personalização

Para adicionar novos flashcards, edite o array `flashcardsData` no arquivo `script.js`:

```javascript
{
    afirmacao: "Sua afirmação aqui",
    resposta: "fato",  // ou "mito"
    explicacao: "Explicação científica detalhada aqui..."
}
```

## 📝 Notas de Desenvolvimento

- **Compatibilidade**: Testado em Chrome, Firefox, Safari e Edge
- **Responsivo**: Funciona em telas de 320px até 1920px+
- **Acessibilidade**: Semântica HTML adequada
- **Performance**: Sem dependências externas, carrega instantaneamente
- **Código limpo**: Comentários em português, funções bem documentadas

## Autor

**Karen Andrade**  
Projeto desenvolvido para fins educacionais  
Disciplina: Desenvolvimento Web

## Licença

Este projeto é de código aberto para fins educacionais.

---
