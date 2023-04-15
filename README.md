# HTML
body {
  color: rgb(var(--foreground-rgb));
  background: linear-gradient(to bottom,
      transparent,
      rgb(var(--background-end-rgb))) rgb(var(--background-start-rgb));
}

.main-container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.main-content {
  flex-grow: 1;
  padding: 1rem;
}

.iframe-container {
  width: 100%;
  height: 0;
  padding-bottom: 56.25%;
  /* 16:9 aspect ratio */
  position: relative;
}

iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
