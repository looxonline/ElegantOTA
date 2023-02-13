<template>
  <!-- eslint-disable max-len -->
  <main class="container">
    <div class="columns mt-3">
      <div class="col-12 mt-3 text-center">
        <img width="280px" alt="BTT OTA" src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPHN2ZyB2aWV3Qm94PSIwIDAgNTAwIDUwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8cGF0aCBkPSJNIDEzOC43MjcgNDA0Ljg5NSBMIDEzOC43MzMgNDA0LjkgTCAxMzguNzQgNDA0Ljg5NSBMIDEzOC43NTQgNDA0LjkyIEwgMjA2LjU0NiA0NjUuNDM4IEwgMjM0LjAwNCA0MzguMzU4IEwgMjMzLjk5NSA0MzguMzUgTCAyMzQuMzUzIDQzOC4wMTQgTCAyMzQuODA4IDQzNy41NjUgTCAyMzQuODIgNDM3LjU3NSBMIDI0OS44NDEgNDIzLjQ2NiBMIDI2NC42OTIgNDM3LjQxNSBMIDI2NC43MSA0MzcuMzk5IEwgMjY1LjUxNSA0MzguMTg5IEwgMjY1LjY4NyA0MzguMzUgTCAyNjUuNjgzIDQzOC4zNTMgTCAyOTIuOTYyIDQ2NS4xMDUgTCAzNjAuMzI0IDQwMi4wNDQgTCAzNjAuNTgyIDQwMi4zMjMgTCAzNjAuNzc5IDQwMS45ODkgTCA0MjAuNDMxIDQ0NC45NTggTCAzNjcuMDE3IDQyNi4wODYgTCAzMDguNzc5IDQ4MC42MTYgTCAzMDguODM0IDQ4MC42NyBMIDMwNS44MzcgNDgzLjM3MSBMIDMwNC44NDEgNDg0LjMwNCBMIDMwNC44MjMgNDg0LjI4NSBMIDI5Mi4zNjkgNDk1LjUxMSBMIDI0OS44MzUgNDUzLjgzOCBMIDIwNy4zIDQ5NS43ODYgTCAxOTAuNzk1IDQ4MC45NzEgTCAxOTAuODAyIDQ4MC45NjQgTCAxMzIuNTYyIDQyOC45NyBMIDc5LjEgNDQ3Ljg0NyBMIDEzOC42OTIgNDA0LjkyOSBaIE0gODYuNjQ0IDMzLjg5NSBDIDg2LjY0NCAxOC40NjIgOTkuOTk5IDUuODggMTE2LjQzOCA1Ljg4IEMgMTMyLjg3NiA1Ljg4IDE0Ni4yMTYgMTguNDM1IDE0Ni4yMTYgMzMuODk1IEMgMTQ2LjIxNiA0NC4zMDggMTQwLjE0IDUzLjM5NyAxMzEuMTY4IDU4LjIyMiBMIDEzMS4xNjggNzcuNTY0IEwgMTQ2Ljc5MyA2My42MDUgTCAxNjIuNTE2IDc5LjE2MiBMIDEzMS4xNjggMTA3LjE1IEwgMTMxLjE2OCAxNDEuNDM0IEwgMTg0LjY1NSA5NC4zNiBMIDE5OS45NDkgMTA5Ljc2NiBMIDEzMS4xNjggMTcwLjI5OCBMIDEzMS4xNjggMjE0LjM0NyBMIDE2OC44NDQgMjQ3LjQ4NiBMIDE5NS4xNzIgMjIzLjk3OSBMIDIxMC44OTMgMjM5LjU1MSBMIDE4NC45NDUgMjYyLjcwNyBMIDE4NC41MjkgMjYzLjEyNCBMIDE4NC41MjkgMzg0LjAwNSBMIDIwOC4wMDggNDA0Ljk4OCBMIDIzNi4xMyAzNzcuMjYyIEwgMjM2LjEzIDIxOS4wODQgTCAxNzYuNTU5IDE1OS43OTggTCAxOTIuODMxIDE0NS4zMjcgTCAyMzYuMTMgMTg4LjQxOSBMIDIzNi4xMyA5NS4xMjEgQyAyMjYuODQ2IDkwLjM3MiAyMjAuNTMyIDgxLjExNCAyMjAuNTMyIDcwLjUwNCBDIDIyMC41MzIgNTUuMDcgMjMzLjg4NiA0Mi40ODYgMjUwLjMxMSA0Mi40ODYgQyAyNjYuNzM0IDQyLjQ4NiAyODAuMTMgNTUuMDU3IDI4MC4xMyA3MC41MDQgQyAyODAuMTMgODEuMTMxIDI3My43OTUgOTAuMzkgMjY0LjQ5IDk1LjEzMyBMIDI2NC40OSAxMzAuMjg4IEwgMjgwLjE5OCAxMTYuMjYzIEwgMjk1Ljg5MiAxMzEuODIxIEwgMjY0LjQ5IDE1OS44NiBMIDI2NC40OSAxODUuNjc2IEwgMzA2Ljg2NiAxNDguMzk3IEwgMzIyLjE4OCAxNjMuNzc2IEwgMjY0LjQ5IDIxNC41NDUgTCAyNjQuNDkgMzc3Ljc0MiBMIDI5MS45NjIgNDA0Ljc4OCBMIDMxNC44MDkgMzg0LjQgTCAzMTQuODA5IDI2Mi40OTcgTCAyODkuMTA3IDIzOS41NTEgTCAzMDQuODI4IDIyMy45NzkgTCAzMzEuMTYxIDI0Ny40OSBMIDM2OC44MTggMjE0LjM2MSBMIDM2OC44MTggMTcwLjI4NyBMIDMwMC4wMzcgMTA5Ljc2NiBMIDMxNS4zNTkgOTQuMzYgTCAzNjguODE4IDE0MS40MjYgTCAzNjguODE4IDEwNy4xNDkgTCAzMzcuNDk4IDc5LjE2MiBMIDM1My4xOTIgNjMuNjA1IEwgMzY4LjgxOCA3Ny41NjQgTCAzNjguODE4IDU2Ljk2NCBDIDM1OS4zOTMgNTIuMjU4IDM1Mi45NTggNDIuOTMyIDM1Mi45NTggMzIuMjE2IEMgMzUyLjk1OCAxNi43NyAzNjYuMzI3IDQuMjE0IDM4Mi43NSA0LjIxNCBDIDM5OS4xNzUgNC4yMTQgNDEyLjU0NCAxNi43NyA0MTIuNTQ0IDMyLjIxNiBDIDQxMi41NDQgNDIuNzM4IDQwNi4zNCA1MS45MiAzOTcuMTkyIDU2LjcwNCBMIDM5Ny4xOTIgNzcuOTIgTCA0MTMuMjE3IDYzLjYwNSBMIDQyOC45MjYgNzkuMTYyIEwgMzk3LjE5MiAxMDcuNTE3IEwgMzk3LjE5MiAxNDAuMTIxIEwgNDQ5LjE3NiA5NC4zNiBMIDQ2NC41IDEwOS43NjYgTCAzOTcuMTkyIDE2OC45ODIgTCAzOTcuMTkyIDIyNi4wMTggTCAzOTcuMDY4IDIyNi4wMTggTCAzNDIuODY2IDI3My43MDEgTCAzNDIuODY2IDM4OS4wMzQgTCAzNDIuNzQzIDM4OS4wMzQgTCAzMDcuNzE4IDQyMC4zIEwgMzA3LjcxOSA0MjAuMzAxIEwgMjkxLjIxMiA0MzUuMDk5IEwgMjUwLjA3NSAzOTQuNiBMIDIwOC43NzMgNDM1LjMxOSBMIDE5Ni4yMjIgNDI0LjA1NyBMIDE5Ni4yMTkgNDI0LjA2IEwgMTU3LjExOSAzODkuMTMxIEwgMTU3LjIxNyAzODkuMDM0IEwgMTU3LjExOSAzODkuMDM0IEwgMTU3LjExOSAyNzMuNjk4IEwgMTAyLjkzMiAyMjYuMDE4IEwgMTAyLjgyMSAyMjYuMDE4IEwgMTAyLjgyMSAxNjkuMDA0IEwgMzUuNSAxMDkuNzY2IEwgNTAuODA5IDk0LjM2IEwgMTAyLjgyMSAxNDAuMTQ1IEwgMTAyLjgyMSAxMDcuNTQxIEwgNzEuMDYxIDc5LjE2MiBMIDg2Ljc2OSA2My42MDUgTCAxMDIuODIxIDc3Ljk0NCBMIDEwMi44MjEgNTguOCBDIDkzLjIxOSA1NC4xNDQgODYuNjQ0IDQ0LjcyNSA4Ni42NDQgMzMuODk1IFogTSAxMTYuNDM4IDI1LjMwNiBDIDEwOS44MjYgMjUuNzE4IDEwNi4xNDMgMzMuMTMzIDEwOS44MDYgMzguNjUyIEMgMTEzLjQ3IDQ0LjE3MSAxMjEuNzMzIDQzLjY1NCAxMjQuNjgxIDM3LjcyMiBDIDEyNS4yNyAzNi41MzIgMTI1LjU3OSAzNS4yMjIgMTI1LjU3OSAzMy44OTUgQyAxMjUuNDIyIDI5LjAwMyAxMjEuMzMzIDI1LjE1OCAxMTYuNDM4IDI1LjMwNiBaIE0gMjUwLjMxMSA2MS44OTggQyAyNDMuNjg5IDYyLjMyMyAyNDAuMDExIDY5Ljc1NSAyNDMuNjg3IDc1LjI3NyBDIDI0Ny4zNjUgODAuNzk5IDI1NS42NDEgODAuMjY3IDI1OC41ODQgNzQuMzIxIEMgMjU5LjE3MyA3My4xMzUgMjU5LjQ4IDcxLjgyOSAyNTkuNDggNzAuNTA0IEMgMjU5LjMyMiA2NS41OTUgMjU1LjIxOCA2MS43NDUgMjUwLjMxMSA2MS44OTggWiBNIDM4Mi43NSAyMy42MTEgQyAzNzYuMTI5IDI0LjAyNSAzNzIuNDM4IDMxLjQ1IDM3Ni4xMDggMzYuOTggQyAzNzkuNzc1IDQyLjUwOCAzODguMDUyIDQxLjk5IDM5MS4wMDUgMzYuMDQ5IEMgMzkxLjU5NyAzNC44NTkgMzkxLjkwNiAzMy41NDYgMzkxLjkwNiAzMi4yMTYgQyAzOTEuNzQ4IDI3LjMxNiAzODcuNjUzIDIzLjQ2NSAzODIuNzUgMjMuNjExIFoiIGNsYXNzPSJjbHMtMSIgc3R5bGU9ImZpbGw6IHJnYigxOTIsIDQ3LCA0OCk7Ii8+Cjwvc3ZnPg==">
      </div>
      <div class="col-12 p-centered"></div>
      <div class="col-12 mt-3 p-centered" v-if="loading">
        <div class="col-3 col-sm-10 p-centered">
          <div class="loading loading-lg mt-3"></div>
        </div>
      </div>
      <transition name="fade" mode="out-in">
        <div class="col-12 mt-3 pt-2 p-centered" v-if="!loading && !uploading && OTAError !== null" key="error">
          <div class="col-3 col-sm-9 col-md-6 p-centered text-center">
            <svg width="32px" height="32px" style="vertical-align: middle;" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
              <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                <rect id="bound" x="0" y="0" width="24" height="24"></rect>
                <circle id="Oval-5" fill="#DF4759" opacity="0.3" cx="12" cy="12" r="10"></circle>
                <rect id="Rectangle-9" fill="#DF4759" x="11" y="7" width="2" height="8" rx="1"></rect>
                <rect id="Rectangle-9-Copy" fill="#DF4759" x="11" y="16" width="2" height="2" rx="1"></rect>
              </g>
            </svg>
            <span style="vertical-align: middle;" class="ml-2"> {{ OTAError }} </span>
            <br>
            <br>
            <div class="mt-3">
              <button class="btn btn-light mr-2" @click="clear">
                <svg xmlns="http://www.w3.org/2000/svg" class="pt-1" width="16px" height="16px" viewBox="0 0 24 24">
                  <g data-name="Layer 2">
                    <g data-name="arrow-back">
                      <rect width="24" height="24" transform="rotate(90 12 12)" opacity="0" />
                      <path
                        fill="currentColor"
                        d="M19 11H7.14l3.63-4.36a1 1 0 1 0-1.54-1.28l-5 6a1.19 1.19 0 0 0-.09.15c0 .05 0 .08-.07.13A1 1 0 0 0 4 12a1 1 0 0 0 .07.36c0 .05 0 .08.07.13a1.19 1.19 0 0 0 .09.15l5 6A1 1 0 0 0 10 19a1 1 0 0 0 .64-.23 1 1 0 0 0 .13-1.41L7.14 13H19a1 1 0 0 0 0-2z" />
                    </g>
                  </g>
                </svg>
                Back
              </button>
              <button class="btn btn-primary ml-2" @click="retryOTA">
                <svg xmlns="http://www.w3.org/2000/svg" class="pt-1" width="16px" height="16px" viewBox="0 0 24 24">
                  <g data-name="Layer 2">
                    <g data-name="refresh">
                      <rect width="24" height="24" opacity="0" />
                      <path
                        fill="currentColor"
                        d="M20.3 13.43a1 1 0 0 0-1.25.65A7.14 7.14 0 0 1 12.18 19 7.1 7.1 0 0 1 5 12a7.1 7.1 0 0 1 7.18-7 7.26 7.26 0 0 1 4.65 1.67l-2.17-.36a1 1 0 0 0-1.15.83 1 1 0 0 0 .83 1.15l4.24.7h.17a1 1 0 0 0 .34-.06.33.33 0 0 0 .1-.06.78.78 0 0 0 .2-.11l.09-.11c0-.05.09-.09.13-.15s0-.1.05-.14a1.34 1.34 0 0 0 .07-.18l.75-4a1 1 0 0 0-2-.38l-.27 1.45A9.21 9.21 0 0 0 12.18 3 9.1 9.1 0 0 0 3 12a9.1 9.1 0 0 0 9.18 9A9.12 9.12 0 0 0 21 14.68a1 1 0 0 0-.7-1.25z" />
                    </g>
                  </g>
                </svg>
                Retry
              </button>
            </div>
          </div>
        </div>
        <div class="col-12 mt-3 pt-2 p-centered" v-else-if="!loading && !uploading && OTASuccess" key="success">
          <div class="col-3 col-sm-9 col-md-6 p-centered text-center">
            <svg width="32px" height="32px" style="vertical-align: middle;" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
              <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                <rect id="bound" x="0" y="0" width="24" height="24"></rect>
                <circle id="Oval-5" fill="#42BA96" opacity="0.3" cx="12" cy="12" r="10"></circle>
                <path d="M16.7689447,7.81768175 C17.1457787,7.41393107 17.7785676,7.39211077 18.1823183,7.76894473 C18.5860689,8.1457787 18.6078892,8.77856757 18.2310553,9.18231825 L11.2310553,16.6823183 C10.8654446,17.0740439 10.2560456,17.107974 9.84920863,16.7592566 L6.34920863,13.7592566 C5.92988278,13.3998345 5.88132125,12.7685345 6.2407434,12.3492086 C6.60016555,11.9298828 7.23146553,11.8813212 7.65079137,12.2407434 L10.4229928,14.616916 L16.7689447,7.81768175 Z" id="Path-92" fill="#42BA96"></path>
              </g>
            </svg>
            <span style="vertical-align: middle;" class="ml-2 mb-2"> OTA Success </span>
            <br>
            <br>
            <button class="btn btn-primary mt-3" @click="clear">
              <svg xmlns="http://www.w3.org/2000/svg" class="pt-1" width="16px" height="16px" viewBox="0 0 24 24">
                <g data-name="Layer 2">
                  <g data-name="arrow-back">
                    <rect width="24" height="24" transform="rotate(90 12 12)" opacity="0" />
                    <path
                      fill="currentColor"
                      d="M19 11H7.14l3.63-4.36a1 1 0 1 0-1.54-1.28l-5 6a1.19 1.19 0 0 0-.09.15c0 .05 0 .08-.07.13A1 1 0 0 0 4 12a1 1 0 0 0 .07.36c0 .05 0 .08.07.13a1.19 1.19 0 0 0 .09.15l5 6A1 1 0 0 0 10 19a1 1 0 0 0 .64-.23 1 1 0 0 0 .13-1.41L7.14 13H19a1 1 0 0 0 0-2z" />
                  </g>
                </g>
              </svg>
              Back
            </button>
          </div>
        </div>
        <div class="col-12 mt-3 p-centered" v-else-if="!loading && !uploading" key="otainput">
          <div class="col-3 col-sm-9 col-md-6 p-centered">
            <div class="form-group pt-2 mt-2">
              <label class="form-radio form-inline mr-2">
                <input type="radio" name="firmwaretype" for="firmwaretype" value="firmware" v-model="type"><i class="form-icon"></i> Firmware
              </label>
            </div>
            <div class="form-group pt-2 mt-3">
              <input class="form-input file-input" type="file" ref="file" accept=".bin,.bin.gz" @change="uploadOTA">
            </div>
          </div>
        </div>
      </transition>
      <transition name="fade" mode="out-in">
        <div class="col-12 mt-3 mb-2 pt-2 p-centered" v-if="!loading && uploading">
          <div class="col-2 mt-3 mb-2 col-sm-7 col-md-4 text-right p-centered">
            <div class="bar mt-3 bar-sm">
              <div class="bar-item tooltip" :data-tooltip="progress+'%'" :style="{ width: progress+'%' }"></div>
            </div>
            <div class="pt-2">{{progress}}%</div>
          </div>
        </div>
      </transition>
      <div class="col-12 mt-3 p-centered"></div>
    </div>
    <transition name="fade" mode="out-in">
      <div class="columns mt-3" v-if="!loading">
        <div class="col-12 text-center">
          <span class="label label-rounded mr-2">{{ deviceData.id }}</span> - <span class="label label-rounded label-primary ml-2">{{ deviceData.hardware }}</span>
        </div>
      </div>
    </transition>
  </main>
</template>

<script>
export default {
  name: 'App',

  data() {
    return {
      loading: true,
      uploading: false,
      progress: 0,
      OTAError: null,
      OTASuccess: false,

      type: 'firmware',
      file: null,
      deviceData: {
        id: null,
        hardware: null,
      },
    };
  },

  methods: {
    fileMD5(file) {
      return new Promise((resolve, reject) => {
        const blobSlice = File.prototype.slice
          || File.prototype.mozSlice || File.prototype.webkitSlice;
        const chunkSize = 2097152; // Read in chunks of 2MB
        const chunks = Math.ceil(file.size / chunkSize);
        const spark = new this.SparkMD5.ArrayBuffer();
        const fileReader = new FileReader();
        let currentChunk = 0;
        let loadNext;

        fileReader.onload = (e) => {
          spark.append(e.target.result); // Append array buffer
          currentChunk += 1;

          if (currentChunk < chunks) {
            loadNext();
          } else {
            const md5 = spark.end();
            resolve(md5);
          }
        };

        fileReader.onerror = (e) => {
          reject(e);
        };

        loadNext = () => {
          const start = currentChunk * chunkSize;
          const end = ((start + chunkSize) >= file.size) ? file.size : start + chunkSize;

          fileReader.readAsArrayBuffer(blobSlice.call(file, start, end));
        };

        loadNext();
      });
    },
    uploadOTA(event) {
      this.uploading = true;
      const formData = new FormData();
      if (event !== null) {
        [this.file] = event.target.files;
      }
      const request = new XMLHttpRequest();

      request.addEventListener('load', () => {
        // request.response will hold the response from the server
        if (request.status === 200) {
          this.OTASuccess = true;
        } else if (request.status !== 500) {
          this.OTAError = `[HTTP ERROR] ${request.statusText}`;
        } else {
          this.OTAError = request.responseText;
        }
        this.uploading = false;
        this.progress = 0;
      });

      // Upload progress
      request.upload.addEventListener('progress', (e) => {
        this.progress = Math.trunc((e.loaded / e.total) * 100);
      });

      request.withCredentials = true;

      this.fileMD5(this.file)
        .then((md5) => {
          formData.append('MD5', md5);
          formData.append(this.type, this.file, this.type);
          request.open('post', '/update');
          request.send(formData);
        })
        .catch(() => {
          this.OTAError = 'Unknown error while upload, check the console for details.';
          this.uploading = false;
          this.progress = 0;
        });
    },

    retryOTA() {
      this.OTAError = null;
      this.OTASuccess = false;
      this.uploadOTA(null);
    },

    clear() {
      this.OTAError = null;
      this.OTASuccess = false;
    },
  },

  mounted() {
    if (process.env.NODE_ENV === 'production') {
      fetch('/update/identity').then(async (response) => {
        if (response.ok) {
          this.deviceData = await response.json();
          this.loading = false;
        }
      });
    }
  },

};
</script>

<style lang="scss">
$primary-color: #488EFF;
// Variables and mixins
@import "~spectre.css/src/variables";
@import "~spectre.css/src/mixins";

/*! Spectre.css v#{$version} | MIT License | github.com/picturepan2/spectre */
// Reset and dependencies
@import "~spectre.css/src/normalize";
@import "~spectre.css/src/base";

// Elements
@import "~spectre.css/src/typography";

@import "~spectre.css/src/labels";
@import "~spectre.css/src/buttons";
@import "~spectre.css/src/tooltips";
@import "~spectre.css/src/cards";
@import "~spectre.css/src/bars";
@import "~spectre.css/src/forms";

@import "~spectre.css/src/layout";

@import "~spectre.css/src/animations";
@import "~spectre.css/src/utilities";

.logo{
  width: 100%;
  max-width: 320px;
}

.card{
  border: 0;
  box-shadow: 0 0.25rem 1rem rgba(48,55,66,.1);
  border-radius: 0.275rem;
}

.label{
  font-size: 0.65rem !important;
}

.file-input{
  border-radius: 0.275rem;
}

.pt-3{
  padding-top: 32px;
}

.mt-3{
  margin-top: 24px;
}

.fade-enter-active, .fade-leave-active {
  transition: opacity .25s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>
