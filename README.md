# 🌾 Loja Camda

Site de e-commerce para produtos da empresa **Camda** - fabricante de rações animais.

## 📋 Sobre

Este projeto apresenta uma loja online estática para comercialização de rações para:
- 🐄 Bovinos (Corte e Leite)
- 🐴 Equinos
- 🐑 Ovinos

## 🎯 Características

✅ **Produtos** - Catálogo de 10 produtos com descrição e preço  
✅ **Carrinho de Compras** - Funcional com adição e remoção de itens  
✅ **Design Responsivo** - Adapta-se a diferentes tamanhos de tela  
✅ **Segurança** - Validação de input e proteção contra XSS  
✅ **Sem Dependências** - HTML, CSS e JavaScript puro  

## 🔒 Segurança

Este site inclui proteções de segurança:

- ✅ **Validação de Input** - Nome e preço validados
- ✅ **Sanitização** - Remoção de caracteres perigosos
- ✅ **CSP Headers** - Content Security Policy configurado
- ✅ **Proteção XSS** - Uso seguro de DOM (textContent vs innerHTML)
- ✅ **Limites** - Máximo de 50 itens por carrinho
- ✅ **Tratamento de Erros** - Feedback seguro ao usuário

**⚠️ Nota Importante:** Este é um protótipo frontend. Para produção com pagamentos reais:
1. Implemente um backend seguro com validação servidor-side
2. Configure HTTPS obrigatório
3. Implemente autenticação e autorização
4. Use um gateway de pagamento certificado
5. Adicione rate limiting e WAF

## 🚀 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/venerandodasilvawesley-debug/camda-site.git
cd camda-site
```

2. Abra `index.html` em um navegador moderno:
```bash
# Linux/macOS
open index.html

# Windows
start index.html
```

3. Navegue pelos produtos e adicione ao carrinho

## 📁 Estrutura

```
camda-site/
├── index.html              # Página principal
├── logo.png               # Logo da marca
├── aniversario.png        # 60 anos Camda
├── inicio.png             # Background dos produtos
├── logocartao.png         # Ícones de pagamento
├── segurancacartao.png    # Badge de segurança
├── pix.png                # Ícone PIX
├── README.md              # Este arquivo
└── .gitignore            # Arquivos ignorados pelo Git
```

## 🛠️ Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Grid layout responsivo
- **JavaScript ES6** - Carrinho com validação

## 📝 Melhorias Futuras

- [ ] Backend com Node.js/Express para persistência
- [ ] Banco de dados para gerenciar produtos
- [ ] Autenticação de usuários (JWT)
- [ ] Integração com gateway de pagamento
- [ ] Sistema de pedidos e histórico
- [ ] Painel administrativo
- [ ] Multi-idioma (PT/EN)
- [ ] Notificações por email

## 🔍 Melhorias de Segurança (v1.1)

**Adicionado em 26/03/2026:**
- ✅ Content Security Policy (CSP)
- ✅ Headers de segurança (X-Frame-Options, X-Content-Type-Options)
- ✅ Validação rigorosa de inputs
- ✅ Sanitização de dados
- ✅ Limite de itens no carrinho (50)
- ✅ Preço mínimo (R$ 0,01) e máximo (R$ 999.999,99)
- ✅ ID único para cada item (facilita deleção)
- ✅ Botão para remover itens
- ✅ Feedback ao usuário (erros e sucesso)
- ✅ Proteção contra manipulação via console

## 📄 Licença

Este projeto é propriedade da empresa Camda.

## 📧 Suporte

Para dúvidas ou sugestões sobre o site, entre em contato com a equipe de TI.

---

**Versão:** 1.1  
**Última atualização:** 26 de março de 2026  
**Segurança:** Score 6/10 (MVP com proteções básicas)
