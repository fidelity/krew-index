# Fidelity's Krew Plugin Index

An index for [Krew](https://krew.sigs.k8s.io) that contains kubectl plugins that are published as part of Fidelitys Open Source work.

## Usage

To use the index you will need to run the following command once:

```bash
$ kubectl krew index add fidelity https://github.com/fidelity/krew-index.git
```

To then use the index to install a plugin called `foo` you would run the following command:

```bash
$ kubectl krew install fidelity/foo
```

## Additional Information

Additional documentation for Krew can be found [here](https://krew.sigs.k8s.io/docs/).