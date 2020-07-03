apiVersion: entando.org/v1
kind: EntandoDeBundle
metadata:
  name: eng-346
  namespace: keb
  labels:
    widget: 'true'
    pageTemplate: 'true'
spec:
  details:
    name: ENG-346
    description: >-
      A bundle to use for testing ENG-346 functionalities.  Contains 1 widget
      with a config UI and a page template that uses that widget as defualt
      widget for a frame
    dist-tags:
      latest: v0.0.1
    versions:
      - v0.0.1
  tags:
    - version: v0.0.1
      shasum: eb6b7e3c56423a7721b1e6af209894980189d605
      integrity: eb6b7e3c56423a7721b1e6af209894980189d605
      tarball: 'https://github.com/kerruba-bundles/ENG-346.git'

