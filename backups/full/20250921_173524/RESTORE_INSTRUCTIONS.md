# Instrucciones de Restauración

## Archivo de Backup
- **Archivo**: blackstar_full_backup_20250921_173516.tar.gz
- **Tipo**: full
- **Fecha**: Sun Sep 21 17:35:24 UTC 2025
- **Tamaño**: 15M

## Restaurar desde este backup

### 1. Descargar el archivo
```bash
# Descargar desde GitHub
git clone https://github.com/darius-dev-blackstar/blackstar-backups.git
cd blackstar-backups
```

### 2. Extraer backup
```bash
# Extraer archivo de backup
tar -xzf backups/full/20250921_173524/blackstar_full_backup_20250921_173516.tar.gz
```

### 3. Restaurar sistema
```bash
# Usar scripts de restauración
./scripts/rollback-system.sh restore blackstar_full_backup_20250921_173516.tar.gz
```

## Información del Sistema
- **Servidor**: ip-172-31-21-46
- **Usuario**: ubuntu
- **Fecha de backup**: Sun Sep 21 17:35:24 UTC 2025
