# REACT-TESTING

Small app for learning Jest and React testing library
NOTE: I was unable to set up Jest in Vite. See retro

## Retrospective

Would have been easier to start with CRA instead of Vite.
I followed the article in the sources, but there have been changes
for the latest version of Jest. It is clear that if you're going to
run tests for Vite, vitest is the way to go. With each new version of
Jest, there runs the potential of breaking changes and therefore the
transformations done in the config files must be updated.

Summary:
There is too much transformations to use Jest with Vite and a risk of
breaking changes with Jest releases. Use vitest with vite.

## Sources
- setting up jest in vite https://hung.dev/posts/jest-vite

Choosing between vitest and jest
- https://dev.to/mbarzeev/from-jest-to-vitest-migration-and-benchmark-23pl
- https://github.com/vitest-dev/vitest/issues/579