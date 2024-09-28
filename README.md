# sastogit

Como conectar o Github no SAS Viya

## Passo-a-passo

Passo 1

Passo 2

Pass 3
No Terminal digite o seguinte comando:

```ssh
ssh-keygen -t ecdsa -b 521 -C 'your_email@domain.com'
```

Depois, ele irá para você dar um nome ao seu arquivo ```ssh```. No meu caso eu usei <b>SAS</b>.

Agora, você precisará let a chave. Use então esse comando:

```ssh
cat /<nome_do_arquivo>.pub
```

Copie a chave.

Agora, pegue os dois arquivos gerados do SSH e coloque em uma pasta no SAS Viya...