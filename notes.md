links:
- [store rich text in db](https://stackoverflow.com/questions/53846018/how-to-store-rich-text-in-database)
  - maybe use for conversion before storing md in db?
  - also in SO article:
    - before sending to db:
      - convertToRaw, JSON.stringify
    - GET from db:
      - JSON.parse, convertFromRaw
- [lexical - alternative for DraftJS](https://lexical.dev/)
- [QuillJS docs](https://quilljs.com/docs/quickstart/)