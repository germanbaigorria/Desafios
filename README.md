# Desafios

1° desafio: crear un contrato modular escalable de depositos para usuarios registrados;

2° desafio: crear una funcion dentro del contrato main para depositos en eth dentro del contrato MAIN;
 - crear un 2° contrato separado solo para ETH   (listo)
 - reutilizacion de contratos de registro de usuarios. (pendiente)

3º desafio:   Si Vaults está bloqueado → no se puede depositar.
 Si Vaults está desbloqueado → se permite depositar y el depósito pasa a "mempool" (una capa de staging),
 y luego es enviado a Vaults.
