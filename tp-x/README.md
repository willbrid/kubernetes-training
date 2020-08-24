Un noeud master et 2 noeuds workers

- time k3d cluster create hue --servers 1
- time k3d node create hue-worker1 -c hue
- time k3d node create hue-worker2 -c hue