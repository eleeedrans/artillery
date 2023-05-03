Test de Carga usando artillery

https://www.artillery.io/docs/

Requisitos: Tener instalado NodeJs


Para comenzar el test:
1) Instalar los paquetes con npm install
2) Ejecutar script principal con npm start


Variables para modificar:
    - Target: la baseUrl de nuestro server
    - data.csv: Ahi va la data de userId, Amount, PreBalance, PostBalance, UserId y SequenceNumberPerPlayer en formato csv
    - phases[0].duration: Cuanto queremos que dure el test
    - phases[0].arrivalRate: Cuantas solicitudes queremos que aparezcan por segundo
