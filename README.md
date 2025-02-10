
# Clima Agora 🌤️

Este projeto é uma aplicação web que permite aos usuários consultar as condições climáticas atuais e a previsão do clima para os próximos dias em qualquer cidade. A interface é moderna, com um design suave de pôr do sol e a capacidade de compartilhar as informações de clima via WhatsApp.

## Funcionalidades

- **Consulta de clima atual:** O usuário pode digitar o nome da cidade para obter as condições climáticas atuais, como temperatura, sensação térmica, vento, umidade, nascer e pôr do sol.
- **Previsão do clima:** Exibe a previsão do tempo para os próximos dias com detalhes de temperatura e condições.
- **Compartilhamento no WhatsApp:** Permite que o usuário compartilhe as informações climáticas em um link direto para o WhatsApp.
- **Ajuste de fonte:** O usuário pode aumentar ou diminuir o tamanho da fonte das informações de clima após a busca.
- **Design moderno e responsivo:** A interface se adapta a dispositivos móveis e de desktop com cores suaves e interativas.

## Tecnologias Usadas

- **HTML5**
- **CSS3** (para o design e estilo)
- **JavaScript** (para interação e integração com a API)
- **API OpenWeatherMap** (para buscar dados climáticos)

## Como Usar

1. Clone ou baixe o repositório em seu computador:
   ```bash
   git clone https://github.com/joaoricardobr/climatempo-.git
   ```

2. Abra o arquivo `index.html` no seu navegador.

3. Digite o nome da cidade no campo de busca e clique em "🔍 Buscar Clima" para obter as informações climáticas.

4. O clima atual, junto com a previsão dos próximos dias, será exibido na tela. Você poderá ajustar o tamanho da fonte usando os botões de aumento e diminuição e compartilhar os dados no WhatsApp clicando no botão "📲 Compartilhar no WhatsApp".

## Chave da API

Este projeto usa a API pública da OpenWeatherMap. Para usá-la, você precisará de uma chave API pessoal. Para obter a chave, siga as etapas abaixo:

1. Acesse o site da [OpenWeatherMap](https://openweathermap.org/).
2. Registre-se ou faça login.
3. Gere sua chave de API.
4. Substitua a chave no código, dentro da variável `API_KEY` no arquivo `index.html`.

## Personalização

- **Alterar a chave da API:** No código, localize a linha onde a chave da API é definida (variável `API_KEY`) e substitua pela sua chave pessoal obtida no passo acima.
- **Alterar o design e cores:** Você pode personalizar as cores e o layout do site editando as regras CSS no arquivo `index.html`.

## Contribuição

Se você quiser contribuir para o projeto, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma nova branch (`git checkout -b minha-nova-feature`).
3. Faça suas modificações.
4. Commit e envie suas mudanças para a branch (`git commit -am 'Adicionando uma nova feature'` e `git push origin minha-nova-feature`).
5. Abra um pull request para revisão.

## Créditos

- **Desenvolvedor:** João Ricardo (@joaoricardo.pe)
- **Fonte da API:** [OpenWeatherMap](https://openweathermap.org/)
- **Design e desenvolvimento do site:** Criado por João Ricardo, engenheiro de computação, Instagram [@joaoricardo.pe](https://www.instagram.com/joaoricardo.pe/)
```

### Estrutura do Repositório

- **`index.html`:** Arquivo principal da aplicação.
- **`README.md`:** Este arquivo, contendo todas as informações sobre o projeto.
- **Outros arquivos:** Pasta de imagens, CSS, JavaScript e outros recursos necessários.

### Observações

- Certifique-se de substituir `https://github.com/joaoricardobr/climatempo-.git` pelo link correto do seu repositório.
- Se houver outras pastas ou arquivos importantes no projeto, inclua uma seção **"Estrutura do Repositório"** para descrevê-los.
