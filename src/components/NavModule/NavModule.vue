<template>
  <div class="header-container">
    <nav class="logo-container">
      <a href="/" class="navigation-logo">
        <svg class="logo-icon" viewBox="0 0 515.16 80.36">
          <path
            d="M96.74 17.39H125l-1.34 8.25h-17.79V36.1h16v8.26h-16V63h-9.13zM128 34.43c0-12.08 6-17.51 16.9-17.51 9.4 0 13.69 5.09 13.69 5.09v7.12h-7.45S150.62 25 145 25c-6 0-7.85 3-7.85 9.2v11.97c0 6.24 1.88 9.19 7.85 9.19 5.64 0 6.17-4.09 6.17-4.09h7.45v7.11s-4.29 5.1-13.69 5.1C134 63.48 128 58 128 46zM208 49.93c0 8.18-4.52 13.07-14.85 13.07H176V17.39h16.5c10.94 0 14.76 5 14.76 12.47A11.52 11.52 0 01202 39.93v.13s6 3.09 6 9.87zm-23.11-24.56V36h9.93a5.89 5.89 0 003.56-5.5c0-2.82-1.54-5.1-5.5-5.1zm14.16 24.09a6.2 6.2 0 00-4-5.64h-10.16v11.07h8.53c3.69 0 5.63-2.08 5.63-5.43zM249.37 57.91V63h-8.19l-2.48-9.6a40.88 40.88 0 01-8.12.81 44 44 0 01-7.92-.74L220.18 63h-8v-5.1l11.2-40.52h14.76zm-12.68-12.14L234 35.63c-1.07-4.22-2.41-10.13-2.41-10.13h-1.81s-1.35 5.91-2.49 10.13l-2.61 10.2a33.45 33.45 0 005.9.54 31.18 31.18 0 006.11-.6zM278.82 44.62s4.49 8.06 9.19 12.89V63h-7c-5.7-6.24-11.54-17.45-11.54-17.45h-4.76V63h-9.11V17.39h17.25c9.93 0 15.36 4.69 15.36 13.55 0 10.4-9.39 13.68-9.39 13.68zm-4-7.31a6 6 0 004.22-6c0-3.62-2.21-5.7-5.9-5.7h-8.45v11.7z"
          ></path>
          <path
            data-name="C"
            d="M293.3 34.43c0-12.08 6-17.51 16.91-17.51 9.4 0 13.69 5.09 13.69 5.09v7.12h-7.45s-.54-4.1-6.17-4.1c-6 0-7.85 3-7.85 9.2v11.94c0 6.24 1.88 9.19 7.85 9.19 5.63 0 6.17-4.09 6.17-4.09h7.45v7.11s-4.29 5.1-13.69 5.1C299.28 63.48 293.3 58 293.3 46z"
          ></path>
          <path
            d="M330.34 17.39h28.91l-1.34 8.25h-18.45V36.1h16.71v8.26h-16.71v10.4h19.12V63h-28.24zM366 17.39h9.12v37.37h18.45L392.19 63H366zM395.27 35c0-11.87 6.18-18.32 17.72-18.32S430.7 23.16 430.7 35v10.36c0 11.81-6.17 18.32-17.71 18.32s-17.72-6.44-17.72-18.32zM413 55.56c6 0 8.59-2.82 8.59-9.53V34.36c0-6.71-2.55-9.53-8.59-9.53s-8.59 2.82-8.59 9.53V46c-.01 6.74 2.59 9.56 8.59 9.56zM438.08 17.39h8.38l13 21.4c1.07 1.74 3.62 6.91 3.62 6.91h.14s-.34-4.9-.34-9.39V17.39h8.86V63h-8.84v-3.68L451.43 40.6l-4.5-7.85h-.2s.2 4.16.2 8.65V63h-8.85z"
          ></path>
          <path
            data-name="A"
            d="M515.16 57.91V63H507l-2.49-9.6a40.81 40.81 0 01-8.12.81 43.91 43.91 0 01-7.91-.74L486 63h-8v-5.1l11.2-40.51H504zm-12.68-12.14l-2.68-10.14c-1.08-4.22-2.42-10.13-2.42-10.13h-1.81s-1.34 5.91-2.48 10.13l-2.62 10.2a33.45 33.45 0 005.9.54 31.1 31.1 0 006.11-.6z"
          ></path>
          <path
            d="M51.89 1.25l.4.27C56.69 4.43 60.23 5 65.61 5a18.14 18.14 0 005.89-1l.5-.25 2.55 3.58-.26.36C64.8 20.3 72.2 33.91 77.44 39.35l.48.5-.49.49c-.69.69-1.88 1.93-2.76 2.85l-.3.32v1.08C74.89 53 72.71 59.91 68 65.13c-5 5.54-13 8.87-22.38 9.39h-.36l-.27.24c-2.39 2.18-4.82 4-4.84 4l-.43.31-.42-.31c-.1-.08-2.5-1.86-4.86-4l-.27-.24h-.36c-9.42-.52-17.37-3.85-22.41-9.39C6.65 59.91 4.48 53 4.92 44.59v-.08-.4H5v-.56l-.3-.32c-.83-.87-2-2.15-2.76-2.85l-.49-.49.48-.5c5.24-5.44 12.64-19 3.15-31.66l-.28-.4 2.55-3.58.52.18a18.14 18.14 0 005.89 1c5.38 0 8.92-.53 13.32-3.44l.4-.27.4.28a20 20 0 0011.81 3.97 20 20 0 0011.8-3.94l.4-.28"
            fill="#deb500"
          ></path>
          <path
            data-name="BADGE BORDER"
            d="M79.37 39.84l-1.18-1.22c-5-5.22-12.14-18.28-3.07-30.34l.71-.95-3.43-4.81-1.23.48a17.23 17.23 0 01-5.56 1c-5.18 0-8.58-.5-12.76-3.27l-1-.65-1 .67a19 19 0 01-11.16 3.68A19 19 0 0128.46.67L27.5 0l-1 .65c-4.18 2.77-7.58 3.27-12.76 3.27A17.23 17.23 0 018.2 3L7 2.52 3.53 7.33l.72.95c9.07 12.06 2 25.12-3.07 30.34L0 39.84 1.2 41c.65.65 1.8 1.84 2.74 2.84v.63c-.46 8.7 1.81 15.87 6.74 21.29 5.24 5.76 13.41 9.2 23.08 9.73 2.4 2.18 4.83 4 4.94 4.07l1 .77 1-.77c.1-.08 2.52-1.89 4.92-4.07 9.67-.53 17.84-4 23.08-9.73 4.93-5.42 7.2-12.59 6.74-21.29v-.11a2.87 2.87 0 010-.36v-.15c.94-1 2.09-2.19 2.74-2.84zm-5.73 3.4c.09.88 0 .84.1 1.35 1 19.4-12.48 28.55-28.8 29.23-2.5 2.33-5.25 4.38-5.25 4.38s-2.76-2-5.26-4.38C18.11 73.14 4.6 64 5.63 44.59c.06-.51 0-.47.1-1.35-.94-1-2.49-2.6-3.3-3.42 5.85-6.08 12.68-20 3.2-32.58l2-2.66a18.89 18.89 0 006.13 1.07c5.43 0 9.15-.54 13.71-3.56a20.82 20.82 0 0012.22 4.07A20.81 20.81 0 0051.9 2.09c4.56 3 8.27 3.56 13.71 3.56a18.89 18.89 0 006.13-1.07l2 2.66c-9.48 12.6-2.65 26.5 3.21 32.58-.82.82-2.37 2.43-3.31 3.42z"
            fill="#050505"
          ></path>
          <path
            d="M10.79 32.39c3-6.82 4.08-15.57-.92-24.13a22.41 22.41 0 003.89.36c5.11 0 9.14-.47 13.67-3a23.26 23.26 0 0012.25 3.51 23.27 23.27 0 0012.26-3.54c4.53 2.56 8.56 3 13.67 3a21.07 21.07 0 003.91-.38c-5 8.58-3.91 17.33-.94 24.15H10.79"
            fill="#fff"
          ></path>
          <path
            d="M68.58 32.39c-3-6.82-4.08-15.57.94-24.15a21.07 21.07 0 01-3.91.38c-5.11 0-9.14-.47-13.67-3a23.27 23.27 0 01-12.26 3.51h-.14v23.26z"
            fill="#ffd200"
          ></path>
          <path
            d="M62.22 65.34c5.69-4.16 9.06-10.81 8.56-20.51 0-.55-.09-.58-.14-1.13h-8.42z"
            fill="#002596"
          ></path>
          <path
            d="M53.2 69.52a27 27 0 009-4.18V43.7h-9zM17.15 65.34a27 27 0 009 4.18V43.7h-9z"
            fill="#8b2346"
          ></path>
          <path
            d="M8.59 44.83c-.5 9.7 2.87 16.35 8.56 20.51V43.7H8.73c-.05.55-.09.58-.14 1.13z"
            fill="#002596"
          ></path>
          <path
            d="M39.71 48.48a8.44 8.44 0 014.48 1.29V43.7h-9v6.1a8.43 8.43 0 014.52-1.32zM39.71 65.47a8.43 8.43 0 01-4.53-1.32v6.73H44.19v-6.7a8.44 8.44 0 01-4.48 1.29z"
            fill="#8b2346"
          ></path>
          <path
            d="M44.19 43.7v6.07a8.48 8.48 0 010 14.41v6.7a43.33 43.33 0 009-1.36V43.7zM31.21 57a8.49 8.49 0 014-7.18V43.7h-9v25.82a43.43 43.43 0 009 1.36v-6.73a8.47 8.47 0 01-4-7.15z"
            fill="#002596"
          ></path>
          <path
            d="M12.82 15.9a25.24 25.24 0 01.23 8.6h8.76v7.89h8.6V24.5h9.17v-8.6h-9.17V7.15a25.57 25.57 0 01-3-1.56 21.44 21.44 0 01-5.62 2.25v8.06zM58.09 32.39V8A19.79 19.79 0 0155 7v25.39zM45.72 32.39V8.31a20.36 20.36 0 01-3.09.62v23.46zM64.27 32.39V8.6c-1.07 0-2.09-.07-3.09-.16v24zM51.91 32.39V5.61a28.32 28.32 0 01-3.09 1.61v25.17z"
            fill="#cc092f"
          ></path>
          <path
            d="M8.47 43.68c0 .29-.05.43-.07.59s-.05.29-.07.55C8 52.28 9.81 58.31 13.86 62.76c4.65 5.1 12.18 8 21.79 8.4H43.71c9.6-.4 17.13-3.3 21.78-8.4 4-4.45 5.91-10.48 5.53-17.95 0-.25-.05-.4-.07-.54s0-.3-.07-.59v-.24H8.49zm.37 1.18c0-.24.05-.38.07-.51A3.42 3.42 0 009 44h61.41a3.42 3.42 0 000 .39c0 .13 0 .27.07.5.37 7.31-1.45 13.22-5.41 17.56-4.55 5-12 7.84-21.41 8.23h-8.05c-9.45-.39-16.86-3.23-21.41-8.23-3.91-4.38-5.73-10.29-5.36-17.59zM10.55 32.29l-.16.36H69l-.16-.36c-2.54-5.84-4.45-14.73.92-23.92l.29-.5-.58.13a20.52 20.52 0 01-3.86.38c-5.23 0-9.12-.49-13.54-3l-.13-.08-.13.08a22.92 22.92 0 01-12.13 3.5 22.88 22.88 0 01-12.12-3.5l-.13-.08-.13.08c-4.42 2.5-8.32 3-13.54 3A21.73 21.73 0 019.91 8l-.55-.1.28.49c5.36 9.18 3.45 18.06.91 23.9zm29.29-22.9A23.4 23.4 0 0052 5.89c4.46 2.5 8.4 3 13.66 3a20.94 20.94 0 003.34-.3c-5 9-3.3 17.7-.83 23.54H39.84zM10.36 8.6a22.47 22.47 0 003.4.28c5.26 0 9.2-.49 13.66-3a23.29 23.29 0 0011.9 3.49v22.76H11.18c2.47-5.84 4.21-14.52-.82-23.53z"
            fill="#050505"
          ></path>
          <path
            d="M39.65 65.61A8.68 8.68 0 1031 56.93a8.68 8.68 0 008.65 8.68zm0-.52a8.1 8.1 0 01-4.55-1.39 13 13 0 005.43-1.36c1.38-.83 2.84-1.85 3.11-3.22a2.17 2.17 0 013.16 1.75 8.17 8.17 0 01-7.15 4.22zm-4-6.29a3.52 3.52 0 001.45.52 2.79 2.79 0 002.81-2.26 2 2 0 013.12.76c.72 1.71-.79 2.94-2.73 4.1a13 13 0 01-5.81 1.31 8.23 8.23 0 01-2.16-2.73h.2a3.5 3.5 0 003.1-1.7zm-1.3-4.12a18.31 18.31 0 01.79-4.53 8 8 0 013.82-1.34 2.26 2.26 0 00.22 3.3 2.65 2.65 0 00-.61.67 3.14 3.14 0 00.85 4.27 2.31 2.31 0 01-2.26 1.78c-1.91-.24-2.8-1.99-2.83-4.15zm9.35 3.9a2.66 2.66 0 00-.22-.95 2.44 2.44 0 00-3.81-1A2.66 2.66 0 0139 53c.95-1.5 3.11-.91 5.08.19a8.39 8.39 0 013.73 4.45 7.73 7.73 0 01-.63 2.49 2.63 2.63 0 00-3.5-1.55zm.59-5.77c-1.42-.79-3.29-1.52-4.64-1a1.81 1.81 0 01.09-3.08 8.16 8.16 0 018.07 7.67 9.46 9.46 0 00-3.54-3.59zm-9.78-2.21c-.15.6-.3 1.12-.42 1.66-.42 1.92-.41 4.81 1.15 6.24a3 3 0 01-2.73 1.5h-.42a8.13 8.13 0 012.42-9.39zM32.29 35.76v-1.71h-5.8v8.04h1.75v-3.32h2.37v-1.7h-2.37v-1.31h4.05zM39.08 35.66a1.39 1.39 0 011.36.81v.07l1.62-.74v-.08a3.08 3.08 0 00-3-1.79c-2.1 0-3.57 1.7-3.57 4.14s1.38 4.14 3.52 4.14a3.09 3.09 0 003-1.82v-.07l-1.47-.87v.07a1.56 1.56 0 01-1.47 1c-1.06 0-1.78-1-1.78-2.41s.71-2.45 1.79-2.45zM51.8 37.73a1.81 1.81 0 00.75-1.51c0-1.36-1-2.17-2.58-2.17h-3.69v8h3.65c1.81 0 2.89-1 2.89-2.63a1.89 1.89 0 00-1.02-1.69zM48 35.67h1.9c.78 0 .88.36.88.67s-.26.66-.8.66H48zm2 4.75h-2v-1.86h2c.71 0 1 .29 1 .93s-.33.93-1 .93z"
            fill="#050505"
          ></path>
        </svg>
      </a>
    </nav>

    <div class="nav-container">
      <nav class="navigation-top-container">
        <div class="navigation-top-left">
          <h2 class="follow">FOLLOW FC BARCELONA</h2>
          <a href="https://vb.me/fcbarcelona_channel">
            <svg class="socialicon" viewBox="0 0 365 394.03">
              <path
                d="M334.47 220.86c-9.71 80.07-66.92 85.13-77.46 88.6-4.5 1.47-46.23 12.09-98.67 8.58l-56.86 63-.06-72.61-.45-.11C24.59 286.6 27.16 205.17 28 162.43s8.7-77.77 32-101.31c41.85-38.82 128.08-33 128.08-33 72.82.33 107.73 22.77 115.82 30.29 26.89 23.59 40.58 79.89 30.57 162.45M323.8 38.4C314.23 29.4 275.58.67 189.49.28c0 0-101.51-6.27-151 40.21C10.94 68.7 1.25 110 .22 161.14s-2.34 147.08 88 173.09h.08l-.05 39.68S87.65 390 98 393.27c12.5 4 19.84-8.24 31.77-21.4 6.56-7.22 15.59-17.83 22.4-25.94 61.77 5.29 109.26-6.85 114.65-8.65 12.48-4.15 83-13.39 94.51-109.28 11.84-98.87-5.74-161.39-37.49-189.6"
              ></path>
              <path
                d="M268.72 232.8s-11.58-9.88-17.22-14.13c-5.32-4-13.79-9.37-18.53-12.11-8.51-4.84-17.2-1.8-20.78 3l-7.45 9.59c-3.82 4.86-9.71 4-11.25 3.73-11-2.76-22.72-9.65-34.7-21.25s-19.46-23.94-22.08-36.65l-.19-.84c-.7-5.22.17-7.64 2.3-11.2l.4-.33c5-4.68 14.37-10.38 15.62-15.8 3.66-9.42-12.26-29.07-14.53-32.53 0 0-11.58-15.33-15.7-18.26-4.44-3.7-11.33-5.81-18.27-1.54l-.36.26C86 98.2 78.8 106 80.77 117.54l1 4.66c10.12 31.89 29.65 65.9 58.79 96.18 28.82 29.9 60 47.81 90.72 60.22 8 2.65 16.27.36 24.76-6.89l.14-.1A79.14 79.14 0 00271.71 252v-.14c3.74-7.37 2.47-14.35-3-19.1M220.88 163a2.32 2.32 0 01-2.29-2.22c-.4-8.27-2.63-14.6-6.62-18.83s-9.93-6.55-17.69-7a2.36 2.36 0 01.25-4.71c9 .5 15.93 3.33 20.74 8.41s7.45 12.42 7.91 21.86A2.33 2.33 0 01221 163h-.12"
              ></path>
              <path
                d="M243.62 170.76h-.06a2.33 2.33 0 01-2.24-2.41c.35-15.87-4.28-29.29-13.79-39.9A50.2 50.2 0 00210.45 116a69 69 0 00-22.94-5.44 2.35 2.35 0 01.33-4.69c18.33 1.38 32.82 7.9 43.09 19.4s15.36 26.06 15 43.18a2.35 2.35 0 01-2.3 2.3"
              ></path>
              <path
                d="M266.9 180.08a2.32 2.32 0 01-2.3-2.34c-.11-14-2.22-26.72-6.3-37.73a78.88 78.88 0 00-18.2-28.56A82 82 0 00213 93.29a89.65 89.65 0 00-33.12-6.24 2.35 2.35 0 010-4.7c25.16.19 46.49 8.84 63.43 25.74a83.24 83.24 0 0119.28 30.26c4.27 11.52 6.49 24.77 6.6 39.36a2.32 2.32 0 01-2.27 2.37z"
              ></path>
            </svg>
          </a>
          <a href="https://twitter.com/fcbarcelona">
            <svg class="socialicon" viewBox="0 0 512.002 512.002">
              <path
                d="M512.002 97.211c-18.84 8.354-39.082 14.001-60.33 16.54 21.686-13 38.342-33.585 46.186-58.115a210.29 210.29 0 01-66.705 25.49c-19.16-20.415-46.461-33.17-76.674-33.17-58.011 0-105.042 47.029-105.042 105.039 0 8.233.929 16.25 2.72 23.939-87.3-4.382-164.701-46.2-216.509-109.753-9.042 15.514-14.223 33.558-14.223 52.809 0 36.444 18.544 68.596 46.73 87.433a104.614 104.614 0 01-47.577-13.139c-.01.438-.01.878-.01 1.321 0 50.894 36.209 93.348 84.261 103a105.245 105.245 0 01-27.674 3.687c-6.769 0-13.349-.66-19.764-1.888 13.368 41.73 52.16 72.104 98.126 72.949-35.95 28.176-81.243 44.967-130.458 44.967-8.479 0-16.84-.496-25.058-1.471 46.486 29.807 101.701 47.197 161.021 47.197 193.211 0 298.868-160.062 298.868-298.872 0-4.554-.104-9.084-.305-13.59 20.526-14.809 38.335-33.309 52.417-54.373z"
              ></path>
            </svg>
          </a>
          <a href="https://www.facebook.com/fcbarcelona">
            <svg class="socialicon" viewBox="0 0 257.72 257.72">
              <path
                d="M243.49 0H14.22A14.22 14.22 0 000 14.22v229.27a14.23 14.23 0 0014.22 14.23h123.44v-99.8h-33.59V119h33.59V90.34c0-33.29 20.32-51.42 50-51.42a273.05 273.05 0 0130 1.54v34.78H197.1c-16.15 0-19.28 7.68-19.28 18.94V119h38.52l-5 38.9h-33.5v99.8h65.67a14.23 14.23 0 0014.23-14.23V14.22A14.23 14.23 0 00243.49 0z"
              ></path>
            </svg>
          </a>
          <a href="https://www.instagram.com/fcbarcelona/">
            <svg class="socialicon" viewBox="0 0 169.063 169.063">
              <path
                d="M122.406 0H46.654C20.929 0 0 20.93 0 46.655v75.752c0 25.726 20.929 46.655 46.654 46.655h75.752c25.727 0 46.656-20.93 46.656-46.655V46.655C169.063 20.93 148.133 0 122.406 0zm31.657 122.407c0 17.455-14.201 31.655-31.656 31.655H46.654C29.2 154.063 15 139.862 15 122.407V46.655C15 29.201 29.2 15 46.654 15h75.752c17.455 0 31.656 14.201 31.656 31.655v75.752z"
              ></path>
              <path
                d="M84.531 40.97c-24.021 0-43.563 19.542-43.563 43.563 0 24.02 19.542 43.561 43.563 43.561s43.563-19.541 43.563-43.561c0-24.021-19.542-43.563-43.563-43.563zm0 72.123c-15.749 0-28.563-12.812-28.563-28.561 0-15.75 12.813-28.563 28.563-28.563s28.563 12.813 28.563 28.563c0 15.749-12.814 28.561-28.563 28.561zM129.921 28.251c-2.89 0-5.729 1.17-7.77 3.22a11.053 11.053 0 00-3.23 7.78c0 2.891 1.18 5.73 3.23 7.78 2.04 2.04 4.88 3.22 7.77 3.22 2.9 0 5.73-1.18 7.78-3.22 2.05-2.05 3.22-4.89 3.22-7.78 0-2.9-1.17-5.74-3.22-7.78-2.04-2.05-4.88-3.22-7.78-3.22z"
              ></path>
            </svg>
          </a>
          <a href="https://www.youtube.com/user/fcbarcelona">
            <svg class="socialicon" viewBox="0 0 28 20.05">
              <path
                d="M27.72 4.32a6.17 6.17 0 00-1.11-2.82A3.93 3.93 0 0023.8.29C19.88 0 14 0 14 0S8.12 0 4.2.29A3.93 3.93 0 001.39 1.5 6.17 6.17 0 00.28 4.32 44 44 0 000 8.94v2.16a43.69 43.69 0 00.28 4.61 6.19 6.19 0 001.11 2.83 4.7 4.7 0 003.09 1.22c2.24.22 9.52.29 9.52.29s5.88 0 9.8-.3a4 4 0 002.81-1.21 6.19 6.19 0 001.11-2.83A43.69 43.69 0 0028 11.1V8.94a44 44 0 00-.28-4.62zm-16.61 9.4v-8l7.56 4z"
              ></path>
            </svg>
          </a>
          <a href="https://www.tiktok.com/@fcbarcelona">
            <svg class="socialicon" viewBox="-32 0 512 512">
              <path
                d="M432.734 112.465c-53.742 0-97.464-43.723-97.464-97.465 0-8.285-6.715-15-15-15h-80.336c-8.282 0-15 6.715-15 15v329.367c0 31.594-25.707 57.297-57.301 57.297s-57.297-25.703-57.297-57.297c0-31.597 25.703-57.3 57.297-57.3 8.285 0 15-6.715 15-15V191.73c0-8.28-6.715-15-15-15C75.199 176.73 0 251.934 0 344.367 0 436.801 75.2 512 167.633 512S335.27 436.8 335.27 344.367V198.574c29.851 15.918 63.074 24.227 97.464 24.227 8.286 0 15-6.715 15-15v-80.336c0-8.281-6.714-15-15-15zm0 0"
              ></path>
            </svg>
          </a>
          <a href="https://www.twitch.tv/fcbarcelona">
            <svg class="socialicon" viewBox="0 0 260 260">
              <path
                d="M17.458 0L0 46.556v186.201h63.983v34.934h34.931l34.898-34.934h52.36L256 162.954V0H17.458zm23.259 23.263H232.73v128.029l-40.739 40.741H128L93.113 226.92v-34.886H40.717V23.263zm64.008 116.405H128V69.844h-23.275v69.824zm63.997 0h23.27V69.844h-23.27v69.824z"
              ></path>
            </svg>
          </a>
        </div>

        <div class="navigation-top-right">
          <div class="user-button-wraper">
            <button class="user-login-button">
              <svg class="icon-button" viewBox="0 0 78.09 76.86">
                <path
                  d="M41 72.85c-26.5 0-34.5-2.2-36.7-3.1a8.48 8.48 0 014.8-6.5c6.3-3 16.5-6.4 16.61-6.5a2 2 0 001.3-1.4A31.82 31.82 0 0128.36 51a2.41 2.41 0 00.81-.2 2 2 0 001.19-1.9v-.3a10.65 10.65 0 002.8 1.9 13.68 13.68 0 005.9 1.3 14.23 14.23 0 004.5-.8 13.93 13.93 0 004.4-2.9v.9a2.06 2.06 0 001.2 1.9 2.35 2.35 0 00.8.2 31 31 0 011.4 4.39 2 2 0 001.3 1.4c.1 0 10.3 3.5 16.6 6.5a8.51 8.51 0 014.8 6.6c-2 .81-9.4 2.91-33.1 2.91zM26.16 33a26.33 26.33 0 01-1-3.7 11.05 11.05 0 01-.2-2.1 2.7 2.7 0 00.8-.7 1.82 1.82 0 000-2c-.1-.2-2.7-5.1.2-12.4.4-.9.4-.9 1.4-1.1a12 12 0 003.5-.8 2 2 0 001.2-1.8c0-.3.3-3.3 5.3-4.1 1.9-.3 6.9 1.5 10 2.89 2.5 1 4.4 3 6 6a6.74 6.74 0 01.5 3.11 32.87 32.87 0 01-1.5 8.6 2.25 2.25 0 00.1 1.4c.1.1.1.3.2.39a4.93 4.93 0 00.7.61 11.75 11.75 0 01-.2 2.1 13.09 13.09 0 01-1.2 4.1 1 1 0 00-.5.9v.4c0 1.39-.5 5.3-2.6 6.8-.1.1-.2.1-.3.2-2.3 2.4-4.6 4.8-6.4 5.5a9.54 9.54 0 01-7.4-.4 13 13 0 01-4.9-4.7c0-.1-.1-.1-.1-.2l-.1-.1-.3-.3c-1.8-1.4-2.4-4.5-2.5-6.2v-.6c0-.6 0-1-.5-1.4 0-.1-.1-.2-.2-.4zM71 59.65c-5.4-2.5-13.2-5.3-16-6.3a21.42 21.42 0 00-1.6-4.4 3.55 3.55 0 00-1.4-1.7l.1-3.2a5.24 5.24 0 001-1.1c0-.1.1-.1.1-.2s.2-.3.31-.4a.35.35 0 01.1-.2c.1-.1.1-.3.2-.4s.1-.2.1-.3.1-.2.2-.4.1-.19.1-.3.1-.2.2-.39.1-.2.1-.31.1-.19.1-.39.1-.2.1-.3.1-.2.1-.4.11-.2.11-.3.1-.2.1-.4a32966741879589.32 32966741879589.32 0 00.2-.6v-.3a.39.39 0 01.1-.31v-2a5.17 5.17 0 00.6-1.3 38.57 38.57 0 001.1-4c.5-2.39.31-4.2-.5-5.3.81-2.9 2.2-9.6.4-13.3-2-4-4.6-6.5-8-7.9-1.4-.6-8.4-3.7-12.1-3.2-5.6.81-7.9 4-8.5 6.5a7 7 0 01-1.4.2c-1.9.2-3.5.61-4.7 3.5-2.7 6.7-1.6 11.9-.7 14.3a.8.8 0 00-.19.5 7.28 7.28 0 00-.11 4.7 17.85 17.85 0 001.5 4.9c.11.1.11.2.2.4V37a.37.37 0 00.1.3v.2a.35.35 0 00.11.3.36.36 0 00.1.3c0 .11.1.2.1.4a.37.37 0 00.1.3c0 .11.1.2.1.4s.1.2.1.3.11.2.11.4.1.2.1.3.1.2.1.4.1.2.1.3.1.2.2.4.1.2.1.3.1.2.2.3.1.2.2.3.1.2.2.3.1.2.2.3.2.2.2.3.1.2.2.31l.3.3c.1.1.1.2.2.2l.1.1.1 3.2a3.55 3.55 0 00-1.4 1.7c-.6 1.3-1.2 3.19-1.6 4.39-2.8 1-10.6 3.7-16 6.3A12.46 12.46 0 000 70.86a1.74 1.74 0 00.4 1.19c1.1 1.4 7.2 4.81 40.4 4.81 30 0 35.8-3.4 36.89-4.81a1.69 1.69 0 00.4-1.19A12.13 12.13 0 0071 59.65z"
                ></path>
              </svg>
              Login
            </button>
            <button class="user-register-button">
              <svg class="icon-button" viewBox="0 0 79.3 80.6">
                <path
                  d="M62.2 65.5c5.7-4.2 9.1-10.8 8.6-20.5a4.5 4.5 0 01-.1-1.1h-8.5zM8.6 44.9c-.5 9.7 2.9 16.3 8.6 20.5V43.8H8.8a5.2 5.2 0 00-.2 1.1zm35.6-1.1v6.1a8.5 8.5 0 010 14.4V71a42.4 42.4 0 009-1.4V43.8zm-13 13.3a8.5 8.5 0 014-7.2v-6.1h-9v25.8a42.4 42.4 0 009 1.4v-6.7a8.5 8.5 0 01-4-7.2zM12.8 16a25 25 0 01.2 8.6h8.8v7.9h8.6v-7.9h9.2V16h-9.2V7.3l-3-1.6a19.7 19.7 0 01-5.6 2.2V16zm45.3 16.5V8.1a18.1 18.1 0 01-3.1-.9v25.4h3.1zm-12.4 0V8.4a15.5 15.5 0 01-3.1.6v23.5zm18.5 0V8.7l-3.1-.2v24zm-12.3 0V5.7l-3.1 1.6v25.2z"
                ></path>
                <path
                  d="M79.3 40l-1.1-1.3c-5-5.2-12.1-18.3-3.1-30.3l.7-.9-3.4-4.8-1.2.4a18.4 18.4 0 01-5.6 1c-5.2 0-8.6-.5-12.8-3.3l-1-.6-1 .7a18.8 18.8 0 01-11.1 3.6A18.9 18.9 0 0128.5.7l-1-.7-1 .6c-4.2 2.8-7.6 3.3-12.8 3.3a16.2 16.2 0 01-5.6-1l-1.2-.4-3.4 4.8.7.9c9.1 12.3 2 25.3-3 30.5L0 39.9l1.2 1.3L3.9 44v.6c-.5 8.8 1.8 16 6.7 21.4s13.4 9.2 23.1 9.7c2.4 2.2 4.8 4 4.9 4.1l1 .8 1-.8c.1-.1 2.5-1.9 4.9-4.1 9.7-.5 17.8-4 23.1-9.7s7.2-12.6 6.7-21.3V44l2.7-2.8zm-5.7 3.4c.1.9 0 .8.1 1.4 1 19.4-12.5 28.5-28.8 29.2-2.5 2.3-5.2 4.4-5.2 4.4a54.4 54.4 0 01-5.3-4.4c-16.3-.7-29.8-9.9-28.8-29.3.1-.5 0-.5.1-1.4l-3.3-3.4c5.9-6.1 12.7-20 3.2-32.6l2-2.7a17.8 17.8 0 006.1 1.1c5.4 0 9.2-.5 13.7-3.6a20.8 20.8 0 0012.2 4.1 20.8 20.8 0 0012.2-4.1c4.6 3 8.3 3.6 13.7 3.6a17.8 17.8 0 006.1-1.1l2 2.7c-9.5 12.6-2.7 26.5 3.2 32.6z"
                ></path>
                <path
                  d="M8.4 43.8a1.1 1.1 0 01-.1.6 1.1 1.1 0 01-.1.5c-.4 7.5 1.5 13.5 5.5 17.9s12.2 8 21.8 8.4h8.1c9.6-.4 17.1-3.3 21.8-8.4s5.9-10.5 5.5-18c0-.3 0-.4-.1-.5a1.5 1.5 0 00-.1-.6v-.2H8.5zm.4 1.2a.7.7 0 01.1-.5.8.8 0 01.1-.4h61.4c0 .2 0 .3.1.4a1.1 1.1 0 00.1.5c.4 7.3-1.4 13.2-5.4 17.6s-12 7.8-21.4 8.2h-8.1c-9.5-.4-16.9-3.3-21.5-8.3S8.4 52.3 8.8 45zm1.7-12.6l-.2.4h58.6l-.2-.4c-2.5-5.8-4.5-14.7.9-23.9l.3-.5h-.6a25.8 25.8 0 01-3.9.4c-5.2 0-9.1-.5-13.5-3h-.2A23.5 23.5 0 0139.6 9a22.3 22.3 0 01-12.1-3.5h-.2c-4.4 2.5-8.3 3-13.5 3a16.9 16.9 0 01-3.8-.4h-.6l.3.5c5.3 9.1 3.4 18 .8 23.8zM39.8 9.5A23.2 23.2 0 0051.9 6c4.5 2.5 8.4 3 13.7 3a19.5 19.5 0 003.4-.3c-5 9-3.3 17.7-.8 23.5H39.8zm-29.5-.8l3.4.3c5.3 0 9.2-.5 13.7-3a23.5 23.5 0 0011.9 3.5v22.7H11.2c2.4-5.8 4.2-14.5-.9-23.5zm22 27.2v-1.7h-5.8v8h1.7v-3.3h2.4v-1.7h-2.4v-1.3h4.1zm6.8-.1a1.6 1.6 0 011.4.8l1.6-.7a3.1 3.1 0 00-3-1.8c-2.1 0-3.6 1.7-3.6 4.1s1.4 4.1 3.5 4.1a3.1 3.1 0 003-1.8l-1.5-.9a1.6 1.6 0 01-1.5 1c-1.1 0-1.8-1-1.8-2.4s.8-2.4 1.9-2.4zm13.4.5c0-1.4-1-2.2-2.6-2.2h-3.7v8h3.7c1.8 0 2.9-1 2.9-2.6a1.8 1.8 0 00-1-1.7 1.6 1.6 0 00.7-1.5zm-4.5-.5h1.9c.8 0 .9.4.9.7a.7.7 0 01-.8.7h-2zm2 4.7h-2v-1.8h2c.7 0 1 .3 1 .9s-.4.9-1 .9z"
                ></path>
                <path
                  d="M39.6 65.7a8.7 8.7 0 10-8.7-8.7 8.7 8.7 0 008.7 8.7zm0-.5a8.1 8.1 0 01-4.6-1.4 12.4 12.4 0 005.4-1.4c1.4-.8 2.8-1.8 3.1-3.2a2.2 2.2 0 013.2 1.7 7.9 7.9 0 01-7.1 4.3zm-4-6.3a3.3 3.3 0 001.5.5 2.9 2.9 0 002.8-2.3 1.9 1.9 0 013.1.8c.7 1.7-.8 2.9-2.7 4.1a12.9 12.9 0 01-5.8 1.3 9.7 9.7 0 01-2.2-2.7h.2a3.4 3.4 0 003.1-1.7zm-1.3-4.1a17 17 0 01.8-4.5 8.2 8.2 0 013.8-1.3 2.4 2.4 0 00.2 3.3l-.6.7a3.2 3.2 0 00.8 4.3 2.3 2.3 0 01-2.3 1.8c-1.8-.4-2.7-2.2-2.7-4.3zm9.4 3.9a2.9 2.9 0 00-.2-.9 2.4 2.4 0 00-3.8-1 2.6 2.6 0 01-.7-3.6c.9-1.5 3.1-.9 5.1.2a8.3 8.3 0 013.7 4.4 10.2 10.2 0 01-.6 2.5 2.7 2.7 0 00-3.5-1.6zm.5-5.8c-1.4-.8-3.3-1.5-4.6-1a1.8 1.8 0 01.1-3.1 8.2 8.2 0 018.1 7.7 10.3 10.3 0 00-3.6-3.6zm-9.7-2.2a10.5 10.5 0 00-.4 1.7c-.4 1.9-.4 4.8 1.1 6.2a2.8 2.8 0 01-2.7 1.5h-.4a7.8 7.8 0 01-.6-3.1 8 8 0 013-6.3z"
                ></path>
              </svg>
              Register as a Culer
            </button>

            <div class="right-tip">
              <div class="text">
                <span>EN</span>
                <div class="ul-float">
                  <ul>
                    <li class="title">Choose your language</li>
                    <li
                      v-for="item in ul_ls"
                      :key="item"
                      @click="li_click(item)"
                    >
                      <span>{{ item }}</span
                      ><span class="text-right" v-if="current_text == item"
                        >Viewing</span
                      >
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </nav>

      <div class="wrapper">
        <div class="tabs">
          <div
            class="tabs-item"
            v-for="item in tabs_ls"
            :key="item.id"
            @click="nav_click(item)"
          >
            {{ item.title }}
            <div class="bottom-hover" v-if="item.title != item.title"></div>
            <div v-else class="bottom-hover float-block">
              <div v-for="el in tab_text_ls" :key="el">
                {{ el }}
              </div>
            </div>
          </div>
        </div>

        <button type="button" @click="modal_open = true">Open</button>

        <teleport to="body">
          <div v-if="modalOpen" class="modal">
            <div class="modal-box">
              Я телепортированное модальное окно! (Мой родитель "body")
              <button type="button" @click="modal_open = false">Close</button>
            </div>
          </div>
        </teleport>
        <!-- data() { return { modalOpen: false } } -->
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { defineProps, defineEmits, ref, reactive } from "vue";

type el = {
  items: string;
};

type tab_el = {
  title: string;
  id: number;
  com: any;
  subitems: el[];
};
defineProps<{
  tabs_ls: tab_el[];
}>();
const ul_ls: string[] = [
  "English",
  "Ctatala",
  "Castellano",
  "Francais",
  "日本语",
  "中文",
];

const emit = defineEmits(["nav_click"]);
const nav_click = (item: tab_el) => {
  emit("nav_click", item);
};

let current_text = ref<string>("EN");
const li_click = (item: string) => {
  console.log(item);
  current_text.value = item;
};

let tab_text_ls = reactive<string[]>(["Subscribe", "Draws", "Benefits"]);
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.header-container {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  min-height: 120px;
  margin-bottom: 16px;
  border-bottom: 1px solid #2a363b;
  margin: 0;
  padding: 0;
}
.header-container::after {
  display: block;
  z-index: 2;
  position: absolute;
  content: "";
  bottom: -0.5rem;
  left: 0;
  right: 0;
  height: 0.5rem;
  background: linear-gradient(90deg, #154284 0, #cd122d);
  background-image: linear-gradient(
    90deg,
    rgb(21, 66, 132) 0px,
    rgb(205, 18, 45)
  );
}
.logo-container {
  padding: 10px;
}
.navigation-logo {
  display: flex;
  flex-grow: 1;
  position: relative;
  width: 290px;
  font-weight: 400;
  background-color: transparent;
  padding-left: 30px;
  align-items: center;
  transition: height 0.2s;
  transition-property: height;
  transition-duration: 0.2s;
  transition-timing-function: ease;
  transition-delay: 0s;
  font-family: fcb-regular, Arial, Helvetica Neue, Helvetica, sans-serif;
}
.logo-icon {
  width: 90%;
  height: 4rem;
  fill: #fff;
}
.navigation-top-container {
  display: flex;
  justify-content: space-between;
  width: 100%;
  padding: 0;
  //  margin-right: 20px;
  background-color: rgb(1, 1, 41);
  height: 50px;
}
.navigation-top-left {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.follow {
  font-size: 10px;
  margin-right: 10px;
  margin-left: 15px;
  color: hsla(0, 0%, 100%, 0.6);
}
.socialicon {
  width: 17px;
  height: 17px;
  margin-right: 15px;
  fill: hsla(0, 0%, 100%, 0.6);
}
.navigation-top-right {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.user-button-wraper {
  display: flex;
  align-items: center;
}
.user-login-button {
  display: inline-flex;
  align-items: center;
  background-color: rgb(1, 1, 41);
  padding: 8px;
  cursor: pointer;
  color: #fff;
  font-weight: 700;
  border-width: 1px;
  border-radius: 4px;
}
.user-login-button:focus,
.user-login-button:hover {
  text-decoration: underline;
}
.icon-button {
  width: 16px;
  height: 16px;
  margin-right: 0.4rem;
  fill: #fff;
}
.user-register-button {
  display: inline-flex;
  align-items: center;
  margin-right: 15px;
  padding: 8px;
  cursor: pointer;
  color: #fff;
  font-weight: 700;
  border-width: 1px;
  border-radius: 4px;
  border-style: outset;
  border-color: -internal-light-dark(rgb(118, 118, 118), rgb(133, 133, 133));
  background: linear-gradient(90deg, #8c1a17, #cd122d);
  background-image: linear-gradient(90deg, rgb(140, 26, 23), rgb(205, 18, 45));
}

.nav-container {
  width: 100%;
}
.right-tip {
  height: 100%;
  .text {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    color: #fff;
    font-size: 14px;
    padding-right: 30px;
    position: relative;
    height: 100%;

    .ul-float {
      color: #181733;
      width: 278px;
      position: absolute;
      top: 100%;
      right: 8px;
      z-index: 999;
      background-color: #fff;
      border-radius: 2px;
      display: none;
      border: 1px solid #f6f6f6;
      ul {
        list-style-type: none;
        width: 100%;
        margin: 0px;
        padding: 0px;
        padding-bottom: 16px;
        font-size: 14px;
        color: #222;
        li {
          border-bottom: 1px solid #f6f6f6;
          width: 100%;
          padding: 8px 16px;
          padding-left: 24px;
          display: flex;
          justify-content: space-between;
          .text {
            color: #767676;
            font-size: 12px;
          }
          .text-right {
            color: #767676;
            font-size: 12px;
            margin-right: 60px;
          }
        }
        .title {
          color: #767676;
          margin-top: 10px;
          font-size: 12px;
          border: none;
          margin-bottom: 12px;
        }
      }
    }
    .ul-float::before {
      content: " ";
      border-top: 0;
      border-bottom: 10px solid #fff;
      border-left: 8px solid transparent;
      border-right: 8px solid transparent;
      position: absolute;
      top: -10px;
      right: 5px;
    }
    .ul-float:hover {
      display: block;
    }
  }
  .text:hover {
    cursor: pointer;
    .ul-float {
      display: block;
    }
  }
  .text::after {
    content: " ";
    display: inline-block;
    vertical-align: middle;
    border-bottom: 0;
    border-top: 6px solid #fff;
    border-left: 3px solid transparent;
    border-right: 3px solid transparent;
    position: absolute;
    right: 20px;
  }
}

.wrapper {
  display: flex;
}

.tabs {
  height: 70px;
  display: flex;
  width: 100%;
  color: #fff;
  .tabs-item {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    border-left: 1px solid #29283d;
    position: relative;
    .bottom-hover {
      display: none;
      position: absolute;
      bottom: -8px;
      width: 100%;
      height: 8px;
      background-color: rgb(255, 208, 0);
    }
    .float-block {
      z-index: 100;
      background: #153c79;
      position: absolute;
      bottom: -100px;
      left: 0;
      height: auto;
      div {
        padding: 8px 10px;
        text-align: center;
      }
    }
    .float-block::before {
      content: " ";
      border-top: 0;
      border-bottom: 10px solid #153c79;
      border-left: 6px solid transparent;
      border-right: 6px solid transparent;
      position: absolute;
      top: -10px;
      right: calc(50% - 6px);
    }
  }
  .tabs-item:hover {
    cursor: pointer;
    .bottom-hover {
      display: block;
    }
  }
}

.modal {
  position: fixed;
  top: 0;
  right: 0;
  // bottom: 0;
  left: 0;
  height: 70%;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.modal-box {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color: white;
  width: 300px;
  height: 350px;
  padding: 5px;
}
</style>
