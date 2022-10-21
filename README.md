# Tour de App - Laravel boiler plate

Šablona pro vývoj aplikace pro Tour de App společně s vytvořením a nahráním výstupu

## Lokální spuštění

    docker build . -t tda-laravel
    docker run -p 8080:80 -v "$(pwd)":/app tda-laravel

## Odevzdání
V rámci GitHub akce se aplikace automaticky odevzdává, jediné co je potřeba udělat je v rámci repozitáře si nastavit svůj vlastní TEAM\_SECRET, který dostanete po registraci do soutěže
