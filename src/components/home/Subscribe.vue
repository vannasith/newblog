<template>
  <v-container
    id="subscribe"
    tag="section"
  >
    <base-card
      color="blue-grey lighten-5"
      class="pa-3"
    >
      <v-container>
        <v-row>
          
          <v-col
            cols="12"
            
          >
            <base-subheading>Contact</base-subheading>

            <v-list class="transparent">
              <v-list-item >
                <v-list-item-avatar
                  color="primary"
                >
                  <v-icon
                    class="elevation-4"
                    dark
                  >
                    mdi-email-outline
                  </v-icon>
                </v-list-item-avatar>
                <v-list-item-content>
                <v-list-item-title>EMAIL</v-list-item-title>

                <v-list-item-subtitle>
                  THEARTOFTRAVEL@GMAIL.COM
                </v-list-item-subtitle>
                </v-list-item-content>
             
                <v-list-item-avatar color="primary">
                  <v-icon
                    class="elevation-4"
                    dark
                  >
                    mdi-map-marker
                  </v-icon>
                </v-list-item-avatar>
                <v-list-item-content>
                <v-list-item-title>ADDRESS</v-list-item-title>

                <v-list-item-subtitle>
                  1234 WORLD DR. HERE, TX 76123
                </v-list-item-subtitle>
                </v-list-item-content>
              
                <v-list-item-avatar color="primary">
                  <v-icon
                    class="elevation-4"
                    dark
                  >
                    mdi-phone
                  </v-icon>
                </v-list-item-avatar>
                <v-list-item-content>
                <v-list-item-title>PHONE</v-list-item-title>

                <v-list-item-subtitle>
                  555-789-1234
                </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-list>
          </v-col>
        </v-row>
      </v-container>
    </base-card>
  </v-container>
</template>

<script>
  export default {
    name: 'HomeSubscribe',
  }
</script>
