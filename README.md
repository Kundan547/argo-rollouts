# argo-rollouts

Argo Rollouts is a Kubernetes controller and set of CRDs (Custom Resource Definitions) that provide advanced deployment capabilities such as blue-green, canary, and progressive delivery strategies.

## Features

- **Blue-Green Deployments**
- **Canary Deployments**
- **Progressive Delivery**
- **Automated Rollbacks**
- **Metric Analysis Integration**

## Getting Started

1. **Install Argo Rollouts:**
   ```sh
   kubectl create namespace argo-rollouts
   kubectl apply -n argo-rollouts -f https://github.com/argoproj/argo-rollouts/releases/latest/download/install.yaml
   ```

2. **Deploy a Sample Rollout:**
   ```sh
   kubectl apply -f examples/rollout.yaml
   ```

3. **Monitor Rollouts:**
   ```sh
   kubectl argo rollouts get rollout <rollout-name>
   ```

## Documentation

- [Official Documentation](https://argoproj.github.io/argo-rollouts/)
- [GitHub Repository](https://github.com/argoproj/argo-rollouts)

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
