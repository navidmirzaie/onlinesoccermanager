
### Domeinen

- clubs
- leagues
- players
- match

### Leagues

voorlopig selectie uit twee leagues:

1. Premier League
2. Eredvisie

### Clubs

**PL**

1. Mancheter united
2. Manchester city
3. Chelsea
4. Arsenal
5. Liverpool
6. Tottenham Hotspur

**Eredivisie**

1. Ajax
2. Feyenoord
3. AZ
4. Vitesse
5. PSV
6. Utrecht

### Relaties van domeinen tot elkaar

- League heeft clubs -> Club heeft spelers -> spelers -> statistieken
- statistieken clubs zullen: Keeper, verdediging, middenveld en aanval zijn.

score club statistieken:
`Math.floor((Keeper + verdediging + middenveld + aanval) / 4)`

Een match bestaat uit 2 teams

- TeamA vs teamB
- teamA is thuisspelend team
- Thuisspelend team heeft een extra geluksfactor van x (nader te bepalen)
- een match duurt 90 minuten (pak hem beet 5 minuten versneld)
- een match heeft 2e helften waarvan deze per helft 45 minuten duren (2.5 minuut)



