Steps to repro:

1. `npm install`
2. `npm run build`
3. Open `dist/server/datadog/tracing/init.ts`
4. See second line `require("./absolutePathTest");` (expected `require("../../absolutePathTest");`)
