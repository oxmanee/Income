<template>
  <v-card>
    <v-tabs background-color="#aeddff" v-model="active_tab">
      <v-tab v-for="item in menu" :key="item.index">{{ item.title }}</v-tab>
    </v-tabs>
  </v-card>
</template>

<script>
export default {
  name: "Menubar",
  data: () => ({
    active_tab: 4,
    menu: [
      { id: 1, title: "ข้อมูลหลัก" },
      { id: 2, title: "สถานะภาพสมรส" },
      { id: 3, title: "อาชีพ" },
      { id: 4, title: "ที่อยู่" },
      { id: 5, title: "รายได้" },
      { id: 6, title: "เอกสารแนบ" }
    ]
  })
};
</script>
