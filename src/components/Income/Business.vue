<template>
  <v-container>
    <v-layout row>
      <v-checkbox :label="`รายได้จากวิชาชีพเฉพาะ/อาชีพอิสระ`"></v-checkbox>
    </v-layout>
    <v-layout row>
      <v-card class="mx-auto" width="100%" outlined>
        <v-card-text>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-layout>
                  <v-flex md4>
                    <v-subheader>ลักษณะธุรกิจ</v-subheader>
                  </v-flex>
                  <v-flex md8>
                    <v-subheader>
                      <v-select></v-select
                    ></v-subheader>
                  </v-flex>
                  <v-flex md2> </v-flex>
                </v-layout>
              </v-flex>
              <v-flex md3> </v-flex>
              <v-flex md2> </v-flex>
            </v-layout>
          </v-container>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-layout>
                  <v-flex md4>
                    <v-subheader>สัดส่วนการถือหุ้น</v-subheader>
                  </v-flex>
                  <v-flex md1> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md3>
                    <v-subheader
                      ><v-text-field
                        type="number"
                        value="0"
                        style="text-align:right;"
                      ></v-text-field
                    ></v-subheader>
                  </v-flex>
                  <v-flex md2>
                    <v-subheader>%</v-subheader>
                  </v-flex>
                </v-layout>
              </v-flex>
              <v-flex md3> </v-flex>
              <v-flex md2> </v-flex>
            </v-layout>
          </v-container>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-layout>
                  <v-flex md4>
                    <v-subheader>รายได้</v-subheader>
                  </v-flex>
                  <v-flex md1> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md3>
                    <v-subheader
                      ><v-text-field
                        type="number"
                        value="0"
                        style="text-align:right;"
                      ></v-text-field
                    ></v-subheader>
                  </v-flex>
                  <v-flex md2>
                    <v-subheader>บาท/เดือน</v-subheader>
                  </v-flex>
                </v-layout>
              </v-flex>
              <v-flex md3> </v-flex>
              <v-flex md2> </v-flex>
            </v-layout>
          </v-container>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-layout>
                  <v-flex md4>
                    <v-subheader>อัตรากำไรของธุรกิจ</v-subheader>
                  </v-flex>
                  <v-flex md1> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md3>
                    <v-subheader
                      ><v-text-field
                        type="number"
                        value="0"
                        style="text-align:right;"
                      ></v-text-field
                    ></v-subheader>
                  </v-flex>
                  <v-flex md2>
                    <v-subheader>%</v-subheader>
                  </v-flex>
                </v-layout>
              </v-flex>
              <v-flex md3> </v-flex>
              <v-flex md2> </v-flex>
            </v-layout>
          </v-container>
          <v-container>
            <v-layout row>
              <v-flex md7>
                <v-layout>
                  <v-flex md4>
                    <v-subheader>รายได้สุทธิ</v-subheader>
                  </v-flex>
                  <v-flex md1> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md2> </v-flex>
                  <v-flex md3>
                    <v-subheader
                      ><v-text-field
                        type="number"
                        value="0"
                        style="text-align:right;"
                      ></v-text-field
                    ></v-subheader>
                  </v-flex>
                  <v-flex md2>
                    <v-subheader>บาท/เดือน</v-subheader>
                  </v-flex>
                </v-layout>
              </v-flex>
              <v-flex md3> </v-flex>
              <v-flex md2> </v-flex>
            </v-layout>
          </v-container>
        </v-card-text>
      </v-card>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: "Business",

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
