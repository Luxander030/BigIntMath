# BigInt Math library

## Made because the team that made the Math functions didn't think about making the same thing for BigInt

### Reason for existing

In my RPG game (Lux's RPG), I had to use BigInt because stats would inflate exponentially. A problem with that was with the fact that Math functions do *not* work with BigInt. So, glow and behold (but not really glow), I had to make a makeshift Math library for BigInt. However. What started as a library for `min`, `max`, and `clamp`, turned into a library I made *relativly* large. So enjoy, what I have now made, as my own BigInt Math library, named BigMath.

#### What to expect

Here, you will find 2 files. `BigIntMath.js`, and `BigIntMath.min.js`. The first file is the expanded version, and the second file is the minified version.

##### `BigIntMath.js`

Here, you will find all the different functions and all of their comments explaining what they do (in case you don't know whatever the hell they do)

##### `BigIntMath.min.js`

Minified version. Use it if you're going to src it.

#### How to SRC the minified version

In your HTML file (as this is how it is going to be so far, until I figure out how to use npm), put this code near the top or in the `<head>`:

``` html
<script 
    src="https://raw.githubusercontent.com/Luxander030/BigIntMath/refs/heads/main/BigIntMath.min.js"
    integrity="sha512-/GMcwFiIrMypFt7SAdUYmvoRStmMJx6AB23PlsPz71wx+pcfd1sBWy/giNmOw7BIOZZV1bcUzmqCZ6NFL7MHvg=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer">
</script>
```
