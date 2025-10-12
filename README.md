![poster](./.github/poster.png)

## Sobre

Repositório do treinamento: Testes contínuos em Robot Framework no Github Actions

## Techs
- Robot Framework
- Browser (Playwright)
- Python

## Como executar

1. Clonar o repositório, instalar as dependências
```
pip install -r requirements.txt
```

2. Configura os navegadores do Playwright para o Robot Framework Browser.
```
rfbrowser init        
```

3. Executar testes em Headless
```
robot -d ./logs -v IS_HEADLESS:True tests
```

4. Executar testes em modo assistido
```
robot -d ./logs -v IS_HEADLESS:False tests
```

<hr>
Curso disponível em https://qax.com.br

