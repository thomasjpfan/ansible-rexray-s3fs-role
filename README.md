# Ansible Role for Docker S3FS Rexray Volume Plugin

Installs Rexyray AWS S3FS volume plugin.

## Variables

The following variables must be defined. A safe way to store these aws keys is to use Ansible Vault.

- `rexray_s3fs_accesskey`: AWS access key
- `rexray_s3fs_secretkey`: AWS secret key
- `rexray_s3fs_version`: rexray version

## License

MIT