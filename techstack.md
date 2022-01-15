## Tech stack
### Smart kontrakty
- Foundry
- Solidity
- Solmate
- The graph (Je možné že nepoužijeme, uvidíme jestli bude čas a chuť dělat subgraph)
### Frontend
- Nextjs
- Typescript
- Tailwind css
- Web3.js
------------
### Proč zrovna tohle?
#### Foundry
Jako naše prostředí pro vývoj smart kontraktů a tvorbu testů jsme se rozhodli použít Foundry. Je to přepracování DappTools, které jsou původně napsány v haskellu do rustu. Foundry poskytuje možnost psát všechny testy přímo v solidity. To nám umožňuje se při vývoji smart kontraktů nedotknout ts nebo js.
Foundry je extrémně rychlé a unix friendly.
#### Solmate
Nejefektivnější knihovna smart kontraktů co aktuálně existuje. Její používání vyžaduje trochu speciální pozornosti, protože pro rychlost byly například odstraněny nějaké memory safety checky a podobně. Knihovna je samozřejmě plná assembly magic. Knihovna má také implementovaný nový EIP-4626 standard, který chceme použít pro nás staking kontrakt.
#### Nextjs
Nejlepší meta framework pro reactjs o které vím. Má tunu funkcí, ale zároveň je opravdu rychlá.
#### Web3.js
Zvolil jsem Web3js jen proto, že s tím mám nějaké zkušenosti. Pokud se ale rozhodneme tak je možné že použijeme ethers.js.
