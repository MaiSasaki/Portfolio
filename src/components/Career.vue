<template>
  <v-container>
    <v-row>
      <v-col>
        <v-list>
          <v-row v-for="(item, index) in items" :key="index">
            <v-col md="2" class="pb-6" style="background-color: #f8f5e9">
              {{ item.date }}
            </v-col>
            <v-col md="10" style="background-color: #f8f5e9">
              {{ item.title }}
            </v-col>

            <!-- <v-list-item-content class="py-1">
              <v-list-item-title>
                
              </v-list-item-title>
              <v-list-item-subtitle>
               
              </v-list-item-subtitle>
            </v-list-item-content> -->
          </v-row>
        </v-list>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    items: [
      { date: "2020.02", title: "HTML,CSSを独学で習得" },
      { date: "2020.06", title: "JavaScriptを授業で習得" },
      { date: "2020.08", title: "Vue.jsを参考書など独学で学習" },
      { date: "2020.09", title: "株式会社エクサ　5daysサマーインターン参加" },
      { date: "2020.11", title: "Vue.jsを使ってWebアプリ作成" },
      { date: "2020.12", title: "アイケイケイ株式会社　2daysウィンターインターン参加" },
      { date: "2021.01", title: "ウィンターハッカソン参加" },
      { date: "2021.02", title: "自己紹介ポートフォリオ作成" },
    ],
  }),
};
</script>

<style>
</style>