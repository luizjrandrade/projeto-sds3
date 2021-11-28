# projeto-sds3
Projeto Java, Spring Boot, criado na Semana DevSuperior Spring React.
>  *App inédito para com as tecnologias mais demandadas do mercado*

<h3>Objetivos do Projeto</h3>
<ul>
<li>Criar projetos backend e frontend</li>
<li>Salvar os projeto no Github em monorepo</li>
<li>Montar o visual estático do front end</li>
<li>Publicar o front end no Netlify</li>
</ul>

### Passo 1: criar projetos
- Criar projeto ReactJS com `create-react-app`:

### Passo 2: "limpar" o projeto ReactJS
- Limpar projeto ReactJS / tsconfig.json
- Arquivo _redirects

- **COMMIT: Bootstrap**
### Passo 4: adicionar componentes estáticos básicos
- Navbar
- Footer
- DataTable

- **COMMIT: Basic static components**
### Passo 5: adicionar gráficos estáticos
- Apex Charts
- BarChart
- DonutChart

- **COMMIT: Static charts**
### Passo 6: implantação no Netlify
- Deploy básico
  - Base directory: frontend
  - Build command: yarn build
  - Publish directory: frontend/build

- Configurações adicionais
  - Site settings -> Domain Management
  - Deploys -> Trigger deploy

### Passo 7: Modelo Conceitual
![Image](https://github.com/devsuperior/bds-assets/raw/main/sds/sds3-mc.png "Modelo conceitual")

### Padrão camadas adotado
![Image](https://github.com/devsuperior/bds-assets/raw/main/sds/camadas.png "Padrão camadas")

- Criar repositories
- Criar DTO's
- Criar service
- Criar controller
- **COMMIT: Layers**

### Passo 8: Busca paginada de vendas

- Pageable
- page, size, sort
- Evitando interações repetidas ao banco de dados
- **COMMIT: Pagination**

### Passo 9: Buscas agrupadas (GROUP BY)

- Total de vendas por vendedor
- Taxa de sucesso por vendedor
- **COMMIT: Group by search**

### Passo 10: Validação no Postgres local

- Criar três perfis de projeto: test, dev, prod
- Gerar script SQL no perfil dev
- Testar projeto no banco Postgres local

## Passo 11: Objetivos
- Integrar back end e front end
- Três pilares do React
  - Componentes
  - Props
  - Estado
- React Hooks
  - useState
  - useEffect
- Libs
  - React Router DOM
  - Axios

## Projeto Netlify
<a href="https://dsvendas-luizjunior.netlify.app/" target="_blank">DSVendas LuizJunior</a>

