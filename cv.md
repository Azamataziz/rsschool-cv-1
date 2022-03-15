# Vyacheslav, Fyur

![Photo](./assets/img/photo-230x230.png "Photo")

**Hi, I'm Fyur a web developer**
I have been looking for something that I like for a long time, tried many different directions, they included: development of modifications, games, applications. I am currently studying Front-End development, I am also planning to study Back-End development. I like it and I am ready to develop in this direction.

## Skills

| Language / Framework | Level           |
| --                   | --              |
| HTML                 | Above average   |
| CSS                  | Above average   |
| JavaScript           | Above average   |
| Figma                | High            |
| Github               | Average         |
| Git                  | Average         |
| NodeJS               | Below average   |
| Webpack              | Low             |
| React                | Low             |
| Java                 | Below average   |
| Python               | Low             |
| Database             | Low             |

## Code Example

**JavaScript - [Replace With Alphabet Position](https://www.codewars.com/kata/546f922b54af40e1e90001da)**

```javascript
function alphabetPosition(str) {
  return str
  .replace(/[^a-z]/ig, "")
  .split("")
  .map((char) => char.toUpperCase().charCodeAt(0) - 64)
  .join(" ");
}
```

**JavaScript - [Clocky Mc Clock-Face](https://www.codewars.com/kata/59752e1f064d1261cb0000ec)**

```javascript
function whatTimeIsIt(angle) {
  const hours = Math.floor(angle / 30) || 12;
  const minutes = Math.floor((angle % 30 * 2));

  return String(hours).padStart(2, "0") + ":" + String(minutes).padStart(2, "0");
}
```

