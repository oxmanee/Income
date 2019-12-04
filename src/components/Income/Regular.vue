<template>
  <v-container>
    <v-layout row>
      <v-checkbox :label="`รายได้ประจำ`"></v-checkbox>
    </v-layout>
    <v-layout row>
      <v-card class="mx-auto" width="100%" outlined>
        <v-card-text>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-subheader>เงินเดือน</v-subheader>
              </v-flex>
              <v-flex md3>
                <v-subheader
                  ><v-text-field
                    style="text-align:right;"
                    type="number"
                    value="0"
                  ></v-text-field
                ></v-subheader>
              </v-flex>
              <v-flex md2>
                <v-subheader>บาท/เดือน</v-subheader>
              </v-flex>
            </v-layout>
          </v-container>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-subheader>ค่าตอบแทนประจำเดือน</v-subheader>
              </v-flex>
              <v-flex md3>
                <v-subheader
                  ><v-text-field
                    style="text-align:right;"
                    type="number"
                    value="0"
                  ></v-text-field
                ></v-subheader>
              </v-flex>
              <v-flex md2>
                <v-subheader>บาท/เดือน</v-subheader>
              </v-flex>
            </v-layout>
          </v-container>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-layout>
                  <v-flex md2>
                    <v-subheader>รายได้ผันแปร</v-subheader>
                  </v-flex>
                  <v-flex md1>
                    <v-subheader>เฉลี่ย</v-subheader>
                  </v-flex>
                  <v-flex md2>
                    <v-subheader
                      ><v-text-field
                        style="text-align:right;"
                        type="number"
                        value="0"
                      ></v-text-field
                    ></v-subheader>
                  </v-flex>
                  <v-flex md2>
                    <v-subheader>เดือน</v-subheader>
                  </v-flex>
                  <v-flex md5>
                    <v-subheader
                      ><v-text-field style="text-align:right;"></v-text-field
                    ></v-subheader>
                  </v-flex>
                </v-layout>
              </v-flex>
              <v-flex md3>
                <v-subheader
                  ><v-text-field
                    style="text-align:right;"
                    type="number"
                    value="0"
                  ></v-text-field
                ></v-subheader>
              </v-flex>
              <v-flex md2>
                <v-subheader>บาท/เดือน</v-subheader>
              </v-flex>
            </v-layout>
          </v-container>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-layout>
                  <v-flex md2>
                    <v-subheader>รายได้อื่นๆ</v-subheader>
                  </v-flex>
                  <v-flex md1>
                    <v-subheader>เฉลี่ย</v-subheader>
                  </v-flex>
                  <v-flex md2>
                    <v-subheader
                      ><v-text-field
                        style="text-align:right;"
                        type="number"
                        value="0"
                      ></v-text-field
                    ></v-subheader>
                  </v-flex>
                  <v-flex md2>
                    <v-subheader>เดือน</v-subheader>
                  </v-flex>
                  <v-flex md5> </v-flex>
                </v-layout>
              </v-flex>
              <v-flex md3>
                <v-subheader
                  ><v-text-field
                    style="text-align:right;"
                    type="number"
                    value="0"
                  ></v-text-field
                ></v-subheader>
              </v-flex>
              <v-flex md2>
                <v-subheader>บาท/เดือน</v-subheader>
              </v-flex>
            </v-layout>
          </v-container>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-layout>
                  <v-flex md2> </v-flex>
                  <v-flex md1> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md2>
                    <v-subheader>รายได้รวม</v-subheader>
                  </v-flex>
                  <v-flex md5> </v-flex>
                </v-layout>
              </v-flex>
              <v-flex md3>
                <v-subheader
                  ><v-text-field
                    style="text-align:right;"
                    type="number"
                    value="0"
                  ></v-text-field
                ></v-subheader>
              </v-flex>
              <v-flex md2>
                <v-subheader>บาท/เดือน</v-subheader>
              </v-flex>
            </v-layout>
          </v-container>
        </v-card-text>
      </v-card>
    </v-layout>
  </v-container>
</template>

<script>

export default {
  name: "Regular",

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
