# 🎮 Guia Rápido - Novos Comandos KiddieOS

## ⚡ Resumo Executivo

Seu shell do KiddieOS foi **turbinado** com 4 novos comandos! Agora você tem **27 comandos** disponíveis para fazer muito mais coisas.

---

## 🎯 Novos Comandos em 30 Segundos

| Comando | Função | Sintaxe |
|---------|--------|---------|
| **info** | Ver info do sistema | `info` |
| **copy** | Copiar arquivos | `copy origem destino` |
| **type** | Ver tipo de arquivo | `type arquivo` |
| **echo** | Imprimir texto | `echo texto` |

---

## 📚 Guia Detalhado

### 1. INFO - Diagnóstico do Sistema 🔍

**O que faz:**
- Mostra versão do kernel
- Exibe memória disponível
- Útil para diagnosticar problemas

**Como usar:**
```
> info
=== KiddieOS System Information ===
Kernel Version: 1.4
Available Memory: 624 KB
```

**Quando usar:**
- Verificar se há memória suficiente
- Confirmar versão do kernel
- Diagnosticar problemas de hardware

---

### 2. COPY - Gerenciar Arquivos 📋

**O que faz:**
- Copia arquivos de um lugar para outro
- Preserva atributos do arquivo
- Suporta caminhos de diretório

**Como usar:**
```
> copy arquivo.txt backup.txt
> copy dados.doc \backup\dados.doc
> copy programa.exe \apps\programa.exe
```

**Exemplos práticos:**
```
// Fazer backup de um arquivo importante
> copy importante.txt importante.bak

// Copiar para subpasta
> copy dados.txt \documentos\dados.txt

// Copiar múltiplos com mesmo nome
> copy config.sys config.old
```

**Quando usar:**
- Fazer backups de arquivos
- Duplicar arquivos
- Organizar arquivos em pastas

---

### 3. TYPE - Identificar Tipo de Arquivo 🔎

**O que faz:**
- Mostra que tipo de arquivo é
- Identifica extensão
- Valida compatibilidade

**Como usar:**
```
> type documento.txt
> type programa.exe
> type imagem.bmp
```

**Exemplo de saída:**
```
> type config.sys
Type: System Configuration File (SYS)

> type boot.bin
Type: Binary Executable (BIN)
```

**Quando usar:**
- Verificar tipo de arquivo desconhecido
- Confirmar extensão antes de usar
- Validar formato de arquivo

---

### 4. ECHO - Imprimir na Tela 📢

**O que faz:**
- Imprime texto na tela
- Útil para mensagens customizadas
- Perfeito para scripts

**Como usar:**
```
> echo Olá Mundo
Olá Mundo

> echo Sistema iniciado com sucesso
Sistema iniciado com sucesso

> echo KiddieOS v1.4 64MB RAM
KiddieOS v1.4 64MB RAM
```

**Exemplos criativos:**
```
// Criar mensagens de boas-vindas
> echo Bem-vindo ao KiddieOS!

// Informar status
> echo Backup concluído com sucesso!

// Criar separadores
> echo ===========================
```

**Quando usar:**
- Criar mensagens personalizadas
- Fazer scripts com saída
- Debugar programas
- Criar menus customizados

---

## 🚀 Exemplos de Uso Combinado

### Exemplo 1: Backup Automático
```
> echo Iniciando backup...
Iniciando backup...

> info
=== KiddieOS System Information ===
Kernel Version: 1.4
Available Memory: 624 KB

> copy importante.txt importante.bak
> copy dados.doc backup\dados.doc

> echo Backup concluído!
Backup concluído!
```

### Exemplo 2: Organizar Arquivos
```
> lf
(lista os arquivos)

> mkdir \backup
(cria pasta backup)

> copy programa.exe \backup\programa.exe
> copy dados.txt \backup\dados.txt

> echo Arquivos organizados!
```

### Exemplo 3: Diagnóstico do Sistema
```
> info
(mostra status do sistema)

> type sistema.ini
(verifica arquivo)

> echo Sistema pronto para operação
```

---

## 💡 Dicas e Truques

1. **Use echo para feedback**
   ```
   > echo Operação iniciada
   > copy arquivo.txt backup.txt
   > echo Operação finalizada
   ```

2. **Combine com cd para organizar**
   ```
   > cd \docs
   > copy documento.txt backup.doc
   > echo Arquivo salvo em docs/backup.doc
   ```

3. **Use echo para criar divisores**
   ```
   > echo ================================
   > echo ===  STATUS DO SISTEMA    ===
   > echo ================================
   > info
   ```

4. **Verifique tipos antes de operações**
   ```
   > type arquivo.txt
   > copy arquivo.txt copia.txt
   ```

---

## ⚙️ Especificações Técnicas

### Estatísticas do Shell Atualizado:

- **Comandos totais**: 27
- **Comandos novos**: 4
- **Arquivo modificado**: `shell16.asm`
- **Linhas adicionadas**: ~100
- **Compatibilidade**: 100% com versão anterior

### Comandos por Categoria:

**Sistema:**
- exit, reboot, shutdown, start

**Arquivo:**
- read, write, del, ren, mkdir, open, copy ⭐, type ⭐

**Diretório:**
- cd, assign, lf

**Dados:**
- bpb, fat, hex, disk, attrib, chmod

**Utilitários:**
- help, clean, echo ⭐, info ⭐

**Teste:**
- test, div

---

## 🔧 Resolução de Problemas

**O comando não funciona?**
- Verifique a sintaxe: `help [comando]`
- Certifique-se de ter permissões necessárias
- Recompile o kernel se fez alterações

**Memória insuficiente?**
- Use `info` para verificar
- Feche programas desnecessários
- Use `clean` para limpar a tela

**Arquivo não encontrado?**
- Use `lf` para listar arquivos
- Use `cd` para navegar entre pastas
- Use `type` para verificar arquivo

---

## 📞 Próximos Passos

Agora que seu shell é mais poderoso:

1. ✅ Experimente os novos comandos
2. ✅ Crie scripts com `echo`
3. ✅ Organize seus arquivos com `copy`
4. ✅ Monitore seu sistema com `info`
5. ✅ Explore as combinações possíveis

---

**Divirta-se explorando seu novo e poderoso KiddieOS Shell! 🎉**

*Para mais detalhes técnicos, consulte NOVOS_COMANDOS.md*
