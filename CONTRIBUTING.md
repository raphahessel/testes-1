# Contribuindo

## Preparação

#### 1. Faça um fork do repositório
[Bifurcar um repo - GitHub Docs](https://docs.github.com/pt/github/getting-started-with-github/quickstart/fork-a-repo)

#### 2. Crie um clone do seu fork
```sh
git clone https://github.com/SEU-USERNAME/testes
```

#### 3. Configure um remote para sincronizar alterações no fork
```sh
git remote add upstream https://github.com/comunidadedev/testes.git
```

## Resolvendo um problema

#### 1. Escolha um [problema](https://github.com/comunidadedev/testes/issues) e comente nele para sabermos que você irá resolve-lo

#### 2. Certifique-se de que você está trabalhando na branch develop
```sh
git checkout develop
```

#### 3. Sincronize as alterações no fork
##### *Não é necessário se você tiver feito o clone recentemente*
```sh
git fetch upstream
```

```sh
git merge upstream/develop
```

#### 4. Crie uma branch
```sh
git checkout -b feature/nome_da_sua_feature
```

#### 5. Desenvolva o seu código

#### 6. Faça o commit das alterações
```sh
git add .
```

```sh
git commit -m 'descrição do commit'
```
##### *Dica: faça o commit apenas quando o código estiver funcionando*

#### 7. Faça o push da sua branch
```sh
git push origin feature/nome_da_sua_feature
```

#### 8. Crie um pull request
[Criando uma pull request a partir de uma bifurcação - GitHub Docs](https://docs.github.com/pt/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

## Dúvidas
Se tiver dúvidas você pode enviá-las no Discord.
