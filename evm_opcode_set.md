| STOP = 0x00 | EQ = 0x10       | ADDRESS = 0x30 | BLOCKHASH = 0x40 | POP = 0x50 | PUSH1 = 0x60 | LOG0 = 0xa0 | CREATE = 0xf0           |
| ----------- | --------------- | -------------- | ---------------- | ---------- | ------------ | ----------- | ----------------------- |
| ADD         | ISZERO          | BALANCE        | COINBASE         | MLOAD      | PUSH32       | LOG1        | CALL                    |
| MUL         | AND             | ORIGIN         | TIMESTAMP        | MSTORE     |**DUP1=0x80** | LOG2        | CALLCODE                |
| SUB         | OR              | CALLER         | NUMBER           | MSTORE8    | DUP16        | LOG3        | RETURN                  |
| DIV         | XOR             | CALLVALUE      | DIFFICULTY       | SLOAD      |**SWAP1=0x90**| LOG4        | DELEGATECALL            |
| SDIV        | NOT             | CALLDATALOAD   | GASLIMIT         | SSTORE     | SWAP16       |             | **SELFDESTRUCT = 0xff** |
| MOD         | BYTE            | CALLDATASIZE   |                  | JUMP       |              |             |                         |
| SMOD        | **SHA3 = 0x20** | CALLDATACOPY   |                  | JUMPI      |              |             |                         |
| ADDMOD      |                 | CODESIZE       |                  | PC         |              |             |                         |
| MULMOD      |                 | CODECOPY       |                  | MSIZE      |              |             |                         |
| EXP         |                 | GASPRICE       |                  | GAS        |              |             |                         |
| SIGNEXTEND  |                 | EXTCODESIZE    |                  | JUMPDEST   |              |             |                         |
| LT          |                 | EXTCODECOPY    |                  |            |              |             |                         |
| GT          |                 |                |                  |            |              |             |                         |
| SLT         |                 |                |                  |            |              |             |                         |
| SGT         |                 |                |                  |            |              |             |                         |
