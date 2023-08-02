# Callout Component

The Callout component is a flexible, customizable component built with React and SCSS, designed to create a 'callout' or 'tooltip' like element in your application.

## Props

The Callout component accepts several props to customize its behavior and appearance:

- `children` (ReactNode): The content of the Callout.
- `backgroundColor` (string, default='white'): The background color of the Callout.
- `borderColor` (string, default='black'): The color of the border around the Callout.
- `pointPosition` (string, default='left'): The position of the callout point. Can be 'top', 'bottom', 'left', 'right'.
- `pointOffset` (string, default='2rem'): The offset of the callout point from the start of the Callout.
- `pointAlignment` (string, default='start'): The alignment of the callout point. Can be 'start', 'center', 'end'.
- `pointTranslate` (string): A custom translation for the callout point. If not provided, the point will be translated based on `pointAlignment`.
- `pointLength` (string, default='2rem'): The length of the callout point.
- `cornerRadius` (string, default='0.5rem'): The border-radius of the Callout.
- `borderWidth` (string, default='0.2rem'): The width of the border around the Callout.
- `pointWidthMultiplier` (number, default=0.5): A multiplier for the width of the callout point.
- `pointLengthMultiplier` (number, default=1): A multiplier for the length of the callout point.
- `style` (Object): Custom styles to be passed to the Callout component.

## Usage

Here's an example of how to use the Callout component:

```jsx
<Callout
  backgroundColor='#f5f5f5'
  borderColor='#333'
  pointPosition='right'
  pointOffset='3rem'
  pointAlignment='center'
>
  This is a callout!
</Callout>
```

You can then make adjustments as necessary to suit the specific style and requirements of your project.
