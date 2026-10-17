# MDF CDN do LD Project

Arquivos que a Central de Catálogos do LD Project baixa:

- `catalogos_mdf.json`: catálogos disponíveis (versão, tamanho e SHA-256 de cada pacote).
- `catalogos_mdf.json.sig`: assinatura Ed25519 do manifesto.
- `chave_publica.txt`: a chave que o LD Project usa para conferir a assinatura.
- Os pacotes `ld_<fabrica>.zip` ficam nas releases.
