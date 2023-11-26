<template>
  <div>
    <div class="d-flex justify-end text-center mx-2 pt-2">
      <div style="font-size: 14px" class="mr-3 my-3">Gmail</div>
      <div style="font-size: 14px" class="mr-2 my-3">Images</div>
      <v-btn icon="mdi-apps" class="mr-2" variant="text"></v-btn>
      <v-btn
        elevation="0"
        style="
          background-color: #8ab4f8;
          color: black;
          font-size: 10.15pt;
          font-weight: 300;
          text-transform: capitalize;
        "
        class="px-5 my-1 mx-2"
        >sign in</v-btn
      >
    </div>
    <v-container id="center_div">
      <div class="d-flex justify-center">
        <img
          src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_light_color_272x92dp.png"
        />
      </div>
      <div class="d-flex justify-center pt-7">
        <v-text-field
          prepend-inner-icon="mdi-magnify"
          variant="outlined"
          style="max-width: 590px"
          append-inner-icon="mdi-google-lens"
          rounded
        ></v-text-field>
      </div>
      <div class="d-flex justify-center pt-2" id="search_btn">
        <v-btn variant="tonal" class="mx-3"> Google Search </v-btn>
        <v-btn variant="tonal"> I'm Feeling Lucky </v-btn>
      </div>
      <div class="d-flex justify-center pt-7" style="font-size: small">
        <p style="color: #cfcece">Google offered in: &nbsp;</p>
        <div class="d-flex flex-row" id="language">
          <p>हिन्दी</p>
          <p>বাংলা</p>
          <p>తెలుగు</p>
          <p>मराठी</p>
          <p>தமிழ்</p>
          <p>ગુજરાતી</p>
          <p>ಕನ್ನಡ</p>
          <p>മലയാളം</p>
          <p>ਪੰਜਾਬੀ</p>
        </div>
      </div>
    </v-container>

    <div class="footer">
      <div class="d-flex justify-space-between px-2">
        <div>
          <span class="pr-7">About</span>
          <span class="pr-7">Advertising</span>
          <span class="pr-7">Business</span>
          <span>How Search works</span>
        </div>
        <div>
          <span class="pr-7">Privacy</span>
          <span class="pr-7">Terms</span>
          <span>Settings</span>
        </div>
      </div>
    </div>

    <div class="second-footer">
      <div class="px-2">
        <span>India</span>
      </div>
    </div>
  </div>
</template>
<style>
@import url("../assets/main.css");
</style>
