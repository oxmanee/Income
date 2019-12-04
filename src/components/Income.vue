<template>
  <div>
    <Regular />
    <Profession />
    <Business />
    <Another />
    <v-container
      ><v-layout row>
        <v-flex md7>
          <v-layout>
            <v-flex md1> </v-flex>
            <v-flex md4>
              <v-subheader style="color:red;">รายได้เฉลี่ยรวมต่อเดือน</v-subheader>
            </v-flex>
            <v-flex md3>
              <v-subheader
                ><v-text-field
                  type="number"
                  value="0"
                  style="text-align:right;"
                ></v-text-field
              ></v-subheader>
            </v-flex>
            <v-flex md2> <v-subheader style="color:red;">บาท/เดือน</v-subheader></v-flex>
            <v-flex md2> </v-flex>
            <v-flex md1> </v-flex>
          </v-layout>
        </v-flex>
        <v-flex md3> </v-flex>
        <v-flex md2> </v-flex
      ></v-layout>
    </v-container>
  </div>
</template>

<script>
import Regular from "./Income/Regular";
import Profession from "./Income/Profession";
import Business from "./Income/Business";
import Another from "./Income/Another";
export default {
  name: "Income",
  components: {
    Regular,
    Profession,
    Business,
    Another
  },
  data: () => ({
    //
  })
};
</script>
<style>
.v-text-field__slot input {
  text-align: right;
}
</style>
