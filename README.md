# dev-tips

A collection of Development tips &amp; tricks.

## Git

### Undo rebase

[Stack Overflow](https://stackoverflow.com/questions/134882/undoing-a-git-rebase)

## React

### Render props pattern

[patterns.dev](https://www.patterns.dev/posts/render-props-pattern/)
[codesandbox.io](https://codesandbox.io/s/react-typescript-forked-8g63p?file=/src/App.tsx)

```tsx
// type for children function
interface Props {
  children(props: InjectedProps): JSX.Element;
}
```
