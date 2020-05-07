# askit-css-js-html-examples
A collection of CSS, HTML and JS examples to popular intro-level questions

The example collection can be found in the `entries.json` file which is a JSON-formatted file containing a list of "entries". The format for each Entry is as follows:
```typescript
type Entry = {
    title: string;
    keywords: Array<string>;
    lines: Array<string>|string;
    description?: string;
    language: "css"|"html"|"javascript"|"typescript"
}
```
