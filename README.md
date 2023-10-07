# HelmCharts
Zero to Hero Helm Chart

What is Helmcharts?
Why is it used?
How to use helm?
Sample helm chart
Interview Questions?
Materials

Three big concepts
A chart is a helm package. it contains all the necessary resources definition to run an application,tool,or service inside of a kubernetes cluster, Think of it the kubernetes equialent of a homebrew formula, an apt,dpkg,or a yum RPM file.

A Repository is the place where charts 


A Release is an instance of a chart running in a kubernetes cluster. One chart can be often be installed many times into the same cluster and each time it is installed, a new release is created. cnsider a Mysql chart, if you want two databases running in your cluster, you can install that chart twice. Each one will have it's own release which will in turn have its own release name with these concepts in mind we can now explain Helm like this:

Helm installs resources in the specific orders:

Helm doc_url: https://helm.sh/docs/
