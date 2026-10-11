# Pretorio: rilasci

Pretorio sorveglia le connessioni in ingresso alle cartelle condivise di un PC Windows.

In [Releases](https://github.com/officinatributaria/pretorio-rilasci/releases) si trovano i file
di installazione firmati da Officina Tributaria S.p.A.:

- `PretorioSetup-X.Y.Z.exe`: file unico per Windows a 64 bit; sceglie da solo ARM64 o x64;
- `PretorioSetup-X.Y.Z-win-arm64.msi` e `-win-x64.msi`: i pacchetti per un'installazione a mano;
- `aggiornamento.json` e `aggiornamento.json.firma`: li legge Pretorio per proporre gli
  aggiornamenti. Installa solo file firmati con il certificato di Pretorio.

Il codice sorgente non è in questo repository.
