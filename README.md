# infra-devops


## jenkins

Revisar plugins instalados, en la consola de script de jenkins:

    Jenkins.instance.pluginManager.plugins.each{ plugin -> 
        println ("${plugin.getDisplayName()} (${plugin.getShortName()}): ${plugin.getVersion()
    }")
}

## Sonarqube
Contraseña por defecto tras primera instalacion
admin/admin
