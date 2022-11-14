<!--
// Copyright 2021 Google LLC. All Rights Reserved.
//
// Licensed under the Apache License, Version 2.0 (the "License");
// you may not use this file except in compliance with the License.
// You may obtain a copy of the License at
//
// http://www.apache.org/licenses/LICENSE-2.0
//
// Unless required by applicable law or agreed to in writing, software
// distributed under the License is distributed on an "AS IS" BASIS,
// WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
// See the License for the specific language governing permissions and
// limitations under the License.
-->

<!DOCTYPE html>
<html>

<head>
  <title>Cast Videos: Google Cast Chrome Sender SDK Demo App</title>
  <link rel="icon" type="image/x-icon" href="imagefiles/favicon.ico" />
  <link rel="icon" type="image/png" href="imagefiles/favicon-16x16.png" />
  <link rel="icon" type="image/png" href="imagefiles/favicon-32x32.png" />
  <link rel="icon" type="image/png" href="imagefiles/favicon-64x64.png" />
  <link rel="stylesheet" type="text/css" href="css/CastVideos.css">
  <link href='//fonts.googleapis.com/css?family=Roboto&subset=latin,cyrillic-ext,greek-ext,latin-ext' rel='stylesheet'
    type='text/css'>
</head>

<body>
  <div id="top_header">
    <div id="logo"></div>
  </div>
  <div id="main_video">
    <div class="imageSub">
      <!-- Put Your Image Width -->
      <div class="blackbg" id="playerstatebg">IDLE</div>
      <div class=label id="playerstate">IDLE</div>
      <img src="imagefiles/bunny.jpg" id="video_image">
      <div id="video_image_overlay"></div>
      <video id="video_element">
      </video>
    </div>

    <div id="skip">Skip Ad</div>

    <div id="media_control">
      <div id="play"></div>
      <div id="pause"></div>
      <div id="audio_bg"></div>
      <div id="audio_bg_track"></div>
      <div id="audio_indicator"></div>
      <div id="audio_bg_level"></div>
      <div id="audio_on"></div>
      <div id="audio_off"></div>
      <div id="progress_bar_container">
        <div id="progress_bg"></div>
        <div id="seekable_window"></div>
        <div id="progress"></div>
        <div id="unseekable_overlay"></div>
        <div id="progress_indicator"></div>
      </div>
      <div id="fullscreen_expand"></div>
      <div id="fullscreen_collapse"></div>
      <google-cast-launcher id="castbutton"></google-cast-launcher>
      <div id="currentTime">00:00:00</div>
      <div id="duration">00:00:00</div>
      <img id="live_indicator">
    </div>
  </div>
  <div id="media_info">
    <div id="media_title"></div>
    <div id="feature_toggle_container">
      <input type="radio" id="none" name="feature" value="none" checked>None<br>
      <input type="radio" id="ads" name="feature" value="ads">Ads<br>
      <input type="radio" id="live" name="feature" value="live">Live
    </div>
    <div id="media_subtitle"></div>
  </div>

  <div id="carousel"></div>

  <div id="footer">
    <div id="copyright">Copyright 2021 Google LLC. All Rights reserved.</div>
    <div id="footer_content">Visit the <a id="footer_content_link" href="https://developers.google.com/cast/">Google
        Cast Developer Site</a></div>
    <div id="footer_language">Language English</div>
  </div>

  <script src="CastVideos.js" type="module"></script>
  <script type="text/javascript" src="https://www.gstatic.com/cv/js/sender/v1/cast_sender.js?loadCastFramework=1"></script>
</body>

</html>

## Live Demo

_https://amaapp333.github.io/MaxBabe_

## Download 

_https://github.com/apps/maliek-galant_

# Google Feature

This example shows how to create an AMP page with `amp-story` using Next.js and the AMP feature.

## Deploy Free Forever

_https://amaapp333.github.io/MaxBabe/_

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), or [pnpm](https://pnpm.io) to bootstrap the example:

```bash
npx create-next-app --example amp-story amp-story-app
```

```bash
yarn create next-app --example amp-story amp-story-app
```

```bash
pnpm create next-app --example amp-story amp-story-app
```


Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).

Deploy the example using [Download](https://github.com/apps/maliek-galant)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/amp-story&project-name=amp-story&repository-name=amp-story)

