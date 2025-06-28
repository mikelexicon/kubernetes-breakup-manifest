# Breakup-Manifest
> A Kubernetes ConfigMap breakup sonnet—shipping heartbreak as code.

---

## What is this?

`breakup-manifest.yaml` is a perfectly valid Kubernetes **ConfigMap** whose  
`message.txt` key stores a 10-couplet sonnet about pods parting ways, failing  
liveness probes, and deleting love with `kubectl`.  
Half demo, half comedy, 100 % YAML.

---

## Quick start

```
apply the ConfigMap

kubectl apply -f breakup-manifest.yaml

read the sonnet

```

---

## Example output

```

To you, my dear, I now must say goodbye;           \# 1
Our pods once paired now drift on diff'rent tides. \# 2
The node that held us warm grows cold and dry,     \# 3
A rolling surge deletes what love provides.        \# 4
Liveness now fails within this weary heart,        \# 5
Readiness gates deny all traffic through.          \# 6
The service mesh unwinds; we stand apart,          \# 7
No ingress left to forward me to you.              \# 8
Accept this helm and chart your course anew;       \# 9
I run delete—our joint release is done.            \#10

```

---

## Why?

Because DevOps deserves poetry too.  
Use it as a demo file, a stand-up ice-breaker, or a reminder that even micro-services can feel macro-emotions.

---

## License

MIT — see LICENSE for details.
