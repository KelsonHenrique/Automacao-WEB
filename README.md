# Automação-WEB
Neste projeto, utilizamos Python para realizar automação na web, empregando as bibliotecas Selenium e Webdriver como ferramentas fundamentais para essa finalidade. Explore conosco a eficiência dessa abordagem! 🚀

## Habilidades Desenvolvidas
A proposta do projeto é automatizar o preenchimento dos campos de nome, e-mail e contato em uma tela de cadastro disponível no link: https://pages.hashtagtreinamentos.com/inscricao-minicurso-python-automacao-org?origemurl=hashtag_yt_org_minipython_8AMNaVt0z_M

![image](https://github.com/KelsonHenrique/Automacao-WEB/assets/141082201/f455df36-50b1-458e-a171-b76c7a9afc5a)

- Gostaria de chamar atenção para o seguinte comando:

```
  servico = Service(ChromeDriverManager().install())
```
  Com ele, podemos identificar a versão do Chrome e instalar o ChromeDriver correspondente

 ```
navegador = webdriver.Chrome(service=servico)
```
Utilizando "service=servico" como argumento, evitaremos a necessidade de baixar o chromedriver manualmente.


## Como executar esse projeto 

- Instale Python versão 3.10.7;
- Instale o Anaconda para obter o Jupyter Notebook na sua máquina;
- Use o prompt de comando do Anaconda para instalar o Selenium e o Webdriver Manager;
```
pip install selenium
```
```
pip install webdriver-manager
```
O uso do Webdriver Manager evita a necessidade de atualizar o webdriver sempre que ocorrer uma atualização no navegador

- Para um melhor uso da biblioteca Selenium, recomendo acessar o site: https://selenium-python.readthedocs.io/getting-started.html

