# CSV-test

Consistem uma API de importação de CSV, usando typescript, express, prisma e o db postgres

Para conseguir inicializar a aplicação é necessário instalar as dependencias com o comando

"npm intall"

"npm install @prisma/client"

"npm i @prisma/engines"

npm install @prisma/client

npm i @prisma/engines

Em .env configurar conexão com um banco de dados postgres

No SQL Shell (Postgres) crie uma database com o nome

"csvdb"

Após isso é necessário criar a nova migrate do prisma com o comando

"npx prisma migrate dev"

De um nome para a migração

Quando a migração for criada, é necessário gerar as tabelas do banco, com o comando

"npx prisma generate"

Para inicialoza a aplicação é necessário digitar o comando

"npm run dev"

Com isso a aplicação deve subir na porta 3000

<<<<<<< HEAD
                            No Postman ou no Insomnia crie uma rota do tipo POST (localhost:3000/pagamentos), vá em form-data e defina 'KEY' como 'file', e insira o arquivo CSV desejado.

                            Também será possível acessar a rota do tipo GET (localhost:3000/Inadimplentes), que mostrará todas as matriculas que estão com o status em aberto


                            Também será possível acessar a rota do tipo GET (localhost:3000/inadimplencia/2022-01), que mostrará de acordo com o mês o resultado do cálculo esperado

                            a rota do tipo GET (localhost:3000/pagos), que mostrará todas as matriculas que estão com o status em pago

                            e por fim a rota do tipo GET (localhost:3000/total), que mostrará o csv com as inadimplencias.
=======
No Postman ou no Insomnia crie as seguintes rotas: 

                            a rota do tipo POST (localhost:3000/upload), vá em form-data e defina 'KEY' como 'file', e insira o arquivo CSV desejado.
                            
                            a rota do tipo GET (localhost:3000/Inadimplentes), que mostrará todas as matriculas que estão com o status em aberto

                            a rota do tipo GET (localhost:3000/pagos), que mostrará todas as matriculas que estão com o status em pago

                            a rota do tipo GET (localhost:3000/total), que mostrará o csv com as inadimplencias.

                            e por fim a rota do tipo GET (localhost:3000/inadimplencia/{Mes}), que no campo mes, for preenchido como janeiro, trará o valor de inadimplência de apenas aquele mês.
>>>>>>> 2750ec3e90e69498da8aaff8399d59ec75a694cf
