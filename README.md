# KS-Datahub Module Registry in GitHub

HiveMQ datahub modules

na upload:
                   https://github.com/floresboy/KS-Datahub/blob/main/move2topic_value-1.0.0.module
                   > shasum -a 512 Calculate-mov-avg-1.0.0.module
verandeer in :

            "url": "https://raw.githubusercontent.com/floresboy/KS-Datahub/main/move2topic_value-1.0.0.module",
            "shasum512": "89712d2616cf4e951a3c4a29affa578ec951a74b0071129a5d043aa3a93703d89f1bc55202f851ddd0e9851f0a86ccc4f0d4d6922ad57b33e43ffda832bd4ee8"

            
# pas aan in broker config.xml:
    <data-hub>
        <modules>
            <registries>
                <remote>
                    <enabled>true</enabled>
                    <name>KS Git Registry</name>
                    <id>ks-git-registry</id>
                    <url>https://raw.githubusercontent.com/floresboy/KS-Datahub/refs/heads/main/registry.json</url>
                </remote>
            </registries>
        </modules>
    </data-hub>
    
