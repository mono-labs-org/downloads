# Monolythium Desktop Wallet — APT Repository

## Installation

```bash
# Add GPG key
curl -fsSL https://mono-labs-org.github.io/downloads/monolythium.gpg.key | sudo gpg --dearmor -o /usr/share/keyrings/monolythium.gpg

# Add repository
echo "deb [signed-by=/usr/share/keyrings/monolythium.gpg] https://mono-labs-org.github.io/downloads stable main" | sudo tee /etc/apt/sources.list.d/monolythium.list

# Install
sudo apt update
sudo apt install monolythium-wallet
```

## Updates

```bash
sudo apt update && sudo apt upgrade monolythium-wallet
```
