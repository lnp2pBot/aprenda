# Documentação em Português

[Site com a Documentação em Português](https://mostro.network/protocol/)

## Para contribuidores

### Requisitos

* Instalar [Just](https://github.com/casey/just)
```bash
cargo install just
```

### Procedimentos

#### Inicializar o projeto

Inicializa o projeto de documentação mdBook com as dependências necessárias.

```bash
just init
```

#### Servir localmente

Inicia um servidor de desenvolvimento local com recarregamento automático para pré-visualização.

```bash
just serve
```

#### Compilar a documentação

Gera o site de documentação estática para implantação em produção.

```bash
just build
```