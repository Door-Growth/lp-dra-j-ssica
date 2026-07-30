# Landing page — Dra. Jéssica Ferreira

Landing page estática em HTML5, CSS3 e JavaScript puro para gerar conversas qualificadas pelo WhatsApp sobre acompanhamento médico presencial para emagrecimento com possível uso de canetas emagrecedoras.

## Revisão atual

- Copy integralmente reescrita com progressão de desejo, dúvidas, possíveis efeitos, manutenção, método, autoridade e decisão.
- Hero com fotografia profissional da Dra. Jéssica, credenciais informadas pela cliente, CTA na primeira dobra e headline obrigatória.
- Layout inspirado na densidade de páginas modernas de saúde, adaptado à identidade verde, off-white, bege e dourado da Dra. Jéssica.
- Faixa de confiança, carrosséis de dúvidas e depoimentos, linha do tempo, apresentação médica, localização, FAQ e CTA final amplo.
- Sem depoimentos fictícios, promessas de resultado, credenciais inventadas ou endereço não confirmado.

## Estrutura

- `index.html`: conteúdo, SEO, dados estruturados e marcação acessível.
- `legal.html`: textos-base de privacidade e termos, pendentes de revisão jurídica.
- `assets/css/main.min.css`: identidade visual, componentes e responsividade consolidados e minificados.
- `assets/js/main.min.js`: WhatsApp, menu, carrossel, FAQ, animações e rastreamento minificados.
- `assets/images/jessica`: fotos reais da médica e imagem de desejo do hero.
- `assets/images/og-social.png`: arte de compartilhamento da página.
- `assets/icons`: favicon e ícone do WhatsApp.

## WhatsApp

No início de `js/script.js`, substitua `55NUMEROAQUI` pelo número real, usando somente dígitos com DDI e DDD. Todos os CTAs usam a mesma mensagem:

> Olá! Gostaria de entender como funciona o acompanhamento médico para emagrecimento com canetas e saber se essa possibilidade pode ser indicada para mim.

## Imagens

- `jessica-experience.webp`: imagem profissional usada no hero.
- `jessica-about.webp`: primeira grande apresentação da Dra. Jéssica.
- `jessica-final-cta.webp`: CTA final.

## Mensuração

O ponto de inserção do Google Tag Manager/Analytics permanece comentado no `<head>`. `window.dataLayer` recebe:

- `whatsapp_click` com `button_location`, `page_section`, `link_url` e `cta_text`;
- `faq_open` com a pergunta acionada;
- `scroll_25`, `scroll_50`, `scroll_75` e `scroll_90`.

Localizações implementadas: `header`, `hero`, `side_effects`, `maintenance`, `journey`, `doctor`, `location`, `faq`, `final_cta`, `floating_button` e `footer`.

## Validação executada

- sintaxe JavaScript;
- integridade dos arquivos e referências locais;
- IDs, âncoras e hierarquia estrutural;
- carrosséis por botões, arraste, toque e teclado;
- accordion do FAQ com o primeiro item aberto;
- links do WhatsApp em nova aba com `noopener noreferrer`;
- hero sem lazy loading e imagens inferiores com lazy loading;
- preservação integral da seção da caneta por comparação com o backup de referência.

## Informações pendentes

- número real do WhatsApp;
- CRM e RQE, se existir;
- confirmação documental das pós-graduações informadas para publicação;
- endereço completo, horários e mapa;
- Instagram e telefone;
- domínio oficial;
- revisão jurídica de privacidade e termos.
