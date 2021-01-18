# Technikai problémák

## PowerShell

### ExecutionPolicy hiba
> Megoldás:
1. Nyiss egy új PowerShell ablakot adminisztrátorként (jobb gomb a windows gombra, PowerShell(rendergazdaként))
1. Add ki a következő parancsot: `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`
1. Amikor megkérdezi, hogy biztosan akarod-e, írd be az `A` betűt és enter.
