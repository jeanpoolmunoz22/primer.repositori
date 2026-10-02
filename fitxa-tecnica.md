# Fitxa tècnica: Instal·lació i configuració d'Ubuntu

## Objectiu

Documentar els passos bàsics per instal·lar i configurar Ubuntu en un ordinador o màquina virtual.

## Materials

- Un ordinador.
- Una màquina virtual o un ordinador de proves.
- Una imatge ISO d'Ubuntu.
- Connexió a Internet.

## Procediment

1. Comprovar que l'ordinador compleix els requisits d'Ubuntu.
2. Descarregar la imatge ISO des de la pàgina oficial.
3. Crear una màquina virtual i assignar-hi memòria RAM i disc.
4. Carregar la imatge ISO i iniciar l'instal·lador.
5. Seguir les instruccions i completar la instal·lació.
6. Reiniciar la màquina virtual i iniciar sessió.
7. Comprovar que el sistema funciona correctament.

## Comprovacions

- [ ] Ubuntu s'inicia correctament.
- [ ] La connexió a Internet funciona.

## Incidències i solucions

| Incidència | Solució |
|---|---|
| No hi ha connexió a Internet | Revisar la configuració de xarxa. |
| L'ordinador no inicia Ubuntu | Revisar l'ordre d'arrencada. |

## Recursos

- [Documentació oficial d'Ubuntu](https://ubuntu.com/tutorials)
- [Documentació de GitHub](https://docs.github.com/)

## Imatge del procés

![Logotip d'Ubuntu](https://assets.ubuntu.com/v1/29985a98-ubuntu-logo32.png)

## Exemple de comanda

Per consultar la versió del sistema, podem executar:

```bash
lsb_release -a
```
## Historial i recuperació de canvis

La comanda `git log --oneline` permet consultar els commits anteriors. Amb `git show` podem veure els detalls d'un commit. Consultar l'historial ajuda a saber quins canvis s'han fet al document.
