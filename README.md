## Challenge: Create a Dockerized infrastructure for running multiple Ethereum nodes on a single machine.
- Create a Dockerfile for an execution client (geth, etc.)
- Create a separate Dockerfile for a consensus client (pryzm, etc.)
- Create a separate Dockerfile for a monitoring service
- Create a Docker Compose file that runs them together `until the nodes are fully synchronized`

### Requirements
- Use the latest stable version of Ethereum client software (e.g., Geth ...)
- Use the latest stable version of chosen Consensus client (e.g., Pryzm ...)
- The Ethereum nodes should be able to communicate with each other over the local network created by Docker Compose
- The Ethereum nodes should expose the default RPC and WebSocket ports (8545 and 8546 for Geth, 8545 and 8546 for Parity)
- The Docker Compose file should include a separate container running a monitoring tool (e.g., Grafana or Prometheus) to monitor the nodes
- The monitoring tool should be able to retrieve a single metric:  `are the clients synced, if not how close to sync are they?`

### Solution
- Include a solution.md that describes how to run and test your solution
- Create a branch:  your_name/feature/description
- Make a pull request when done!
- PLEASE do not spend more than 4 hours on this.  We can go over what's completed.

