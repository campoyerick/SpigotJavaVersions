## Compatibilidade do Java com o Spigot

Este README fornece informações sobre a compatibilidade do Java com diferentes versões do Spigot.

### Resumo

| Versão do Spigot | Versão mínima do Java | Motivo |
|---|---|---|
| 1.8 - 1.16.5 | Java 8 | Suporte a APIs legadas |
| 1.17 - 1.18.2 | Java 16 | Mudanças na API e no código de bytecode |
| 1.19+ | Java 17 | Mudanças na API e no código de bytecode |

### Detalhes

#### Java 8 para Spigot 1.8 - 1.16.5

O Java 8 é a versão mínima recomendada para todas as versões do Spigot até 1.16.5. As versões anteriores do Java podem não funcionar corretamente com essas versões do Spigot.

#### Java 16 para Spigot 1.17 - 1.18.2

O Spigot 1.17 e 1.18.2 requer Java 16 devido a mudanças na API e no código de bytecode. O Java 8 não é compatível com essas versões do Spigot.

#### Java 17 para Spigot 1.19+

O Spigot 1.19 e superior requer Java 17 devido a mudanças na API e no código de bytecode. O Java 8 e o Java 16 não são compatíveis com essas versões do Spigot.

### Solução de problemas

Se você estiver enfrentando problemas ao executar o Spigot, verifique se está usando a versão correta do Java. Você pode verificar a versão do Java em seu sistema usando o seguinte comando:

```
java -version
```

Se você estiver usando uma versão do Java que não é compatível com a versão do Spigot que você está tentando executar, você precisará instalar a versão correta do Java.

### Recursos adicionais

* Site do Spigot: [https://www.spigotmc.org/](https://www.spigotmc.org/)
* Documentação do Spigot: [https://www.spigotmc.org/wiki/spigot-installation/](https://www.spigotmc.org/wiki/spigot-installation/)
* Documentação do Java: [https://docs.oracle.com/javase/8/docs/technotes/guides/versioning/](https://docs.oracle.com/javase/8/docs/technotes/guides/versioning/)

### Observações

* Este README é apenas um guia geral. Consulte a documentação do Spigot para obter informações mais detalhadas sobre a compatibilidade do Java.
* As informações neste README estão sujeitas a alterações.
