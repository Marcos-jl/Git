<h1>
   <img align="center" alt="Marcos-Git" height="70" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain-wordmark.svg">
    <img align="center" alt="Marcos-GitHub" height="70" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg">
    <img align="center" alt="Marcos-GitLab" height="70" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original-wordmark.svg">
</h1>

Cadastrar Nome:

```
git config --global user.name "YourName"
```

Cadastrar Email:

```
git config --global user.email youremail@exemplo.br
```



# :key: Gerar chave SSH (ed25519)

1. Abra o terminal utilizando o comando (Ctrl + t) no teclado:

2. Execute o comando abaixo:

   ``` 
   ssh-keygen -t ed25519 -C "your_email@example.com"

3. Confirme e crie uma senha para comandos ssh

4. Execute os seguintes comandos:

   ```
   cd .ssh
   cat id_ed25519.pub
   ```

5. Copie a saída cat e adiciona na sua chave ssh do GitHub ou Gitlab.

6. Execute os camandos abaixo:

   ```
   eval "$(ssh-agent -s)"
   ssh-add id_ed25519
   ```

7. Pronto! Sua SSH está configurada!



# :key: Gerar chave SSH (rsa)

1. Abra o terminal utilizando o comando (Ctrl + t) no teclado:

2. Execute o comando abaixo:

   ``` 
   ssh-keygen -t rsa -C "youremail@eexemple.com.br"
   ```

3. Confirme e crie uma senha para comandos ssh

4. Execute os seguintes comandos:

   ```
   cd .ssh
   cat id_rsa.pub
   ```

5. Copie a saída cat e adiciona na sua chave ssh do GitHub ou Gitlab.

6. Execute os camandos abaixo:

   ```
   eval "$(ssh-agent -s)"
   ssh-add id_rsa
   ```

7. Pronto! Sua SSH está configurada!

