## Compatibilidade do Java com o Spigot

Este guia oferece informações sobre a compatibilidade do Java com diferentes versões do Spigot.

### Resumo

| Versão do Spigot | Versão mínima do Java | Razão |
|---|---|---|
| 1.8 - 1.16.5 | Java 8 | Suporte a APIs legadas |
| 1.17 - 1.18.2 | Java 16 | Alterações na API e no bytecode |
| 1.19+ | Java 17 | Alterações na API e no bytecode |

### Detalhes

#### Java 8 para Spigot 1.8 - 1.16.5

O Java 8 é a versão mínima recomendada para todas as versões do Spigot até 1.16.5. Versões anteriores do Java podem não funcionar corretamente com essas versões do Spigot devido ao suporte a APIs legadas.

#### Java 16 para Spigot 1.17 - 1.18.2

O Spigot 1.17 e 1.18.2 requerem Java 16 devido a alterações significativas na API e no bytecode. O Java 8 não é compatível com essas versões do Spigot.

#### Java 17 para Spigot 1.19+

O Spigot 1.19 e posteriores requerem Java 17 devido a mudanças substanciais na API e no bytecode. O Java 8 e o Java 16 não são compatíveis com essas versões do Spigot.

### Solução de Problemas

Se estiver enfrentando problemas ao executar o Spigot, verifique se está usando a versão correta do Java. Você pode verificar a versão do Java em seu sistema usando o seguinte comando:

```
java -version
```

Se estiver usando uma versão do Java que não é compatível com a versão do Spigot que está tentando executar, será necessário instalar a versão correta do Java.

### Recursos Adicionais

* [Site do Spigot](https://www.spigotmc.org/): Visite o site oficial do Spigot para obter mais informações sobre o servidor Minecraft baseado em Bukkit.
* [Documentação do Spigot](https://www.spigotmc.org/wiki/spigot-installation/): Acesse a documentação oficial do Spigot para obter guias de instalação e outras informações úteis.
* [Documentação do Java](https://docs.oracle.com/javase/8/docs/technotes/guides/versioning/): Consulte a documentação oficial do Java para obter detalhes sobre versões e compatibilidade.

### Observações

* Este guia é apenas uma referência geral. Consulte a documentação do Spigot para obter informações mais detalhadas sobre a compatibilidade do Java.
* As informações neste guia estão sujeitas a alterações. Certifique-se de verificar regularmente as atualizações e anúncios do Spigot para obter as informações mais recentes.
