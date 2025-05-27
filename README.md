# Caram3lo_
![Caram3loV1](/assets/caramelov1.png)
## Caram3lo fareja a internet em busca de fontes de financiamento para projetos culturais.

- - -

## **O QUE É O** `Caram3lo_`**?**

- É um *bot web scraper* que **procura editais culturais** em vários sites, nacionais e paraibanos.
- Ao encontrar um edital, ele **dá uma olhada** para ver se tem o link para o documento (tipo um PDF), se tem prazo para se inscrever e se diz quais áreas podem participar.
- Se o edital estiver "completo" com essas informações, ele **guarda** isso em um lugar seguro.
- Depois, ele **avisa lá no Discord** sobre o edital novo que ele encontrou.
- **Manda lembretes importantes** antes do prazo final, tipo "Última semana!" ou "Último dia!".

Basicamente, ele é feito para encontrar e disparar atualizações sobre oportunidades de patrocínio e financiamento para projetos culturais, focando em algumas regiões específicas.

## COMO FUNCIONA?

- A cada hora, Caram3lo_ busca novos editais em vários sites cadastrados, procurando termos relevantes como “edital”, “chamada pública”, “oportunidade”, “patrocínio”, "seleção", "incentivo" e outras palavras-chave relativas à fontes de financiamento.
- Extrai informações essenciais de potenciais editais encontrados.
- Valida cada edital verificando a presença de:
    - **Link direto para o documento oficial** (.PDF, .DOCX, .CVS, .PPTX, .PPT).
    - **Prazo de inscrição**.
    - **Categorias participantes**.
- Descarta editais que não contenham as informações essenciais validadas.
- Armazena editais validados.
- Posta avisos no Discord ao encontrar um novo edital validado ('EDITAL ABERTO').
- Configura lembretes e os envia ('ÚLTIMA SEMANA DE INSCRIÇÕES' e 'ÚLTIMO DIA') conforme os prazos se aproximam.
- Prioriza busca por editais com ênfase em João Pessoa, na Paraíba, e na região Norte-Nordeste do Brasil.

PÓS-LANÇAMENTO:
- Permitir a adição de novas fontes de editais através de uma interface web.

## TECH STACK

- JavaScript - [**Node.js**](https://nodejs.org/pt) (open-source), [Puppeteer](https://pptr.dev/) (open-source)
- Github, Github Pages (gratuito)
- Editado no [**VS Code**](https://code.visualstudio.com/) (open-source).
