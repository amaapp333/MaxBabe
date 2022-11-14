# MaxBabe App
```js
import React, { useEffect } from 'react';

interface Props {
  className?: string;
  style?: React.CSSProperties;
  client: string;
  slot: string;
  layout?: string;
  layoutKey?: string;
  format?: string;
  responsive?: string;
  pageLevelAds?: boolean;
  adTest?: string;
  children?: React.ReactNode;
}

export function Adsense({
  className = '',
  style = { display: 'block' },
  client,
  slot,
  layout = '',
  layoutKey = '',
  format = 'auto',
  responsive = 'false',
  pageLevelAds = false,
  adTest,
  children,
  ...rest
}: Props) {
  useEffect(() => {
    const p: any = {};
    if (pageLevelAds) {
      p.google_ad_client = client;
      p.enable_page_level_ads = true;
    }

    try {
      if (typeof window === 'object') {
        ((window as any).adsbygoogle = (window as any).adsbygoogle || []).push(p);
      }
    } catch {
      // Pass
    }
    // eslint-disable-next-line react-hooks/exhaustive-deps
  }, []);

  return (
    <ins
      className={`adsbygoogle ${className}`}
      style={style}
      data-ad-client={client}
      data-ad-slot={slot}
      data-ad-layout={layout}
      data-ad-layout-key={layoutKey}
      data-ad-format={format}
      data-full-width-responsive={responsive}
      data-adtest={adTest}
      {...rest}
    >
      {children}
    </ins>
  );
}
```


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

