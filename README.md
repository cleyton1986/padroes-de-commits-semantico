# Padrões de commits 📜

De acordo com a documentação do **[Conventional Commits](https://www.conventionalcommits.org/pt-br)**, commits semânticos são uma convenção simples para ser utilizada nas mensagens de commit. Essa convenção define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas.

Esses commits auxiliarão você e sua equipe a entenderem de forma facilitada quais alterações foram realizadas no trecho de código que foi commitado.

Essa identificação ocorre por meio de uma palavra e emoji que identifica se aquele commit realizado se trata de uma alteração de código, atualização de pacotes, documentação, alteração de visual, teste...

## Tipo e descrição 🦄

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

- `feat`- Commits do tipo **feat** indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo **fix** indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo **docs** indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo **test** são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` - Commits do tipo **build** são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - Commits do tipo **perf** servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` - Commits do tipo **style** indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` - Commits do tipo **refactor** referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo **chore** indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `ci` - Commits do tipo **ci** indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

- `raw` - Commits to tipo **raw** indicam mudanças relacionadas a arquivos de configurações, dados, features, parametros.

- `docker` - Commits do tipo **docker** indicam mudanças relacionadas a criação e configurações de arquivos docker, Dockerfile e etc.

- `a11y` - Commits do tipo **a11y** indicam mudanças relacionadas a acessibilidade.

- `deprecation` - Commits do tipo **deprecation** indicam mudanças relacionadas atualizações de código para lidar com métodos ou funcionalidades obsoletas.

- `revert` - Commits do tipo **revert** é relacionado ao reverte de mudanças previamente aplicadas.

- `api` - Commits do tipo **api** indicam trabalho relacionadas APIs externas.

- `conflict` - Commits do tipo **conflict** indicam mudanças relacionadas resolução de conflitos.

- `env` - Commits do tipo **env** indicam mudanças relacionadas variáveis de ambiente.

- `i18n` - Commits do tipo **i18n** é relacionado a internacionalização.

- `type` - Commits do tipo **type** é relacionado a criação, configurações e modificações de tipos.

- `migration` - Commits do tipo **migration** é relacionado manipulação de migrations.

- `security` - Commits do tipo **security** é relacionado a segurança.

- `feedback` - Commits do tipo **feedback** é relacionado a incorporação de feedback.

- `dependency` - Commits do tipo **dependency** é relacionado a atualização ou adição de dependências externas.

- `cleanup` - Commits do tipo **cleanup** é relacionado a limpeza de código ou remoção de arquivos não utilizados.

- `hotfix` - Commits do tipo **hotfix** é relacionado a Implementação de uma correção rápida em produção.

## Recomendações 🎉

- Adicione um tipo consistente com o título do conteúdo.
- Recomendamos que na primeira linha deve ter no máximo 4 palavras.
- Para descrever com detalhes, usar a descrição do commit.
- Usar um emoji no início da mensagem de commit representando sobre o commit.
- Os links precisam ser adicionados em sua forma mais autêntica, ou seja: sem encurtadores de link e links afiliados.

## Complementos de commits 💻

- **Rodapé:** informação sobre o revisor e número do card no Trello ou Jira. Exemplo: Reviewed-by: Elisandro Mello Refs #133
- **Corpo:** descrições mais precisas do que está contido no commit, apresentando impactos e os motivos pelos quais foram empregadas as alterações no código, como também instruções essenciais para intervenções futuras. Exemplo: see the issue for details on typos fixed.
- **Descrições:** uma descrição sucinta da mudança. Exemplo: correct minor typos in code

## Padrões de emojis 💈

<table>
  <thead>
    <tr>
      <th>Tipo do commit</th>
      <th>Emoji</th>
      <th>Palavra-chave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Acessibilidade</td>
      <td>♿ <code>:wheelchair:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Adicionando um teste</td>
      <td>✅ <code>:white_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Atualizando a versão de um submódulo</td>
      <td>⬆️ <code>:arrow_up:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Retrocedendo a versão de um submódulo</td>
      <td>⬇️ <code>:arrow_down:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Adicionando uma dependência</td>
      <td>➕ <code>:heavy_plus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Alterações de revisão de código</td>
      <td>👌 <code>:ok_hand:</code></td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Animações e transições</td>
      <td>💫 <code>:dizzy:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td>🐛 <code>:bug:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Comentários</td>
      <td>💡 <code>:bulb:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Commit inicial</td>
      <td>🎉 <code>:tada:</code></td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Configuração</td>
      <td>🔧 <code>:wrench:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td>🚀 <code>:rocket:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td>📚 <code>:books:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td>🚧 <code>:construction:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Estilização de interface</td>
      <td>💄 <code>:lipstick:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td>🧱 <code>:bricks:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Lista de ideias (tasks)</td>
      <td>🔜 <code> :soon: </code></td>
      <td></td>
    </tr>
    <tr>
      <td>Mover/Renomear</td>
      <td>🚚 <code>:truck:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td>✨ <code>:sparkles:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Package.json em JS</td>
      <td>📦 <code>:package:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td>⚡ <code>:zap:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Refatoração</td>
        <td>♻️ <code>:recycle:</code></td>
        <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td>🔥 <code>:fire:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Removendo uma dependência</td>
      <td>➖ <code>:heavy_minus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Responsividade</td>
      <td>📱 <code>:iphone:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Revertendo mudanças</td>
      <td>💥 <code>:boom:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td>🔒️ <code>:lock:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>🔍️ <code>:mag:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tag de versão</td>
      <td>🔖 <code>:bookmark:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Teste de aprovação</td>
      <td>✔️ <code>:heavy_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Testes</td>
      <td>🧪 <code>:test_tube:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Texto</td>
      <td>📝 <code>:pencil:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tipagem</td>
      <td>🏷️ <code>:label:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tratamento de erros</td>
      <td>🥅 <code>:goal_net:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Dados</td>
      <td>🗃️ <code>:card_file_box:</code></td>
      <td><code>raw</code></td>
    </tr>
    <tr>
      <td>Docker e containers</td>
      <td>🐳 <code>:whale:</code></td>
      <td><code>docker</code></td>
    </tr>
    <tr>
      <td>Melhorias na UI/UX</td>
      <td>🎨 <code>:art:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Trabalho com APIs externas</td>
      <td>🔗 <code>:link:</code></td>
      <td><code>api</code></td>
    </tr>
    <tr>
      <td>Corrigindo erros de lint (específico para correções de lint)</td>
      <td>💅 <code>:nail_care:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Acessibilidade (melhorias específicas de acessibilidade)</td>
      <td>🦮 <code>:guide_dog:</code></td>
      <td><code>a11y</code></td>
    </tr>
    <tr>
      <td>Internacionalização (adicionando ou atualizando traduções)</td>
      <td>🌐 <code>:globe_with_meridians:</code></td>
      <td><code>i18n</code></td>
    </tr>
    <tr>
      <td>Melhoria de Código</td>
      <td>🌈 <code>:rainbow:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Correção de deprecations</td>
      <td>⚠️ <code>:warning:</code></td>
      <td><code>deprecation</code></td>
    </tr>
    <tr>
      <td>Refatoração de código (não funcional)</td>
      <td>🔨 <code>:hammer:</code></td>
      <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Implementação de feature flag</td>
      <td>🚩 <code>:triangular_flag_on_post:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Otimização de assets (imagens, fontes, etc.)</td>
      <td>🐎 <code>:racehorse:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
      <td>Configurações de CI/CD</td>
      <td>🔄 <code>:arrows_counterclockwise:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Reversão de commits</td>
      <td>🔙 <code>:back:</code></td>
      <td><code>revert</code></td>
    </tr>
    <tr>
      <td>Desfazendo alterações anteriores</td>
      <td>⏪ <code>:rewind:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Implementação de novas funcionalidades</td>
      <td>🌟 <code>:star:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Adicionando variáveis de ambiente</td>
      <td>🌍 <code>:earth_americas:</code></td>
      <td><code>env</code></td>
    </tr>
    <tr>
      <td>Correção de tipos</td>
      <td>✏️ <code>:pencil2:</code></td>
      <td><code>type</code></td>
    </tr>
    <tr>
      <td>Manipulação de Migrations</td>
      <td>🔁 <code>:arrows_counterclockwise:</code></td>
      <td><code>migration</code></td>
    </tr>
    <tr>
      <td>Melhorias de segurança no código</td>
      <td>🔏 <code>:lock_with_ink_pen:</code></td>
      <td><code>security</code></td>
    </tr>
    <tr>
      <td>Incorporação de feedback do usuário.</td>
      <td>📣 <code>:mega:</code></td>
      <td><code>feedback</code></td>
    </tr>
    <tr>
      <td>Atualização ou adição de dependências</td>
      <td>📥 <code>:inbox_tray:</code></td>
      <td><code>dependency</code></td>
    </tr>
    <tr>
      <td>Limpeza de código ou remoção de arquivos não utilizados</td>
      <td>🗑️ <code>:wastebasket:</code></td>
      <td><code>cleanup</code></td>
    </tr>
    <tr>
      <td>Implementação de uma correção rápida em produção</td>
      <td>🚑 <code>:ambulance:</code></td>
      <td><code>hotfix</code></td>
    </tr>
  </tbody>

</table>

## 💻 Exemplos

<table>
  <thead>
    <tr>
      <th>Comando Git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: Commit inicial"</code>
      </td>
      <td>🎉 Commit inicial</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: Atualização do README"</code>
      </td>
      <td>📚 docs: Atualização do README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Loop infinito na linha 50"</code>
      </td>
      <td>🐛 fix: Loop infinito na linha 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Página de login"</code>
      </td>
      <td>✨ feat: Página de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modificação no Dockerfile"</code>
      </td>
      <td>🧱 ci: Modificação no Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Passando para arrow functions"</code>
      </td>
      <td>♻️ refactor: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Melhoria no tempo de resposta"</code>
      </td>
      <td>⚡ perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revertendo mudanças ineficientes"</code>
      </td>
      <td>💥 fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Estilização CSS do formulário"</code>
      </td>
      <td>💄 feat: Estilização CSS do formulário</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Criando novo teste"</code>
      </td>
      <td>🧪 test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Comentários sobre a função LoremIpsum( )"</code>
      </td>
      <td>💡 docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":card_file_box: raw: RAW Data do ano aaaa"</code>
      </td>
      <td>🗃️ raw: RAW Data do ano aaaa</td>
    </tr>
        <tr>
      <td>
        <code>git commit -m ":whale: docker: Adição de Dockerfile para ambiente de produção"</code>
      </td>
      <td>🐳 docker: Adição de Dockerfile para ambiente de produção</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":art: feat: Melhorias na interface do usuário para aumentar a usabilidade"</code>
      </td>
      <td>🎨 feat: Melhorias na interface do usuário para aumentar a usabilidade</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":link: api: Integração com a nova API de pagamentos"</code>
      </td>
      <td>🔗 api: Integração com a nova API de pagamentos</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":nail_care: chore: Correção de erros de lint no projeto"</code>
      </td>
      <td>🧹 chore: Correção de erros de lint no projeto</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":guide_dog: a11y: Melhorias de acessibilidade no formulário de login"</code>
      </td>
      <td>🦮 a11y: Melhorias de acessibilidade no formulário de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":globe_with_meridians: i18n: Adição de suporte a mais idiomas na internacionalização"</code>
      </td>
      <td>🌐 i18n: Adição de suporte a mais idiomas na internacionalização</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":rainbow: feat: Melhoria de código no módulo de autenticação"</code>
      </td>
      <td>🌈 feat: Melhoria de código no módulo de autenticação</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":warning: fix: Correção de deprecations após atualização de bibliotecas"</code>
      </td>
      <td>⚠️ deprecation: Correção de deprecations após atualização de bibliotecas</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":hammer: refactor: Refatoração do sistema de rotas para melhorar a manutenção"</code>
      </td>
      <td>🔨 refactor: Refatoração do sistema de rotas para melhorar a manutenção</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":triangular_flag_on_post: feat: Implementação de feature flag para novas funcionalidades em teste"</code>
      </td>
      <td>🚩 feat: Implementação de feature flag para novas funcionalidades em teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":racehorse: perf: Otimização de assets para acelerar o tempo de carregamento da página"</code>
      </td>
      <td>🐎 perf: Otimização de assets para acelerar o tempo de carregamento da página</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":arrows_counterclockwise: ci: Atualização das configurações de CI/CD para melhorar a integração"</code>
      </td>
      <td>🔄 ci: Atualização das configurações de CI/CD para melhorar a integração</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":back: revert: Reversão de commit que introduziu erro em produção"</code>
      </td>
      <td>🔙 revert: Reversão de commit que introduziu erro em produção</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":rewind: fix: Desfazendo alterações anteriores que causaram regressões nos testes"</code>
      </td>
      <td>⏪ fix: Desfazendo alterações anteriores que causaram regressões nos testes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":star: feat: Implementação de novas funcionalidades no sistema de recomendações"</code>
      </td>
      <td>🌟 feat: Implementação de novas funcionalidades no sistema de recomendações</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":earth_americas: env: Adicionando variáveis de ambiente"</code>
      </td>
      <td>🌍 env: Adicionando novas variáveis de ambiente</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":pencil2: type: Correção de tipos"</code>
      </td>
      <td>✏️ type: Correção de tipos</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":arrows_counterclockwise: migration: criação da migration"</code>
      </td>
      <td>🔁 migration: criação da migration</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lock_with_ink_pen: security: melhorando segurança no código"</code>
      </td>
      <td>🔏 security: melhorando segurança no código</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":inbox_tray: dependency: atualização das dependências externas "</code>
      </td>
      <td>📥 dependency: atualização das dependências externas </td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":wastebasket: cleanup: removendo código desnecessário "</code>
      </td>
      <td>🗑️ cleanup: removendo código desnecessário </td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":ambulance: hotfix: correção em produção "</code>
      </td>
      <td>🚑 hotfix: correção em produção </td>
    </tr>

  </tbody>
</table>

## Contribuição ✨

Ajude a comunidade tornando este projeto ainda mais incrível. Leia como contribuir clicando **[aqui](https://github.com/iuricode/padroes-de-commits/blob/main/CONTRIBUTING.md)** e a **[licença](https://github.com/iuricode/padroes-de-commits/blob/main/LICENSE.md)**. Estou convencido de que juntos alcançaremos coisas incríveis!

## Aprenda desenvolvimento frontend ❤️

Este repositório é um projeto gratuito para a comunidade de desenvolvedores, mas você pode me ajudar comprando o meu ebook "**[eFront - Estudando frontend do zero](https://iuricode.com/efront)**" se estiver interessado em aprender ou melhorar suas habilidades de desenvolvimento frontend. A sua compra me ajuda a produzir e fornecer mais conteúdo gratuito para a comunidade. Adquira agora e comece sua jornada no desenvolvimento frontend.
