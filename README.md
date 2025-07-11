# 🚀 Projeto desenvolvido durante o NLW da Rocketseat – Trilha Node.js

Durante o evento **NLW da Rocketseat (Agents)**, desenvolvi este projeto como forma de consolidar meus conhecimentos em **back-end moderno com Node.js**, construindo uma **API robusta, performática e escalável** do zero. Foi uma experiência prática incrível que me permitiu entender com profundidade a integração entre várias tecnologias atuais.

---

## 🧠 O que aprendi

- Utilizar **Node.js com TypeScript nativo**, aproveitando o novo recurso `--experimental-strip-types`
- Construção de APIs com **Fastify**, um framework web rápido e leve
- Uso de **PostgreSQL** com extensão **pgvector**, ideal para trabalhar com vetores (IA)
- Integração com o **Drizzle ORM** para consultas e migrações seguras e *type-safe*
- Validação de dados com **Zod**, garantindo segurança e consistência
- Configuração de ambiente com **Docker e Docker Compose**
- Uso do **Biome** para linting e formatação automática do código

---

## 🏗️ Arquitetura do Projeto

- Estrutura modular com separação entre rotas, schemas e conexão com banco
- Schemas de validação com **Zod** para segurança de tipos
- **Drizzle ORM** para manipulação segura do banco de dados
- Validação centralizada das variáveis de ambiente

---

## 📚 Scripts Disponíveis

| Script              | Descrição                                          |
|---------------------|----------------------------------------------------|
| `npm run dev`       | Executa o servidor em modo de desenvolvimento      |
| `npm start`         | Executa o servidor em modo de produção             |
| `npm run db:seed`   | Popula o banco com dados de exemplo                |

---

## 🌐 Endpoints

A API estará acessível em: [http://localhost:3333](http://localhost:3333)

- `GET /health` – Health check da aplicação
- `GET /rooms` – Lista as salas disponíveis

---

## 💬 Considerações finais

Participar do **NLW Agents** foi uma ótima oportunidade para aplicar conceitos modernos e boas práticas no desenvolvimento de APIs. Estou animado para continuar evoluindo e aplicar esse conhecimento em projetos reais! 🚀
