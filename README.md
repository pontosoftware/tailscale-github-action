# GitHub Action - Connect to Tailscale with Exit Node

#### Usage

```yaml
  - name: Tailscale
    uses: pontosoftware/tailscale-github-action@v1
      with:
        authkey: ${{ secrets.TAILSCALE_AUTHKEY }}
        exit_node_ip: ${{ secrets.TAILSCALE_EXIT_NODE_IP }}
```

See [Ephemeral AuthKeys](https://tailscale.com/kb/1111/ephemeral-nodes/)
