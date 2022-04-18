# RepoVSC
Repositorio utilizando VScode

Este es un archivo README 

hola aquí estoy con la gente de RAS UNI :)

### Nilton está en busqueda de hospedaje
```python
class Nilton(Persona):
    def fit(self, X, k, n_iter=200):
        centers = random.sample(list(X), k)
        for i in range(n_iter):
            clusters = np.argmin(cdist(X, centers), axis=1)
            centers = np.array([X[clusters == c].mean(0) for c in clusters])
        return clusters
```
