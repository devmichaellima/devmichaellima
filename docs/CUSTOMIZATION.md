# Guia de Customização

Este projeto foi criado para funcionar como README de perfil do GitHub de `devmichaellima`.

## Alterar Nome e Posicionamento

No arquivo `README.md`, atualize:

- o título centralizado com o nome;
- a frase de posicionamento logo abaixo do título;
- a seção `Sobre`;
- a seção final de contato.

Mantenha o texto objetivo e baseado em entregas reais.

## Alterar Textos

Edite diretamente as seções do `README.md`. Para preservar o estilo profissional:

- evite frases genéricas;
- prefira resultados, problemas resolvidos e contexto de negócio;
- não declare senioridade ou domínio avançado sem evidência.

## Adicionar ou Remover Tecnologias

As tecnologias estão em duas áreas principais:

- `Experiência prática`;
- `Atualmente Estudando`.

Use `Experiência prática` apenas para ferramentas já usadas em entregas reais. Use `Atualmente Estudando` para tecnologias em estudo, laboratório ou projetos em desenvolvimento.

Para badges, prefira:

- `https://skillicons.dev`;
- `https://shields.io`;
- logos disponíveis no Simple Icons.

## Atualizar Contatos

No `README.md`, atualize todos os links dos botões no topo e da seção `Contato`.

Contatos atuais:

- LinkedIn: `https://www.linkedin.com/in/michael-lima-683aa3242`
- WhatsApp: `https://wa.me/5511959878735`
- E-mail: `mailto:dev.michaellima@gmail.com`
- GitHub: `https://github.com/devmichaellima`

## Trocar Projetos

Na seção `Projetos em Destaque`, substitua descrição, tecnologias e status.

Regras importantes:

- não invente URL para projeto privado, incompleto ou ainda inexistente;
- use `Em desenvolvimento` quando o repositório ainda não estiver público;
- priorize projetos com problema claro, stack definida e impacto mensurável.

## Habilitar ou Desabilitar GitHub Stats

A seção `Estatísticas do GitHub` usa serviços externos. Eles podem ficar temporariamente indisponíveis.

Para desabilitar, comente ou remova o bloco com as imagens:

```html
<p align="center">
  ...
</p>
```

Para habilitar novamente, mantenha os cards no máximo em dois itens para não competir visualmente com os projetos.

## Substituir o Banner

O banner fica em `assets/banner.svg`.

Ao substituir:

- mantenha o caminho relativo `assets/banner.svg`;
- use bom contraste;
- inclua `title`, `desc` e texto alternativo no `README.md`;
- evite imagens pesadas ou dependência de fontes locais.

## Criar o Repositório de Perfil

Para o README aparecer no perfil do GitHub, o repositório precisa ter exatamente o mesmo nome do usuário:

```text
devmichaellima
```

Depois de criar o repositório no GitHub:

1. copie os arquivos deste projeto para o repositório `devmichaellima`;
2. confirme que o `README.md` está na raiz;
3. faça commit e push para a branch principal.

## Publicar

Com o repositório remoto criado:

```bash
git remote add origin https://github.com/devmichaellima/devmichaellima.git
git push -u origin feature/profile-readme
```

Depois, abra um Pull Request ou faça merge para a branch principal conforme seu fluxo de trabalho.
