# Instruções para o Site de Investimento em Pousadas

## Visão Geral
Este documento contém instruções para utilização e atualização do site de investimento em pousadas que foi desenvolvido. O site é uma landing page estática que apresenta oportunidades de investimento em pousadas, destacando os benefícios, as pousadas parceiras e o processo de investimento.

## Estrutura de Arquivos
```
pousadas_investment_site/
├── index.html           # Arquivo principal do site
├── css/
│   ├── style.css        # Estilos principais
│   └── responsive.css   # Estilos para responsividade
├── js/
│   └── main.js          # JavaScript para interatividade
└── images/             # Pasta com todas as imagens utilizadas
```

## Como Utilizar o Site

### Hospedagem
Para publicar o site online, você pode:
1. Fazer upload dos arquivos para qualquer serviço de hospedagem de sites (GoDaddy, Hostinger, Hostgator, etc.)
2. Utilizar serviços gratuitos como GitHub Pages, Netlify ou Vercel
3. Hospedar em seu próprio servidor web

### Visualização Local
Para visualizar o site localmente antes de publicá-lo:
1. Abra o arquivo `index.html` em qualquer navegador web
2. Ou inicie um servidor local com Python: `python -m http.server` na pasta do projeto

## Como Atualizar o Site

### Atualizar Textos
Para modificar os textos do site:
1. Abra o arquivo `index.html` em um editor de texto ou código (como VS Code, Sublime Text, Notepad++)
2. Localize a seção que deseja modificar
3. Altere o texto conforme necessário
4. Salve o arquivo

### Atualizar Imagens
Para substituir as imagens:
1. Prepare as novas imagens com dimensões similares às originais para manter a proporção
2. Coloque as novas imagens na pasta `images/`
3. No arquivo `index.html`, localize as tags `<img>` e atualize os atributos `src` para apontar para as novas imagens

### Atualizar Links
Para modificar os links (WhatsApp, e-mail, Booking):
1. No arquivo `index.html`, localize as tags `<a>` correspondentes
2. Atualize o atributo `href` com o novo link
3. Para o WhatsApp, use o formato: `https://wa.me/SEUNUMERO?text=MENSAGEM`
4. Para e-mail, use o formato: `mailto:SEUEMAIL`

### Atualizar Cores e Estilos
Para modificar cores, fontes e outros estilos:
1. Abra o arquivo `css/style.css`
2. Localize a seção `:root` no início do arquivo que contém as variáveis de cores
3. Altere os valores das cores conforme desejado
4. Para outras modificações de estilo, localize a seção correspondente no arquivo CSS

## Dicas e Recomendações

1. **Otimização de Imagens**: Antes de adicionar novas imagens, otimize-as para web usando ferramentas como TinyPNG ou Squoosh para melhorar o desempenho do site.

2. **Responsividade**: O site foi desenvolvido para ser responsivo em diferentes dispositivos. Ao fazer alterações, teste em diferentes tamanhos de tela para garantir que tudo continue funcionando corretamente.

3. **Backup**: Sempre faça um backup dos arquivos originais antes de realizar modificações significativas.

4. **Redes Sociais**: Os links para redes sociais no rodapé estão configurados como "#". Atualize-os com os links reais das suas redes sociais quando disponíveis.

5. **SEO**: Para melhorar o posicionamento nos mecanismos de busca, considere adicionar meta tags relevantes no cabeçalho do HTML.

## Suporte
Para qualquer dúvida ou assistência adicional com o site, entre em contato através do e-mail fornecido durante o desenvolvimento do projeto.
