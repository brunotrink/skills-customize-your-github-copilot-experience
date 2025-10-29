# Descrição do Projeto

Este projeto é um site educacional para compartilhar tarefas de casa e exercícios de programação com estudantes. Os estudantes podem navegar, visualizar e baixar tarefas diretamente do portal.

## Estrutura do Projeto

- [`assignments/`](../assignments/) Cada tarefa de casa é armazenada em sua própria subpasta com uma estrutura consistente.
- [`templates/`](../templates/) Templates reutilizáveis para novo conteúdo
- [`assets/`](../assets/) Contém os recursos do site incluindo CSS, JavaScript, imagens e arquivos de configuração
- [`index.html`](../index.html) A página principal do site que serve como um portal estático para navegar e visualizar tarefas. O conteúdo é configurável através do arquivo [`config.json`](../config.json) para gerar dinamicamente listas e detalhes de tarefas.

## Diretrizes do Projeto

- Manter estilo consistente em todas as páginas
- Manter nomes de arquivos e pastas descritivos e organizados

## Padrões Educacionais

Ao gerar conteúdo para este projeto:

- **Focado em aprendizado**: Todo conteúdo deve ser projetado com objetivos de aprendizado claros e níveis de dificuldade apropriados
- **Amigável para estudantes**: Use linguagem clara e encorajadora que motiva os estudantes

## Conventional Commits

Este projeto segue o padrão de Conventional Commits para mensagens de commit. Cada commit deve seguir o formato:

```
<tipo>[escopo opcional]: <descrição>

[corpo opcional]

[rodapé(s) opcional(is)]
```

### Tipos de Commit

- `feat`: Nova funcionalidade
- `fix`: Correção de bug
- `docs`: Alterações em documentação
- `style`: Formatação, ponto e vírgula faltando, etc (sem alteração no código)
- `refactor`: Refatoração de código
- `test`: Adição ou correção de testes
- `chore`: Atualizações de tarefas de build, configurações, etc (sem alteração no código)

### Exemplos:

```
feat: adiciona página de lista de exercícios

Implementa uma nova página que lista todos os exercícios disponíveis
organizados por disciplina.

Closes #123
```

```
fix(login): corrige validação de senha

Corrige bug onde senhas com caracteres especiais não eram aceitas
```

```
docs(readme): atualiza instruções de instalação
```

```
style: formata arquivos CSS usando prettier
```

```
test(auth): adiciona testes para autenticação
```