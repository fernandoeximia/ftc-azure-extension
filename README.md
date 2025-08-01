# FTC Azure Extension

Uma extensão para Azure DevOps que fornece funcionalidades específicas para facilitar a vida do Product Owner e do desenvolvedor utilizando inteligencia artificial do jeito certo.

## 📋 Descrição

Esta extensão foi desenvolvida para acelerar a criação de user stories e garantir que elas sejam criadas pensando em uma engenharia apoiada por inteligência artificial.

## 🛠️ Tecnologias

- **Azure DevOps Extension SDK**: Framework oficial para desenvolvimento de extensões
- **Node.js**: Runtime JavaScript para desenvolvimento
- **TypeScript**: Linguagem de programação tipada
- **HTML/CSS**: Interface do usuário

## 📦 Instalação

### Pré-requisitos

- Node.js (versão 18.0.0 ou superior)
- Azure DevOps organizacional
- Permissões de administrador para instalar extensões

### Desenvolvimento

1. **Clone o repositório**
   ```bash
   git clone https://github.com/fernandoeximia/ftc-azure-extension.git
   cd ftc-azure-extension
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Configure o ambiente**
   ```bash
   # Configure as variáveis de ambiente necessárias
   cp .env.example .env
   ```

4. **Desenvolva e teste**
   ```bash
   # Para desenvolvimento local
   npm run dev
   
   # Para criar o pacote de extensão
   tfx extension create
   ```

## 🔧 Configuração

### Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis:

```env
AZURE_DEVOPS_PAT=your_personal_access_token
AZURE_DEVOPS_ORG=your_organization_name
AZURE_DEVOPS_PROJECT=your_project_name
```

### Instalação da Extensão

1. Gere o arquivo `.vsix`:
   ```bash
   tfx extension create
   ```

2. Faça upload da extensão no Azure DevOps:
   - Acesse: https://dev.azure.com/[sua-organizacao]/_gallery/manage
   - Clique em "Upload"
   - Selecione o arquivo `.vsix` gerado


## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença ISC. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Autores

- **Fernando Neiva** - *Desenvolvimento inicial* - [fernandoeximia](https://github.com/fernandoeximia)

## 🙏 Agradecimentos

- Equipe FTC EximiaCo
- ElemarJr

## 📞 Suporte

Para suporte e dúvidas:

- 📧 Email: [fernando.paiva@eximia.co]
- 🐛 Issues: [GitHub Issues](https://github.com/fernandoeximia/ftc-azure-extension/issues)
- 📖 Documentação: [Wiki do projeto](https://github.com/fernandoeximia/ftc-azure-extension/wiki)


