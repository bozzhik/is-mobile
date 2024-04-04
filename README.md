# Overview

The `@bozzhik/is-mobile` variable is a utility designed to determine whether the current device is considered mobile, based on browser identification.

## Installation

To install the `isMobile` variable, you can use npm:

```bash
npm install @bozzhik/is-mobile
```

## Example

In this case, the desired component will be drawn based on the `device`:

```tsx
import {isMobile} from '@bozzhik/is-mobile'

function Component() {
  return isMobile ? <Mobile /> : <Desktop />
}
```
