# erc-20
ERC20

Datos relevantes:

- La función totalSupply devuelve la cantidad total de tokens ERC20.

- La función balanceOf devuelve la cantidad de tokens ERC20 que hay en una cuenta.

- La función transfer permite a un titular de tokens ERC20 transferir una cantidad de tokens a un destinatario.

- Un propietario de tokens ERC20 puede llamar a la función approval para aprobar que un operador (en el código éste es denominado spender) gaste tokens suyos.

- Al llamar a la función allowance, se puede saber cuánto se le permite gastar a un operador del saldo de un propietario de tokens ERC20, y después de que se haya aprobado que un operador gaste tokens de ese saldo, éste puede llamar a la función transferFrom para transferir una cierta cantidad de tokens desde el propietario a un destinatario.

Highlighted facts:

- The totalSupply function returns the total amount of an ERC20 token.

- The balanceOf function returns the amount of an ERC20 token that an account has.

- The transfer function allows a holder of an ERC20 token to transfer an amount of tokens to a recipient.

- An owner of an ERC20 token can call the approve function to approve a spender to spend tokens of theirs.

- By calling the allowance function, it can be known how much a spender is allowed to spend from the balance of an ERC20 tokens' owner, and after a spender has been approved to spend from that balance, they can call the transferFrom function to transfer a certain amount of tokens from the owner to a recipient.
