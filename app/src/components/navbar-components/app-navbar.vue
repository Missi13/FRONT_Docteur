<template>
    <v-navigation-drawer floating permanent width="100%" height="100%">
        
        <v-list dense nav color="#F1F1F1" height="100%">

            <v-list-item-group v-model="selectedItem" color="#335c67" height="100%" d-flex align-content-space-around>

                <!-- Mon compte -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-view-dashboard</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Mon compte</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <v-divider></v-divider>

                

                <!-- Liste des patients -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-view-dashboard</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Liste des patients</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Consultation -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-image</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Consultation</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Ordonnance -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Ordonnance</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Exploration -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Exploration</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Certificats -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Certificats</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Pièces jointes -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Pièces jointes</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Protocoles -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Protocoles</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Historique -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Historique</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Réglement -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Réglement</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Rendez-vous -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Rendez-vous</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Paramètres -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Paramètres</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Statistiques -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Statistiques</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>

                <!-- Manuel d'utilisation -->
                <v-list-item link>
                    <v-list-item-icon>
                        <v-icon>mdi-help-box</v-icon>
                    </v-list-item-icon>
                    <v-list-item-content>
                        <v-list-item-title>Manuel d'utilisation</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </v-list-item-group>
        </v-list>
    </v-navigation-drawer>
</template>

<script>
export default {
    data() {
        return {
            selectedItem: 0
        }
    },
}
</script>

<style scoped>
.navbar {
    background-color: aquamarine;
}
</style>