# llama3-on-akash
Deploy Llama 3 70B with 16-bit quantization on Akash Network

The project is developed for the **Llama 3 on Akash Network** zealy task which is hosted by [Akash](https://zealy.io/cw/akashnetwork/questboard).

## Deploy on Akash guide




- First you need to create a huggingface account and get access to the model from [here](https://huggingface.co/meta-llama/Meta-Llama-3-70B-Instruct)
  - You need to agree to share your contact information to access the model
- Create an [access token](https://huggingface.co/settings/tokens) and use it to replace **hf_yourtoken** in [deploy.yaml](deploy.yaml)
- Create and fund a Keplr or Leap wallet
  - [Keplr wallet](https://akash.network/docs/getting-started/token-and-wallets/#keplr-wallet)
  - [Leap wallet](https://akash.network/docs/getting-started/token-and-wallets/#leap-cosmos-wallet)
- Visit https://deploy.cloudmos.io/
- Connect your wallet
  - You need to have at least 0.5 AKT in your wallet
- Press the deploy button
- Select "Build your template"
- (Optional) Name your deployment
- Select YAML and paste the [deploy.yaml](deploy.yaml) contents
- Press "Create Deployment"
- Accept wallet transaction
- Review bids and select provider
- Accept provider transaction
- Go to LEASES and press the URI
- Check the [Akash docs](https://akash.network/docs/deployments/cloudmos-deploy/) if you have and questions
- Type nvidia-smi in the console to verify GPU usage
- Llama 3 is deployed!
