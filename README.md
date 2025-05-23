<html>
  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Inter%3Awght%40400%3B500%3B700%3B900&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900"
    />

    <title>Galileo Design</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div
      class="relative flex size-full min-h-screen flex-col bg-[#221111] dark justify-between group/design-root overflow-x-hidden"
      style='font-family: Inter, "Noto Sans", sans-serif;'
    >
      <div>
        <div class="flex items-center bg-[#221111] p-4 pb-2 justify-between">
          <h2 class="text-white text-lg font-bold leading-tight tracking-[-0.015em] flex-1 text-center pl-12">Relaxing Music</h2>
          <div class="flex w-12 items-center justify-end">
            <button
              class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-12 bg-transparent text-white gap-2 text-base font-bold leading-normal tracking-[0.015em] min-w-0 p-0"
            >
              <div class="text-white" data-icon="ArrowsHorizontal" data-size="24px" data-weight="regular">
                <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M237.66,133.66l-32,32a8,8,0,0,1-11.32-11.32L212.69,136H43.31l18.35,18.34a8,8,0,0,1-11.32,11.32l-32-32a8,8,0,0,1,0-11.32l32-32a8,8,0,0,1,11.32,11.32L43.31,120H212.69l-18.35-18.34a8,8,0,0,1,11.32-11.32l32,32A8,8,0,0,1,237.66,133.66Z"
                  ></path>
                </svg>
              </div>
            </button>
          </div>
        </div>
        <div class="flex flex-col items-stretch gap-6 bg-[#221111] px-4 pb-4 pt-3 text-white">
          <div class="flex items-center justify-center py-7">
            <div
              class="bg-center bg-no-repeat aspect-square bg-cover rounded-xl size-64"
              style='background-image: url("https://cdn.usegalileo.ai/sdxl10/7cc73860-362f-4f2a-9273-10d973d33cb5.png");'
            ></div>
          </div>
          <div class="text-center">
            <p class="text-white text-[22px] font-bold leading-tight tracking-[-0.015em] truncate"></p>
            <p class="text-[#c99292] text-base font-normal leading-normal truncate"></p>
          </div>
          <div class="flex items-center justify-center gap-6 pt-1">
            <button class="flex shrink-0 items-center justify-center rounded-full size-10 text-[#ec1313]">
              <div class="text-inherit" data-icon="SkipBack" data-size="32px" data-weight="fill">
                <svg xmlns="http://www.w3.org/2000/svg" width="32px" height="32px" fill="currentColor" viewBox="0 0 256 256">
                  <path d="M208,47.88V208.12a16,16,0,0,1-24.43,13.43L64,146.77V216a8,8,0,0,1-16,0V40a8,8,0,0,1,16,0v69.23L183.57,34.45A15.95,15.95,0,0,1,208,47.88Z"></path>
                </svg>
              </div>
            </button>
            <button class="flex shrink-0 items-center justify-center rounded-full size-10 text-[#ec1313]">
              <div class="text-inherit" data-icon="Rewind" data-size="32px" data-weight="fill">
                <svg xmlns="http://www.w3.org/2000/svg" width="32px" height="32px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M232,71.84V184.16a15.92,15.92,0,0,1-24.48,13.34L128,146.86v37.3a15.92,15.92,0,0,1-24.48,13.34L15.33,141.34a15.8,15.8,0,0,1,0-26.68L103.52,58.5A15.91,15.91,0,0,1,128,71.84v37.3L207.52,58.5A15.91,15.91,0,0,1,232,71.84Z"
                  ></path>
                </svg>
              </div>
            </button>
            <button class="flex shrink-0 items-center justify-center rounded-full size-16 bg-[#ec1313] text-white">
              <div class="text-inherit" data-icon="Play" data-size="32px" data-weight="fill">
                <svg xmlns="http://www.w3.org/2000/svg" width="32px" height="32px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M240,128a15.74,15.74,0,0,1-7.6,13.51L88.32,229.65a16,16,0,0,1-16.2.3A15.86,15.86,0,0,1,64,216.13V39.87a15.86,15.86,0,0,1,8.12-13.82,16,16,0,0,1,16.2.3L232.4,114.49A15.74,15.74,0,0,1,240,128Z"
                  ></path>
                </svg>
              </div>
            </button>
            <button class="flex shrink-0 items-center justify-center rounded-full size-10 text-[#ec1313]">
              <div class="text-inherit" data-icon="FastForward" data-size="32px" data-weight="fill">
                <svg xmlns="http://www.w3.org/2000/svg" width="32px" height="32px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M248,128a15.76,15.76,0,0,1-7.33,13.34L152.48,197.5A15.91,15.91,0,0,1,128,184.16v-37.3L48.48,197.5A15.91,15.91,0,0,1,24,184.16V71.84A15.91,15.91,0,0,1,48.48,58.5L128,109.14V71.84A15.91,15.91,0,0,1,152.48,58.5l88.19,56.16A15.76,15.76,0,0,1,248,128Z"
                  ></path>
                </svg>
              </div>
            </button>
            <button class="flex shrink-0 items-center justify-center rounded-full size-10 text-[#ec1313]">
              <div class="text-inherit" data-icon="SkipForward" data-size="32px" data-weight="fill">
                <svg xmlns="http://www.w3.org/2000/svg" width="32px" height="32px" fill="currentColor" viewBox="0 0 256 256">
                  <path d="M208,40V216a8,8,0,0,1-16,0V146.77L72.43,221.55A15.95,15.95,0,0,1,48,208.12V47.88A15.95,15.95,0,0,1,72.43,34.45L192,109.23V40a8,8,0,0,1,16,0Z"></path>
                </svg>
              </div>
            </button>
          </div>
        </div>
        <h3 class="text-white text-lg font-bold leading-tight tracking-[-0.015em] px-4 pb-2 pt-4">Up Next</h3>
        <div class="p-4 @container">
          <div class="flex flex-col items-stretch justify-start rounded-xl @xl:flex-row @xl:items-start">
            <div
              class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl"
              style='background-image: url("https://cdn.usegalileo.ai/sdxl10/80795507-4473-46eb-9e89-abba4333b8d0.png");'
            ></div>
            <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
              <p class="text-white text-lg font-bold leading-tight tracking-[-0.015em]">The best of classical music</p>
              <div class="flex items-end gap-3 justify-between">
                <div class="flex flex-col gap-1">
                  <p class="text-[#c99292] text-base font-normal leading-normal">Music</p>
                  <p class="text-[#c99292] text-base font-normal leading-normal">1.5M views - 2 months ago</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="p-4 @container">
          <div class="flex flex-col items-stretch justify-start rounded-xl @xl:flex-row @xl:items-start">
            <div
              class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl"
              style='background-image: url("https://cdn.usegalileo.ai/sdxl10/bb8e29cf-6284-405a-b0cf-1312c0765ce2.png");'
            ></div>
            <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
              <p class="text-white text-lg font-bold leading-tight tracking-[-0.015em]">Relaxing piano music</p>
              <div class="flex items-end gap-3 justify-between">
                <div class="flex flex-col gap-1">
                  <p class="text-[#c99292] text-base font-normal leading-normal">Music</p>
                  <p class="text-[#c99292] text-base font-normal leading-normal">4.7M views - 3 weeks ago</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="p-4 @container">
          <div class="flex flex-col items-stretch justify-start rounded-xl @xl:flex-row @xl:items-start">
            <div
              class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl"
              style='background-image: url("https://cdn.usegalileo.ai/sdxl10/5fb2fa97-2296-4089-a3df-3f5a389e0598.png");'
            ></div>
            <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
              <p class="text-white text-lg font-bold leading-tight tracking-[-0.015em]">Peaceful guitar music</p>
              <div class="flex items-end gap-3 justify-between">
                <div class="flex flex-col gap-1">
                  <p class="text-[#c99292] text-base font-normal leading-normal">Music</p>
                  <p class="text-[#c99292] text-base font-normal leading-normal">1.2M views - 1 month ago</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="flex gap-2 border-t border-[#482323] bg-[#331919] px-4 pb-3 pt-2">
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 rounded-full text-white" href="#">
            <div class="text-white flex h-8 items-center justify-center" data-icon="House" data-size="24px" data-weight="fill">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M224,115.55V208a16,16,0,0,1-16,16H168a16,16,0,0,1-16-16V168a8,8,0,0,0-8-8H112a8,8,0,0,0-8,8v40a16,16,0,0,1-16,16H48a16,16,0,0,1-16-16V115.55a16,16,0,0,1,5.17-11.78l80-75.48.11-.11a16,16,0,0,1,21.53,0,1.14,1.14,0,0,0,.11.11l80,75.48A16,16,0,0,1,224,115.55Z"
                ></path>
              </svg>
            </div>
          </a>
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 text-[#c99292]" href="#">
            <div class="text-[#c99292] flex h-8 items-center justify-center" data-icon="Compass" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M128,24A104,104,0,1,0,232,128,104.11,104.11,0,0,0,128,24Zm0,192a88,88,0,1,1,88-88A88.1,88.1,0,0,1,128,216ZM172.42,72.84l-64,32a8.05,8.05,0,0,0-3.58,3.58l-32,64A8,8,0,0,0,80,184a8.1,8.1,0,0,0,3.58-.84l64-32a8.05,8.05,0,0,0,3.58-3.58l32-64a8,8,0,0,0-10.74-10.74ZM138,138,97.89,158.11,118,118l40.15-20.07Z"
                ></path>
              </svg>
            </div>
          </a>
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 text-[#c99292]" href="#">
            <div class="text-[#c99292] flex h-8 items-center justify-center" data-icon="CameraPlus" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M208,56H180.28L166.65,35.56A8,8,0,0,0,160,32H96a8,8,0,0,0-6.65,3.56L75.71,56H48A24,24,0,0,0,24,80V192a24,24,0,0,0,24,24H208a24,24,0,0,0,24-24V80A24,24,0,0,0,208,56Zm8,136a8,8,0,0,1-8,8H48a8,8,0,0,1-8-8V80a8,8,0,0,1,8-8H80a8,8,0,0,0,6.66-3.56L100.28,48h55.43l13.63,20.44A8,8,0,0,0,176,72h32a8,8,0,0,1,8,8Zm-48-56a8,8,0,0,1-8,8H136v24a8,8,0,0,1-16,0V144H96a8,8,0,0,1,0-16h24V104a8,8,0,0,1,16,0v24h24A8,8,0,0,1,168,136Z"
                ></path>
              </svg>
            </div>
          </a>
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 text-[#c99292]" href="#">
            <div class="text-[#c99292] flex h-8 items-center justify-center" data-icon="Bookmark" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M184,32H72A16,16,0,0,0,56,48V224a8,8,0,0,0,12.24,6.78L128,193.43l59.77,37.35A8,8,0,0,0,200,224V48A16,16,0,0,0,184,32Zm0,16V161.57l-51.77-32.35a8,8,0,0,0-8.48,0L72,161.56V48ZM132.23,177.22a8,8,0,0,0-8.48,0L72,209.57V180.43l56-35,56,35v29.14Z"
                ></path>
              </svg>
            </div>
          </a>
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 text-[#c99292]" href="#">
            <div class="text-[#c99292] flex h-8 items-center justify-center" data-icon="UserCircle" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M128,24A104,104,0,1,0,232,128,104.11,104.11,0,0,0,128,24ZM74.08,197.5a64,64,0,0,1,107.84,0,87.83,87.83,0,0,1-107.84,0ZM96,120a32,32,0,1,1,32,32A32,32,0,0,1,96,120Zm97.76,66.41a79.66,79.66,0,0,0-36.06-28.75,48,48,0,1,0-59.4,0,79.66,79.66,0,0,0-36.06,28.75,88,88,0,1,1,131.52,0Z"
                ></path>
              </svg>
            </div>
          </a>
        </div>
        <div class="h-5 bg-[#331919]"></div>
      </div>
    </div>
  </body>
</html>
