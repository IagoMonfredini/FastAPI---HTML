# FastAPI + HTML  
Projeto de exemplo utilizando FastAPI para servir HTML e assets estáticos.

## Visão geral  
Neste repositório você encontrará uma aplicação em Python que utiliza o framework FastAPI para entregar diretamente páginas HTML e arquivos estáticos (CSS, JS, imagens). Ideal para aprender como integrar templates e assets em uma API web leve.

## Estrutura do projeto  
├── main.py # arquivo principal da aplicação
├── requirements.txt # dependências do Python
├── templates/ # diretório com arquivos HTML (templates)
├── static/ # diretório com arquivos estáticos (CSS, JS, imagens)
└── .gitignore # padrões de arquivos a ignorar

markdown
Copiar código

## Funcionalidades  
- Roda server FastAPI com endpoints que entregam páginas HTML.  
- Renderização de templates (usando mecanismo de template do FastAPI / Starlette).  
- Servir arquivos estáticos da pasta `static/` (estilos, scripts, imagens).  
- Exemplo de uso básico pronto para ser estendido.

## Começando  
### Pré-requisitos  
- Python 3.8 ou superior.  
- Ambiente virtual (recomendado).  

### Instalação  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/IagoMonfredini/FastAPI---HTML.git
   cd FastAPI---HTML
Crie e ative um ambiente virtual (exemplo com venv):

bash
Copiar código
python -m venv venv
source venv/bin/activate    # no Linux/macOS  
venv\Scripts\activate       # no Windows  
Instale as dependências:

bash
Copiar código
pip install -r requirements.txt
Executando a aplicação
bash
Copiar código
uvicorn main:app --reload
Depois acesse no navegador: http://127.0.0.1:8000
Você deve ver a página HTML inicial e os assets estáticos funcionando.

Personalização
Edite os arquivos HTML na pasta templates/ para alterar conteúdo.

Adicione ou modifique arquivos em static/ para ajustar estilo, scripts ou imagens.

Acrescente rotas no main.py para novas páginas ou APIs conforme necessário.

Por que usar o FastAPI para servir HTML?
Embora o FastAPI seja muito usado para APIs JSON, ele também permite servir HTML e arquivos estáticos de forma simples — como descrito na sua documentação de resposta HTML. 
fastapi.tiangolo.com
+2
fastapi.tiangolo.com
+2
 Isso o torna uma boa escolha para aplicações leves ou microsites que combinam backend API e front-end simples.

Contribuições
Contribuições são bem-vindas! Se você quiser adicionar funcionalidades, corrigir bugs ou melhorar a documentação:

Fork o repositório

Crie um branch (git checkout -b minha‐feature)

Commit suas mudanças (git commit -m 'Adiciona nova página HTML')

Push para o branch (git push origin minha‐feature)

Abra um Pull Request aqui no repositório original.

Licença
Este projeto está sob a MIT ou outra licença conforme sua preferência — ajuste se necessário.

Professora Luci: se quiser, posso gerar também um documento PDF ou versão em português mais formal para apresentação.

yaml
Copiar código

---

Se quiser, posso formatar também com **badges** (por exemplo build, cobertura de testes), ou adicionar **screenshots** da interface. Você gostaria dessa versão ampliada?
::contentReference[oaicite:2]{index=2}
