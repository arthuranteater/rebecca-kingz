<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=1440, maximum-scale=1.0" />
    <link rel="shortcut icon" href="./img/favicon.png" />
    <meta name="og:type" content="website" />
    <meta name="twitter:card" content="photo" />
    <link rel="stylesheet" type="text/css" href="css/desktop-7.css" />
    <style>
      @import url("https://fonts.googleapis.com/css?family=Zilla+Slab:700,400");

      .component-wrapper a,
      .screen a {
        text-decoration: none;
        display: contents;
      }

      .full-width-a {
        width: 100%;
      }

      .full-height-a {
        height: 100%;
      }

      .screen textarea:focus,
      .screen input:focus {
        outline: none;
      }

      .screen *,
      .component-wrapper * {
        box-sizing: border-box;
      }

      .screen div {
        -webkit-text-size-adjust: none;
      }

      .container-center-vertical,
      .container-center-horizontal {
        pointer-events: none;
        display: flex;
        flex-direction: row;
        padding: 0;
        margin: 0;
      }

      .container-center-vertical {
        align-items: center;
        height: 100%;
      }

      .container-center-horizontal {
        justify-content: center;
        width: 100%;
      }

      .container-center-vertical > *,
      .container-center-horizontal > * {
        pointer-events: auto;
        flex-shrink: 0;
      }

      .component-wrapper,
      .screen {
        overflow-wrap: break-word;
        word-wrap: break-word;
        word-break: break-all;
        word-break: break-word;
      }

      .auto-animated div {
        opacity: 0;
        position: absolute;
        --z-index: -1;
      }

      .auto-animated .container-center-vertical,
      .auto-animated .container-center-horizontal {
        opacity: 1;
      }

      .overlay {
        position: absolute;
        opacity: 0;
        display: none;
        top: 0;
        width: 100%;
        height: 100%;
        position: fixed;
      }

      .animate-appear {
        opacity: 0;
        display: block;
        animation: reveal 0.3s ease-in-out 1 normal forwards;
      }

      .animate-disappear {
        opacity: 1;
        display: block;
        animation: reveal 0.3s ease-in-out 1 reverse forwards;
      }

      .animate-nodelay {
        animation-delay: 0s;
      }

      @keyframes reveal {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
      .align-self-flex-start {
        align-self: flex-start;
      }
      .align-self-flex-end {
        align-self: flex-end;
      }
      .align-self-flex-center {
        align-self: center;
      }
      .valign-text-middle {
        display: flex;
        flex-direction: column;
        justify-content: center;
      }
      .valign-text-bottom {
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
      }
      input:focus {
        outline: none;
      }
      .component-wrapper,
      .component-wrapper * {
        pointer-events: none;
      }

      .component-wrapper a *,
      .component-wrapper a,
      .component-wrapper input,
      .component-wrapper video,
      .component-wrapper iframe,
      .listeners-active,
      .listeners-active * {
        pointer-events: auto;
      }

      .hidden,
      .hidden * {
        visibility: hidden;
        pointer-events: none;
      }

      .smart-layers-pointers,
      .smart-layers-pointers * {
        pointer-events: auto;
        visibility: visible;
      }

      .component-wrapper.not-ready,
      .component-wrapper.not-ready * {
        visibility: hidden !important;
      }

      .listeners-active-click,
      .listeners-active-click * {
        cursor: pointer;
      }
    </style>
    <meta name="author" content="AnimaApp.com - Design to code, Automated." />

  </head>
  <body style="margin: 0; background: rgba(255, 255, 255, 1)">
    <input type="hidden" id="anPageName" name="page" value="desktop-7" />
    <div class="container-center-horizontal">
      <div class="desktop-7 screen">
        <div class="rectangle-18-C61RwL"></div>
        <div class="resum-C61RwL">Resumé</div>
        <div class="portfolio-C61RwL">Portfolio</div>
        <div class="rectangle-20-C61RwL"></div>
        <div class="lets-conne-00gmailcom-C61RwL">
          Let’s Connect!&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          907-242-0377&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rebeccaboggs00@gmail.com
        </div>
        <img class="clipart129550-2-C61RwL" src="img/clipart129550-2@2x.png" />
        <img class="clipart1308911-2-C61RwL" src="img/clipart1308911-2@2x.png" />
        <img class="x1200px-med-monogram-1-C61RwL" src="img/1200px-medium-logo-monogram-1@2x.jpg" />
        <img class="screen-sho-5-at-101-2-C61RwL" src="img/screen-shot-2021-01-15-at-1-01-2@1x.jpg" />
        <div class="rectangle-282-C61RwL"></div>
        <div class="a-user-exp-e-designer-C61RwL">A User Experience Designer</div>
        <div class="hi-im-C61RwL">Hi! I’m</div>
        <div class="rebecca-boggs-C61RwL">Rebecca Boggs</div>
        <img class="img7939-1-C61RwL" src="img/img-7939-1@2x.svg" />
      </div>
    </div>
  </body>
</html>
