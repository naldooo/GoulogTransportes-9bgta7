# GOULOG Transportes - Site Reescrito

## 📋 Descrição

Site completamente reescrito e independente do Onspace. Versão moderna, responsiva e otimizada com HTML5, CSS3 (Tailwind) e JavaScript vanilla.

## ✨ Características

### ✅ Removido
- ❌ Todas as dependências do Onspace
- ❌ URLs externas para CDN do Onspace
- ❌ Qualquer integração com plataforma Onspace

### ✅ Implementado
- 🎨 Design moderno e responsivo
- 📱 Mobile-first approach
- ⚡ Animações suaves (scroll reveal, contadores, etc)
- 🖼️ Galeria de imagens com lightbox
- 📧 Formulário de contato com integração WhatsApp
- 🔍 SEO otimizado
- 📊 Contadores animados
- 🌙 Tema escuro profissional
- 🎯 Navegação entre páginas (SPA-like)
- 📞 Botão WhatsApp flutuante
- 🚀 Performance otimizada

## 📁 Estrutura de Arquivos

```
/
├── index.html                 # Arquivo principal (1186 linhas)
├── truck-front.jpg           # Imagem: Scania R450 frontal
├── truck-tanker-side.jpg     # Imagem: Tanque lateral
├── truck-tanker-detail.jpg   # Imagem: Detalhe do tanque
├── truck-hero.jpg            # Imagem: Hero background
├── truck-tanker.jpg          # Imagem: Tanque completo
├── warehouse.jpg             # Imagem: Galpão/infraestrutura
└── README.md                 # Este arquivo
```

## 🎨 Seções do Site

### 1. **Página Inicial (Home)**
- Hero section com call-to-action
- Estatísticas animadas (20+ anos, 50+ conjuntos, etc)
- Seção "Quem Somos"
- Galeria de frota
- Preview de serviços
- Certificação SASSMAQ
- CTA final

### 2. **Página de Serviços**
- Descrição detalhada dos 3 serviços principais:
  - Cargas Químicas
  - Cargas Perigosas
  - Logística Rodoviária
- Diferenciais da empresa
- CTA para contato

### 3. **Página de Contato**
- Informações de contato (WhatsApp, telefones, emails)
- Formulário de contato funcional
- Integração automática com WhatsApp
- Máscara de telefone

### 4. **Footer**
- Links rápidos
- Redes sociais
- Informações de contato
- Links legais

## 🚀 Como Usar

### Localmente
```bash
# Opção 1: Python
python3 -m http.server 8000

# Opção 2: Node.js
npx http-server

# Opção 3: Abrir direto no navegador
# Duplo clique no index.html
```

### Deploy na Netlify
1. Conecte o repositório GitHub
2. Configure a build:
   - Build command: (deixe em branco)
   - Publish directory: `/` (raiz)
3. Deploy automático em cada push

### Deploy em Servidor
```bash
# Copiar todos os arquivos para o servidor
scp -r ./* usuario@servidor:/var/www/goulog/

# Ou via Git
git clone https://github.com/naldooo/GoulogTransportes-9bgta7.git
cd GoulogTransportes-9bgta7
# Servir com nginx, apache, etc
```

## 🎯 Funcionalidades JavaScript

### Navegação
- Sistema de páginas (SPA-like)
- Menu mobile responsivo
- Scroll suave

### Animações
- Scroll reveal (fade-up, fade-left, fade-right)
- Contadores animados com easing
- Hover effects em cards
- Transições suaves

### Interatividade
- Formulário de contato com validação
- Máscara de telefone automática
- Galeria com lightbox
- Navegação por teclado (setas, Esc)
- WhatsApp integrado

### Performance
- Lazy loading de imagens
- CSS otimizado com Tailwind
- Sem dependências externas (exceto Tailwind CDN e Font Awesome)
- Minificação automática possível

## 🎨 Cores e Branding

```css
Vermelho GOULOG: #D72323
Vermelho Escuro: #B01B1B
Preto Principal: #0D0D0D
Cinza: #6B7280
```

## 📱 Responsividade

- ✅ Mobile (320px+)
- ✅ Tablet (768px+)
- ✅ Desktop (1024px+)
- ✅ Large screens (1280px+)

## 🔗 Links Importantes

- **GitHub**: https://github.com/naldooo/GoulogTransportes-9bgta7
- **Netlify**: https://goulogsiteteste.netlify.app/
- **WhatsApp**: https://api.whatsapp.com/send?phone=5513996863512

## 📞 Contatos

- **WhatsApp**: (13) 99686-3512
- **Telefone Diretor (Sérgio)**: (13) 99742-7526
- **Telefone Comercial (Alex)**: (13) 99689-3512
- **Email**: comercial@goulogtransportes.com.br

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Tailwind CSS (CDN)
- **JavaScript** - Vanilla JS (sem frameworks)
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia (Barlow)

## 📝 Notas de Desenvolvimento

### Vantagens da Nova Versão
1. ✅ Totalmente independente
2. ✅ Sem dependências externas críticas
3. ✅ Carregamento mais rápido
4. ✅ Código limpo e bem organizado
5. ✅ Fácil de manter e atualizar
6. ✅ Imagens locais (melhor performance)
7. ✅ SEO otimizado

### Possíveis Melhorias Futuras
- [ ] Adicionar backend para formulário (Node.js/Python)
- [ ] Integrar analytics (Google Analytics)
- [ ] Adicionar blog/notícias
- [ ] Sistema de agendamento
- [ ] Chat ao vivo
- [ ] Versão em inglês/espanhol
- [ ] PWA (Progressive Web App)
- [ ] Otimização de imagens (WebP)

## 📄 Licença

Propriedade de GOULOG Transportes © 2024

## 👨‍💻 Desenvolvedor

Reescrita e modernização: 2024

---

**Versão**: 2.0 (Reescrita Completa)  
**Data**: Maio de 2024  
**Status**: ✅ Produção
