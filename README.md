# Restaurant Manager 🍔

![Banner](https://via.placeholder.com/1200x300.png?text=Restaurant+Manager)  

Bem-vindo ao **Restaurant Manager**, um sistema completo para gerenciamento de restaurantes! Esta aplicação permite que donos de restaurantes cadastrem seus estabelecimentos, configurem taxas de entrega por bairro, gerenciem produtos e acompanhem pedidos, enquanto clientes podem visualizar menus públicos e fazer pedidos online. Construído com tecnologias modernas, é uma solução escalável e fácil de usar.

---

## ✨ Funcionalidades

- **Autenticação**
  - Login e registro de usuários (email, senha e nome do restaurante).
  - Geração automática de slugs para URLs públicas.

- **Dashboard do Restaurante**
  - Configuração de perfil (logo, descrição).
  - Gerenciamento de taxas de entrega por bairro (adicionar, editar, deletar).
  - Gerenciamento de produtos (nome, preço, descrição, disponibilidade).
  - Visualização e controle de pedidos (aceitar, recusar, despachar).

- **Menu Público**
  - Exibição de produtos disponíveis por restaurante (acessível via `/[slug]`).
  - Carrinho de compras com seleção de bairro para entrega.
  - Cálculo dinâmico de subtotal, taxa de entrega e total.
  - Envio de pedidos ao restaurante.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia         | Descrição                              |
|--------------------|----------------------------------------|
| **Next.js**       | Framework React para SSR e SSG         |
| **TypeScript**    | Tipagem estática para maior segurança  |
| **Tailwind CSS**  | Estilização rápida e responsiva        |
| **Supabase**      | Banco de dados PostgreSQL e autenticação |
| **shadcn/ui**     | Componentes UI acessíveis e customizáveis |

---


