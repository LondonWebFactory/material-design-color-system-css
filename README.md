# Material Design Color System CSS

I love the [Material Design Color System](https://material.io/design/color/the-color-system.html), but I hate typing the hexadecimal codes. I therefore decided to bite the bullet and spend some time converting the whole color system into CSS variables.

## Example
Check out the attached example.

## Usage

Place the code at the head of your CSS file and replace your CSS colors like this:

### Old CSS Code
`border:1px solid #757575;`

### New CSS Code
`border:1px solid var(--gray-600);`

## Top-Tip
I use VS Code and it gives a nice preview of the color.
