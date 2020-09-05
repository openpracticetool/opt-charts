# Open Practice Tool: Helm CHarts

In this repository you will find some Helm charts used for Open Practice Tool as platform or to develop it.

## Charts

### Stable

* Red Hat Single Sign On.

### Incubator

* Apicurio.
* Microcks.

## How to use this repo

1. Install [Helm CLI](https://helm.sh/docs/intro/install/) on you workstation.

2. Register this repository:

   ```bash
   $ helm repo add opt-repo https://openpracticetool.github.io/opt-charts/
   ```

3. And Choose wisely:

   ```bash
   $ helm search repo opt-repo
   ```
