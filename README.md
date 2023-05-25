# cloud9-ide-backend

Cloud9 related tools and scripts.

## scripts/stop-if-inactive.sh

```bash
sudo mv ~/.c9/stop-if-inactive.sh ~/.c9/stop-if-inactive.sh-old
curl https://raw.githubusercontent.com/GrahamOHagan/cloud9-ide-backend/main/scripts/stop-if-inactive.sh -o ~/.c9/stop-if-inactive.sh
sudo chown root:root ~/.c9/stop-if-inactive.sh
sudo chmod 755 ~/.c9/stop-if-inactive.sh
```
