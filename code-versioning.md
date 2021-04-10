<div style="text-align: justify">

# VERSIONING DEL CODICE

## COS' &#0200;?

> In informatica, per **versioning** si intende la _gestione di versioni multiple di una stessa informazione_

In poche parole, si tratta di un metodo di lavoro che gli sviluppatori utilizzano per **abbattere** le barriere che rendono non funzionale la collaborazione all'interno di un ambiente lavorativo.

## PERCH&#0200; &#0200; UTILE?

Grazie a questo metodo, è possibile ricavare numerosi vantaggi:

- l'intero **storico** delle versioni viene **salvato**, in modo da poter recuperare da un punto precedente in caso di errori o imprevisti

- più sviluppatori possono lavorare **contemporaneamente** allo stesso progetto, senza preoccuparsi di creare conflitti al suo interno o di comprometterne il funzionamento

- chiunque abbia accesso al progetto, come sviluppatore o come semplice utente, ha la possibilità di **segnalare** ai proprietari eventuali errori, migliorie, consigli o chiarimenti

## COME FUNZIONA?

Per sfruttare questo metodo, è necessario utilizzare un software, _**Git**_.

<div style="text-align: center">

![Git Logo](images/git-logo.png)

</div>

> Git è un software di controllo di versione distribuito utilizzabile da interfaccia a **riga di comando**, creato da _Linus Torvalds_ nel 2005.

Per svolgere azioni, è necessaria la conoscenza di alcuni comandi.  
La prima operazione da compiere è **creare una _repository_**.
A tale scopo è necessario spostarsi nella directory del progetto e scrivere il comando

```git
        git init
```

Se invece si preferisce utilizzarne una **già esistente**, sarà sufficiente **_clonarla_** utilizzando il comando

```git
        git clone
```

seguito dal link della repository da clonare.

Una volta ottenuta la repository, è possibile costruire la storia del progetto tramite una **_commit_**. Prima però è necessaria un'operazione intermedia, in cui i file vengono **temporaneamente salvati** in attesa della commit vera e propria.  
Perciò, per fare una commit, è necessaria la sequenza di comandi

```git
        git add *.js
        git commit -m 'Prima commit'
```

Con il primo comando vengono aggiunti tutti i file .js del progetto, poi si fa la commit (specificando un commento con l'opzione _-m_).  
Per rimuovere un file, invece, bisogna fare lo stesso processo sostituendo il comando _add_ con il comando _rm_, seguito dalla commit.

Per visualizzare l'intera storia del repository si usa il comando

```git
        git log
```

Lavorando con Git, è fondamentale mantenere il proprio progetto **sincronizzato** sia in locale che da remoto, per fare ciò esistono due comandi:

- per aggiornare la repository da remoto con i file che erano stati salvati in precedenza con la commit si utilizza

```git
        git push
```

- per aggiornare la repository locale, scaricando i nuovi file dalla repository remota e aggiornando quelli già esistenti si utilizza

```git
        git pull
```

Un comando utile per controllare lo stato dei file del progetto è

```git
        git status
```

Tramite questo comando è possibile mostrare i file pronti per la commit e quelli che ancora non sono stati versionati.

## AMBIENTI PI&#0217; UTILIZZATI

Per sfruttare questo software, sono state create varie piattaforme che permettono una più comoda gestione di tutte le azioni riguardanti il proprio progetto.  
Le più utilizzate sono:

| GitHub      |           ![GitHub Logo](images/github-logo.png) |
| :---------- | -----------------------------------------------: |
| GitLab      |           ![GitLab Logo](images/gitlab-logo.png) |
| BitBucket   |     ![BitBucket Logo](images/bitbucket-logo.png) |
| SourceForge | ![SourceForge Logo](images/sourceforge-logo.png) |
| Gogs        |               ![Gogs Logo](images/gogs-logo.png) |
| Gitea       |             ![Gitea Logo](images/gitea-logo.png) |

All'interno di questi ambienti, è possibile svolgere alcune operazioni senza utilizzare righe di comando, avendo anche delle funzionalità aggiuntive.

Per esempio, utilizzando **GitHub**, è possibile creare delle **_pull request_**, ossia un metodo per rendere noto ai possessori del progetto che sono state effettuate delle modifiche che potrebbero migliorarlo, chiedendo quindi di effettuare una pull che implementi tali modifiche.

In maniera analoga, è possibile anche creare delle **_issues_**, ossia delle segnalazioni di problemi, bug o errori presenti nel progetto, chiedendo quindi agli sviluppatori di sistemarli e correggerli.

Se si desidera invece avere una propria copia della repository di un progetto, è possibile utilizzare il tasto **_fork_**, grazie al quale viene creata una vera e propria copia di un progetto, sulla quale si può lavorare senza interagire con il progetto vero e proprio.

## COCNLUSIONI

&#0200; chiaro quindi che utilizzare un metodo di versionamento del codice, come Git, sia una risorsa estremamente utile per ogni sviluppatore, la nascita di questa modalità ha portato una vera **rivoluzione** per il mondo della programmazione.

<br>

---

<div style="text-align: right">

#### Mariottini Matteo, 4<sup>a</sup> AI

</div>

</div>
