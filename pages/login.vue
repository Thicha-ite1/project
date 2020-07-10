<template>
 <v-app>
   <v-card>
     <v-card-title>
       <h1>Login</h1>
     </v-card-title>
     <v-card-text>

       <v-form>
         <v-text-field label="Username" 
         prepend-icon="mdi-account-circle"/>
       </v-form>

       <v-form>
         <v-text-field type="Password" label="Password" prepend-icon="https" append-icon="visibility_off"/>
       </v-form>

        <v-card-actions>
            <nuxt-link to="register"><v-btn depressed large color="success">Ragister</v-btn></nuxt-link>
            <v-spacer></v-spacer>
            <nuxt-link to=""><v-btn depressed large color="primary">Login</v-btn></nuxt-link>
        </v-card-actions>

     </v-card-text>
   </v-card>
 </v-app>
</template>