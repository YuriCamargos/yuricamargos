# Calculadora de Instrumentos Industriais - Cargill AEI

Uma calculadora simples e eficiente para conversões de laço de corrente 4-20mA e calibração de instrumentos industriais.

## ✨ Funcionalidades

- **Configuração de Instrumentos**: Configure diferentes tipos de instrumentos (pressão, temperatura, vazão, nível)
- **Presets Rápidos**: Configurações predefinidas para instrumentos comuns
- **Cálculos Bidirecionais**: 
  - Processo → Corrente (4-20mA)
  - Corrente → Processo
- **Tabela de Calibração**: Geração automática de tabela com pontos de 0%, 25%, 50%, 75%, 100%
- **Exportação**: Download em formato TXT e CSV
- **Interface Responsiva**: Funciona em desktop, tablet e mobile
- **Marca Cargill**: Design profissional com cores da marca

## 🚀 Como Publicar

### GitHub Pages
1. Faça upload do arquivo `index.html` para um repositório GitHub
2. Vá em Settings → Pages
3. Selecione a branch e pasta
4. Sua calculadora estará disponível em: `https://seuusername.github.io/repositorio`

### Netlify
1. Faça upload do arquivo `index.html` para Netlify
2. Ou conecte seu repositório GitHub
3. Deploy automático em segundos

### Vercel
1. Importe o projeto do GitHub
2. Deploy automático
3. Domínio personalizado disponível

### Hospedagem Tradicional
1. Faça upload do arquivo `index.html` para qualquer servidor web
2. Acesse via browser

## 🔧 Uso

1. **Configure o Instrumento**:
   - Defina tag, tipo, faixa (min/max), unidade e precisão
   - Use presets para configurações comuns
   - Clique em "Aplicar Configuração"

2. **Realize Cálculos**:
   - Digite valor do processo para obter corrente
   - Digite corrente (4-20mA) para obter valor do processo
   - Resultados calculados automaticamente

3. **Visualize a Calibração**:
   - Tabela gerada automaticamente com pontos padrão
   - Valores precisos para cada percentual

4. **Exporte Dados**:
   - Baixe relatórios em TXT ou CSV
   - Inclui configuração e tabela de calibração

## 📋 Especificações Técnicas

- **Padrão**: Laço de corrente 4-20mA
- **Precisão**: Configurável (0-3 casas decimais)
- **Unidades Suportadas**: PSI, bar, kPa, °C, °F, GPM, LPM, m, ft
- **Compatibilidade**: Todos os navegadores modernos
- **Responsivo**: Mobile-first design

## 🎨 Personalização

O arquivo HTML contém CSS interno que pode ser facilmente modificado para:
- Alterar cores da marca
- Ajustar layout
- Adicionar novos presets
- Modificar unidades disponíveis

## 📱 Responsividade

- **Desktop**: Layout de duas colunas
- **Tablet**: Layout adaptativo
- **Mobile**: Layout de coluna única
- **Impressão**: Otimizado para tabelas de calibração

## ⚡ Performance

- **Tamanho**: ~15KB (arquivo único)
- **Carregamento**: Instantâneo
- **Offline**: Funciona sem internet após carregamento inicial
- **Sem dependências**: JavaScript vanilla, sem bibliotecas externas

## 🔒 Segurança

- **Dados locais**: Nenhum dado é enviado para servidores
- **Privacidade**: Funciona completamente no navegador
- **HTTPS**: Compatível com hospedagem segura

---

**Desenvolvido para Cargill - Time AEI**  
Calculadora profissional para instrumentação industrial
