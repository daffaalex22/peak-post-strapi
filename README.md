# 🏔️ Peak Post Strapi Backend

A multi-tenant blog CMS backend built with Strapi v5. Powers the [Peak Post Frontend](https://github.com/daffaalex22/peak-post).

## 🌟 Features

- 📱 Multi-tenant support - Serve different content for different domains
- 🌐 GraphQL API endpoint
- 🔐 Role-based access control
- 📝 Rich text editor with Markdown support
- 🖼️ Media management
- 🌍 Internationalization ready
- 🔄 Content versioning
- 🎯 Draft & publish workflow

## 🛠️ Notable Tech Stack

- **@strapi/strapi**: Core Strapi framework v5
- **@strapi/plugin-graphql**: GraphQL API support
- **@strapi/plugin-users-permissions**: Authentication & authorization
- **PostgreSQL**: Production database
- **TypeScript**: Type safety throughout the codebase

## 🚀 Live Preview

The API is deployed at:
- Admin Panel: https://peak-post-strapi.onrender.com/admin
- GraphQL Playground: https://peak-post-strapi.onrender.com/graphql

## 💻 Running Locally

1. Clone the repository
```bash
git clone https://github.com/your-username/peak-post-strapi.git
cd peak-post-strapi
```

2. Install dependencies
```bash
yarn install
```

3. Set up environment variables
```bash
cp .env.example .env
```
Configure your `.env` file with appropriate values.

4. Start development server
```bash
yarn develop
```

5. Start production server
```bash
yarn build
yarn start
```

The server will be available at:
- Admin Panel: http://localhost:1337/admin
- GraphQL Playground: http://localhost:1337/graphql

## 📚 Documentation

For more details about Strapi's features and API, check out:
- [Strapi Documentation](https://docs.strapi.io)
- [GraphQL API Reference](https://docs.strapi.io/dev-docs/plugins/graphql)

## 🔗 Related Projects

- [Peak Post Frontend](https://github.com/daffaalex22/peak-post) - Next.js frontend application
