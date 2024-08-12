# Install the latest version of yandex cloud cli

## Example usage

```yaml
- name: Try to install yc cli and login into yandex cloud
  uses: lxhan/yc-install@v1
  with:
    SA_KEY: your service account private key (json form) [optional]
```

_**(eng)**_ This will install the latest version of yandex cloud cli. Then
logging in if SA_KEY parameter is provided.

_**(rus)**_ Устанавливает последнюю версию yc cli. Выполняет логин если указан
SA_KEY.

## Outputs

none
