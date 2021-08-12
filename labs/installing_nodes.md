### Enable JNLP port
1. Go to Manage Jenkin `http://18.191.185.219:8080/manage`
2. Select `Configure Global Security`
3. Under `Agents`, select `Fixed` and add `50000`. Click `Save`

### Install agent using `Launch agent by connecting it to the master`
1. Go to Jenkins dashboard `http://18.191.185.219:8080/`
2. Click `Build Executor Status`
3. Select `New Node`
4. Add `Node Name` as `windows_node` & Select `Permanent Agent`. Click `OK`
5. Add `Description` as `This is Windows Node`, `Number of executors` as `1`, `Remote root directory` as `C:\training\jenkins`, `Labels` as `windows`
6. Add `Usage` as `Only build jobs with labels expression matching this node`
7. Add `Launch Method` as `Launch agent by connecting it to the master`
8. Keep other options as `Deafult`. Click `Save`
