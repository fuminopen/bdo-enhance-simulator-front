<template>
  <v-app>
    <!-- ナビゲーションバー -->
    <v-app-bar app color="indigo" dark>
      <v-toolbar-title>Nuxt 3 & Vuetify Sample Page</v-toolbar-title>
    </v-app-bar>

    <v-navigation-drawer permanent> Navigation Drawer </v-navigation-drawer>

    <!-- メインコンテンツエリア -->
    <v-main>
      <v-container>
        <v-row justify="center">
          <v-col cols="12" md="8">
            <h1>Welcome to Your Nuxt 3 & Vuetify App</h1>
            <p>This is a sample page using Nuxt 3 and Vuetify.</p>
            <!-- サンプルのボタン -->
            <v-btn color="primary" dark>Click Me</v-btn>
          </v-col>
        </v-row>
      </v-container>
    </v-main>

    <!-- フッター -->
    <v-footer app padless>
      <v-col class="text-center" cols="12">
        © {{ new Date().getFullYear() }} - Nuxt 3 & Vuetify Sample
      </v-col>
    </v-footer>
  </v-app>
</template>

<script setup>
// この部分に必要に応じてJavaScriptのコードを追加できます。
</script>

<style scoped>
/* この部分に必要に応じてスタイルを追加できます */
</style>
