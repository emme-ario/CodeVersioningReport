# VERSIONING DEL CODICE

---

<p style="text-align: right"> Mariottini Matteo, 4<sup>a</sup> AI </p>



# COS' &#0200;?


> In informatica, per **versioning** si intende la gestione di versioni multiple di una stessa informazione


### In poche parole...

<p class="fragment fade-up">
    &#232; un <em>metodo di lavoro</em> che gli sviluppatori utilizzano per <strong>collaborare</strong>
</p>



# PERCH&#0200; &#0200; UTILE?


## NUMEROSI VANTAGGI

<div class="r-fit-text" style="text-align: center">
    <p class="fragment fade-up" data-fragment-index="3">
        l'intero <strong>storico</strong> delle versioni viene  <strong>salvato</strong>
    </p>
    <p class="fragment fade-down" data-fragment-index="1">
        pi&#249; sviluppatori possono lavorare  <strong>contemporaneamente</strong> allo stesso progetto
    </p>
    <p class="fragment fade-down" data-fragment-index="2">
        chiunque abbia accesso al progetto pu&#0242     <strong>segnalare</strong> errori
    </p>
</div>



# COME FUNZIONA?


Per sfruttare questo metodo, &#232; necessario utilizzare un software

<p class="fragment fade-down" data-fragment-index="1">
    <strong><em>Git</em></strong>
</p>

<div class="fragment fade-up" data-fragment-index="1">
    <img src="../images/git-logo.png">
</div>


> Git &#232; un software di controllo di versione distribuito utilizzabile da interfaccia a **riga di comando**, creato da Linus Torvalds nel 2005.


Per svolgere azioni, &#232; necessaria la conoscenza di alcuni comandi e bisogna rispettare una certa sequenza di operazioni.


## CREARE UNA REPOSITORY

<pre class="fragment"><code data-line-numbers>
    git init
</code></pre>


Se invece si preferisce utilizzarne una **gi&#0224; esistente** &#232; sufficiente **_clonarla_** utilizzando il comando

<pre class="fragment"><code data-line-numbers>
    git clone
</code></pre>

<p class="fragment fade-up">
    seguito dal link della repository da clonare.
</p>


Una volta ottenuta la repository, &#232; possibile costruire la storia del progetto tramite una **_commit_**. <br>
Prima &#232; necessaria un'operazione intermedia, in cui i file vengono **temporaneamente salvati** in attesa della commit vera e propria.


Quindi, per fare una commit, &#232; necessaria la sequenza di comandi:

<pre class="fragment"><code data-line-numbers>
    git add *.js
    git commit -m 'Prima commit'

</code></pre>

<p class="fragment">
    Con il primo comando vengono aggiunti tutti i file <em>.js</em>
</p>
<p class="fragment">
    Per rimuovere un file si sostituisce il comando <em>add</em> con il comando <em>rm</em>, seguito dalla commit.
</p>


Per visualizzare l'intera storia del repository si usa il comando

<pre class="fragment"><code data-line-numbers>
    git log

</code></pre>


Lavorando con Git, &#232; fondamentale mantenere il proprio progetto **sincronizzato** <br> sia in locale che da remoto. <br>

<p class="fragment fade-down">
Per aggiornare la repository da remoto si utilizza
</p>

<pre class="fragment"><code data-line-numbers>
    git push

</code></pre>

<p class="fragment fade-down">
Per aggiornare la repository locale si utilizza
</p>

<pre class="fragment"><code data-line-numbers>
    git pull

</code></pre>


Un comando utile per controllare lo stato dei file del progetto &#232;

<pre class="fragment"><code data-line-numbers>
    git status

</code></pre>



# QUALI SONO GLI AMBIENTI PI&#0217; UTILIZZATI?


Per sfruttare questo software, sono state create varie piattaforme che permettono una pi&#0249; comoda gestione di tutte le azioni riguardanti il proprio progetto.


## LE PI&#0217; UTILIZZATE SONO:


<div class="r-stack">
    <img  height="700" width="700" src="/images/github-logo.png">
    <p> <strong>GITHUB</strong> </p>
</div>


<div class="r-stack">
    <img  height="700" width="700" src="/images/gitlab-logo.png">
    <p> <strong>GITLAB</strong> </p>
</div>


<div class="r-stack">
    <img  height="700" width="575" src="/images/bitbucket-logo.svg">
    <p> <strong>BITBUCKET</strong> </p>
</div>


<div class="r-stack">
    <img  height="700" width="700" src="/images/sourceforge-logo.png">
    <p> <strong>SOURCEFORGE</strong> </p>
</div>


<div class="r-stack">
    <img  height="700" width="700" src="/images/gogs-logo.png">
    <p style="color: #000000"> <strong>GOGS</strong> </p>
</div>


<div class="r-stack">
    <img  height="700" width="700" src="/images/gitea-logo.png">
    <p style="color: #000000"> <strong>GITEA</strong> </p>
</div>



# COCNLUSIONI


&#0200; chiaro quindi che utilizzare un metodo di versionamento del codice, come Git, sia una risorsa estremamente utile per ogni sviluppatore <br> la nascita di questa modalit&#0224; ha portato una vera 

## RIVOLUZIONE

nel mondo della programmazione.
