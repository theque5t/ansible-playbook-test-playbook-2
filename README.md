# Ansible Playbook: Test Playbook 2

Test playbook

## Requirements

None.

## Playbook Variables

- `pause`
  - **Required:** True
  - **Comments:** Used to enable/disable `pause` tasks
  - **Choices:**
    - `true`: Enable
    - `false`: Disable
  - **Default:** False

- `pause_seconds`
  - **Required:** True
  - **Comments:** Used to fill in the `seconds` attribute on `pause` tasks
  - **Default:** None.

## Dependencies

See [dependencies.yml](./dependencies.yml)

## Example Run

```sh
ansible-playbook /path/to/playbook.yml
```

## License

[MIT](./LICENSE)

## Author Information

Trevor Highfill ([@theque5t](https://github.com/theque5t))
