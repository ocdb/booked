# booked

Personal reading and library management system.

## Usage

```
Usage: booked [command] [subcommand] [options]

Commands:
	books			Manage books
	bookmarks		Manage bookmarks
	texts			Manage texts
	text-notes		Manage text notes
	quotations		Manage quotations
	words			Manage words
	tags			Indices of tags
	help			Use "booked help" for more information.

Database:
	export [format]		Create an export of the database. Supported formats: sh, sql, sqlite, db (default)
	import <file>		Import data from a file. Supported formats: sql, sqlite, db

Environment variables:
	BOOKED_DATA		Specify path of booked data (default "${XDG_DATA_HOME}/booked"; "${HOME}/.local/share/booked")
	BOOKED_RAINBOW		Enable or disable "rainbow_csv" style output (default "1")
	BOOKED_DELIMITER	Specify the string to use as a field delimiter on output (default " / ")
	BOOKED_SEPARATOR	Specify the string to use as a row separator on output (default "---")
	BOOKED_OWNED_INDICATOR	Indicator to display for owned books (default "+")
	BOOKED_READ_INDICATOR	Indicator to display for read books (default "+")
	BOOKED_EMPTY_INDICATOR	Indicator to display for empty fields (default "-")
```

## Dependencies

- bash
- sqlite3

## License

```
Copyright (C) 2025 ocdb

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
