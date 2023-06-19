# my diary

bash-based diary - writes to current directory as YYYY/MM/DD.txt

## usage:
```sh
Usage: diary [date]
  date: YYYY/MM/DD (accepts /, -, ., ;, as delimeters)
```

## Setup / configuration

The diary requires some environment variables, that you can set either by adding them
to your `.bashrc`/`.zshrc`, or using [https://direnv.net/](direnv), or manually by preceding
the command with your environment variables.. (maybe ok for trying out)

Required environment variables to be set:

- `DIARY_DIRECTORY` - The directory that will be used to save your diary entries
- `DIARY_EDITOR` - The editor that will be used to edit your diary entries
- `DIARY_TEMPLATE` - A template that will be applied to every new diary entries

## License

MIT license
