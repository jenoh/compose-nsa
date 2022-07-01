# ANSIBLE
Les [configs ansible](/ansible/) nous permettent de redéployer au besoin les services de DB ou les applications web pour résoudre les incidents.
Les VMs sont configurables dans [l'inventory ansible](/ansible/inventory/azure/hosts)

# GITHUB WORKFLOW
Le workflow [deploy-web](/.github/workflows/deploy-web.yml) permet de lancer ansible avec la configuration susmentionnée, et donc de redéployer en un clic.