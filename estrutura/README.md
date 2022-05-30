# Estrutura de pastas 📁
A estrutura de pastas são importantes para manter o projeto organizado.

#
## 👨‍💻 Pasta src
A pasta ``src`` e onde colocamos os arquivos ``.ts``

## 🔥 Pasta build
A pasta build é onde ficam os arquivos .js depois da compilação depois de rodar:
```sh
tsc nomedoarquivo.ts
```

* Configurando as pastas no ``ts.config``

    Para configurar a pasta ``build`` procuramos a linha `outDir`, em seguida passamos a pasta na qual queremos que sejam gerados os builds 
    ```json
    ...
    "outDir": "./build", 
    ]
    ```

    Para configurar a pasta ``src`` procuramos a linha `rootDir`, em seguida passamos a pasta que usaremos para desenvolver nossos codigos em ``Typescript``
    ```json
    ...
    "rootDir": "./src",
    ]
    ```