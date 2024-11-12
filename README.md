# AS221S6_T08_UtilityPay


# UtilityPay dApp - Plataforma de Pago de Servicios Públicos con Moneda Digital

**UtilityPay** es un contrato inteligente desarrollado en Solidity que permite a los usuarios registrados realizar pagos a servicios públicos utilizando una moneda digital. Los usuarios pueden agregar fondos, consultar su saldo y realizar pagos a servicios públicos de forma segura y transparente.

## Funcionalidades Principales

- **Registro de Usuarios**: Los usuarios pueden registrarse en el sistema para comenzar a usar la plataforma.
- **Agregar Fondos**: Los usuarios pueden depositar fondos en su cuenta dentro del contrato inteligente.
- **Realizar Pagos**: Los usuarios pueden realizar pagos a los servicios públicos registrados, siempre que tengan suficientes fondos.
- **Consulta de Saldo**: Los usuarios pueden verificar su saldo disponible en cualquier momento.

## Smart Contract

El contrato inteligente está implementado en Solidity y se encuentra completamente documentado utilizando **NatSpec** para facilitar su comprensión y uso.

### Funciones Clave

1. **registerUser**: Permite que un nuevo usuario se registre en la plataforma.
2. **addFunds**: Función para agregar fondos a la cuenta del usuario.
3. **payService**: Realiza un pago a un servicio público, especificando la cantidad y la dirección del servicio.
4. **checkBalance**: Consulta el balance del usuario registrado.