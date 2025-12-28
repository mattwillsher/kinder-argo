# kinder-argo

Argo CD app-of-apps for [kinder](https://github.com/mattwillsher/kinder) cluster infrastructure.

## Applications

| App | Wave | Purpose |
|-----|------|---------|
| cert-manager | -3 | Certificate management & CRDs |
| trust-manager | -2 | CA bundle distribution |
| traefik | -1 | Ingress & Gateway API |

## Usage

```bash
kubectl apply -f root-app.yaml
```

## Configuration

Edit `apps/values.yaml` to adjust chart versions or disable components.
