In de eerste run van de security pipeline op de baseline applicatie zijn er problemen gevonden:

1. hardcoded password in docker-compose.yml
2. API key in appsettings.json
3. SQL injection vulnerability

In de opgave staat dat deze nu nog aanvaard mogen worden. Deze problemen worden later opgelost met BunkerWeb WAF voor puntje 3 en OpenBao voor 1 & 2.
